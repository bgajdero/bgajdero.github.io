---
layout: post
title:  "BRAMA - Bounded Rational Agent Motivation Architecture"
date:   2023-01-01 09:41:09
author: Bart Gajderowicz
header:
  overlay_color: "#600"
#   image: "/assets/img/bartg.jpeg"
#   teaser: /assets/img/bartg.jpeg
tag-name: ontology  ai-planning agent-based-simulation goal-based-reasoning bounded-rationality
---
<!-- ![image tooltip here](/assets/img/bartg.jpeg) -->
In classical AI planning, replanning strategies are used to reevaluate a plan during execution. For human-like agents, goal preferences and emotions play an important role in evaluating a plan’s progress. However, most existing systems rely on predefined goal ordering and a static association between an event and its emotion-based utility calculation. During execution, utility of individual actions are used to trigger the replanning process. This approach assumes that a complete sequence of actions can be generated, preferences are known, are transitive, the mood-based utility of every action’s outcome is known, and a replanning condition is well defined. This paper presents an alternative approach, one that does not make assumptions about the agent’s or observer’s omniscience about factors influencing decision making. Our approach recognizes the bounds that limit the agent and observer equally. To accommodate these limits, first, human-centric goal ranking are grounded in a domain-specific mapping to Maslow’s hierarchy. Second, a new replanning condition is proposed with dynamically changing mood-based utility during plan execution.

The BRAMA framework is meant to emulate decisions made by a seemingly irrational human-like agent with the use of a rational reasoner. In this chapter, BRAMA extends a single decision rational reasoner using a utility function that incorporates rational and non-rational factors influencing human decision making. 

For single decision making, BRAMA represents a domain as a state and a set of actions along with related terms. Future actions and outcomes are independent from past actions and outcomes. The outcome of a choice is true if the choice was made and not true if the choice was not made. Each individual action is viewed as an alternative action, and each outcome as an independent alternative outcome (Hansson2005). For example, either a person decided to go for a stroll with an umbrella, without an umbrella, or did not go for a stroll at all. Imagine they went for a stroll. If it was not raining, the outcome is a state where the person went on a stroll, has an umbrella, and enjoyed the stroll. If it was raining and they did not bring an umbrella, then the outcome is a state in which they went on a stroll, did not have an umbrella, and did not enjoy the stroll. 


The nature of outcomes in single decision theory can be put more strongly: the outcomes of alternative choices are mutually exclusive of other choices available or will be available in the future. There are several ways to interpret choices and outcomes. For example, like expected utility theory (EU), prospect theory (PT) also considers choices as mutually exclusive. However, unlike EU, there is no extension to PT that provides support for a time dimension and interdependence of choices. Hence, decision theory incorporated in BRAMA is based on the EU model of utility and decision making. 