---
layout: post
title:  "OSSN - Ontology for Social Service Needs"
date:   2023-01-01 09:41:09
author: Bart Gajderowicz
header:
  overlay_color: "#600"
#   image: "/assets/img/bartg.jpeg"
#   teaser: /assets/img/bartg.jpeg
tag-name: ontology  social-services needs
---
<!-- ![image tooltip here](/assets/img/bartg.jpeg) -->
The Ontology of Social Service Needs (OSSN) represents service provisioning from the perspective of a cognitive, goal-driven client to evaluate services based on how well they remove a client’s constraints and meet client needs.

Browse the [OSSN here](/ossn-doc-html/index-en.html).

OSSN is grounded in real-life requests made by participants of a Housing First intervention program, resulting in 58 different goal types. Each goal is mapped to one or more basic human needs defined by Maslow’s Hierarchy, as inferred from the goal’s type, the motivation behind it, and the client’s demographics. Finally, as clients interact with service providers, three different types of goal orderings are required to capture goal ranking during the planning and execution phases. These include the client’s preferred order, Maslow’s Hierarchy order, and the practical order imposed by the logistical constraints of service providers.


The Ontology of Social Service Needs (OSSN) is an ontology of needs for human-like agents that interact with a social service provisioning system. The ontology is based on data about the types of requests made by social service clients in a real-life intervention program. Existing ontologies focus on the process of service delivery, categorizing services and resources to ensure an efficient assignment of services to incoming clients. The ontology allows for the evaluation of service provisioning from the client’s perspective. By identifying goals of clients and the services that satisfy them, it is possible to create a high-fidelity client emulation model for the purpose of social service evaluation.

The ontology is developed using the ontology engineering method. Ontology engineering is a systemic way of constructing and evaluating an ontological representation of a domain. First, motivating scenarios are identified to define the scope and objectives the ontology is meant to resolve. Second, a set of informal competency questions ore defined which the ontology should answer. Third, an ontology is constructed that represents knowledge required to answer identified competency ques- tions. Finally, the informal competency questions are translated into formal competency questions using the terminology and formal language that allows for the automation of querying identified questions. The work presented here represents the ontology in [OWL syntax](https://www.w3.org/OWL/). The SPARQL query language is used to represent formal competency questions, with a complete evaluation in