## Specifications for ePortfolios

In the context of Perseids ePortfolios are a record of a person’s scholarly activities and learning achievements that includes direct references to the work that it represents. Their purpose is to guide progress and assess it.

In preparation for a Perseids-specific implementation we look at a number of existing specifications of different scopes:

#### Learning Record System

This is a very base-level system which purpose is to record everything with little information structure that goes beyond the characterization of each individual event.

#### Badges

Badges are bundles of more granular experiences, including other badges. The collections they represent can be set up as instructional units, singular actions or quantitative thresholds. Their recursive form (putting badges into badges) supports expression of curricula, syllabi and their components as badges and querying of progress towards their fulfillment.

#### ePortfolios

ePortfolios are supposed to be a full record of a person’s learning and scholarly achievements including auxiliary data, access management and different forms of representation. The defining attributes are their global scope and their summarizing character while at the same time providing access to source materials.

### Perseids

Perseids needs a system to either store summaries or continuously parse raw records of users activities to use as a base for portfolio functions. Given the potential computational cost of retrieval and aggregation of (versioned) records over multiple distributed systems, integration with a LRS like Tin Can API could be a more sensible approach. In addition, this enables recording of read-only activities without parsing server logs.

The micro-publication approach lends itself seamlessly to organizing and bundling into badges. Adequately designed badges can help learners to independently chose and navigate courses of study while providing educators quick access to their students progress. Researchers can track their own progress, find collaborators and student helpers through matching badges with a sought-for profile. The essential work is the design of a hierarchy of badges from single micro-publication to complete skill, insight or credited course.

While badges are in their nature decentralized, ePortfolios are monolithic and a means to communicate with institutions and to present the work stored in LRS and organized in badges as a coherent whole, as a transcript.

### Open Badges Architecture

#### Individual badges



#### Vertical and horizontal integration

Composition of badges from each other enables a hierarchies or learning trees and can be used to make explicit the different stages in learning a particular skill or the steps to fulfill a course requirement. Badges as thematic collection can be used to combine complementing input from different modalities and sources.

#### External sources

Including learning activities from external sources such as Pelagios, hypothesis.is, Memrise, digitized paperwork, etc. Can be entered atomically into LRS.

### ePortfolio Information model
