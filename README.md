# EduCOR: An Educational and Career-Oriented Recommendation Ontology
## Context

EduCOR is an educational ontology for personalized recommendation learning systems that is based on a learning path and user profile. It represents the key components for a personalized learning system based on our requirement analysis.

## Ontology page

Our ontology page with the full documentation can be found in [http://ontology.tib.eu/educor](http://ontology.tib.eu/educor/)

## Abstract

With the increased dependence on online learning platforms and educational resource repositories, a unified representation of digital learning resources becomes  essential to support a dynamic  and  multi-source learning experience. We introduce the EduCOR ontology, an educational, career-oriented ontology  that  provides  a  foundation for representing  online  learning  resources for personalised learning systems. The ontology is designed to enable learning material repositories to offer learning path recommendations, which correspond to the user’s learning goals, academic and psychological parameters, and the labour-market skills that are achieved from the learning  path. We present the multiple patterns that compose the EduCOR ontology, highlighting its cross-domain applicability and integrability with other ontologies. A demonstration of the proposed ontology on the real-life learning platform [eDoer](edoer.eu) is discussed as a use-case. We evaluate the EduCOR ontology using both gold standard and task-based approaches. The comparison of EduCOR to three gold schemata, and its application in two use-cases, shows its coverage and adaptability to multiple OER repositories, which allows generating user-centric and labour-market oriented recommendations.


## Visualisation

You can see a visualisation of the master branch educor.ttl using [WebVOWL](http://ontology.tib.eu/educor/visualization)

This is an overview of the classes in EduCOR ontology.
![](EduCOR.png)

Through our requirement analysis we identified the key components for our representation. These key components formulate homonym patterns. Each pattern of the ontology is highlighted individually:

A: Educational resource pattern

B: Skill Pattern

C: Knowledge topic Pattern

D: Test pattern

E: Learning path pattern

F: Recommendation Pattern

G: User profile pattern

## Use-Case

### General

An OER repository owner could utilise the EduCOR ontology to model the learning materials in their repository.
The repository serves learners through a standard search and information retrieval functionality, which is to be ready for integrating with an automatic decision-support system in the future with minimum to zero adjustments of the repository structure.

### Application Specific

We also used our ontology in specific use case, in the development of [eDoer](http://edoer.eu) platform, an open learning recommender system prototype, focusing on Data Science related jobs.

On the eDoer platform, learners can set their target job, and the system will provide them with a list of skills they need to master for that particular job. Learners are offered to select one or more of those skills and set them as learning objectives. Moreover, learners can search through other existing skills and add additional learning goals. They can also set their learning preferences (type of learning materials, the length of content, etc.), which results in personalised learning content recommendations. The generated learning path includes the target skills and the necessary knowledge topics covered for each skill. Subsequently, users receive OERs for each of the knowledge topics, which can be viewed, rated, and changed. Based on the users' feedback (i.e. ratings) on each of the recommendations, eDoer updates the users' preferences to capture any changes in user preferences. Moreover, there are various assessments available both on skill and knowledge topic levels that provide means to monitor the learning process.

You can watch a demo of eDoer here:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/5PRcUgNa7tA/0.jpg)](https://www.youtube.com/watch?v=5PRcUgNa7tA)

## Ontology Competency Questions

EduCOR seeks to assist OER repository owners and e-learning system designers when planning to include personalised learning features in their systems.

Q1:   How to retrieve OERs from multiple sources for a learning goal?

Q2:   How can a personalized OER difficulty be chosen for the user?

Q3:   How to provide an OER to a user with a specific access mode?

Q4:   How to retrieve required OERs for a certain job skill?

Q5:   What is required to generate a personalized learning path?

Q6:   How to personalize a learning recommendation based on a user’s psychological state?

## Tools used during development

Ontology Editor: [Protege 5.5.0](https://protege.stanford.edu/products.php#desktop-protege)
