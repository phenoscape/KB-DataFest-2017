_Note: the published version of this document is also available at <https://hackmd.io/s/Sk6Xa7Eq-#>._

# Call for Participation:
# Computable evolutionary phenotype knowledge: a hands-on workshop

## Synopsis

The [Phenoscape] project is hosting a hands-on workshop on Dec 11-14, 2017,
at Duke University in Durham, North Carolina.

Evolutionary phenotype data that is amenable to computational data science,
including computation-driven discovery, remains relatively new to science.
Therefore use-cases and applications that effectively exploit these new
capabilities are only beginning to emerge. If you are interested in
discovering, linking to, recombining, or computing with machine-interpretable
evolutionary phenotypes, this is the workshop for you! 

The event will bring together a diverse group of people to collaboratively
design and work hands-on on targets of their interest that take advantage and
promote reuse of [Phenoscape]'s online evolutionary data resources and
services. The event is designed as a hands-on unconference-style workshop.
Participants will break into subgroups to collaboratively tackle self-selected
work targets.

To apply to participate in the event, please fill out the following form
by Oct 9, 2017: <https://goo.gl/tt18gR>
Travel sponsorship is available but limited, as is space. We expect to notify
applicants about acceptance starting one week after application due date.

Updates will be posted to the workshop repository on Github:
<https://github.com/phenoscape/KB-DataFest-2017>

## Who should participate

We are looking to assemble a diverse group of people, including
developers, computer scientists, data scientists, and domain experts from
a variety of relevant fields, such as evolutionary science, ecology,
biodiversity, biomedical sciences, and bioinformatics. Example personas we are
looking for include, but aren’t limited to the following:
* Biology / biodiversity / ecology scientist
* Evolutionary medicine researcher
* Software / tool / resource developer
* Data semantics researcher
* Data product developer
* Training / documentation specialist
* Visual and data interaction designer

Everyone participating in the event must agree to adhere to its [Code of Conduct].

## Scope

We are keeping the scope into which work targets at the event are expected to
fall intentionally broad, so as not to limit participants' ideas apriori.
That said, we generally expect work targets to use data and/or the
computational services of Phenoscape's online resources (see [About the KB]
below) in some way, whether through available APIs or not. 

Possible targets can take many forms. Examples include, but are not limited to
the following:
* Connecting one's data, tool, or database to the KB (to address a research
  question, or to interconnect a community resource);
* Increasing visibility into the KB data, such as through visualization,
  mashups, or apps;
* Devising resources that make it easier to reuse the KB's data or
  capabilities, for example in the form of vignettes;

In general, work targets that align well with participants’ own professional
interests are generally more desirable than others that do not, because they
typically get more traction, and are more likely to be continued in some way
after the event.


## Background

Efficiently repurposing, integrating, and mining the vast stores of phenotype
data has long been hampered by the limited amount of data accessible online
in standard formats, and by the challenges involved with enabling machines to
compute with data that is largely recorded in natural language text
descriptions. A variety of advances has begun to address these challenges,
including powerful knowledge representation technologies, shared domain
ontologies, very fast machine reasoners, and various tools accelerating the
construction of large databases of ontology-linked phenotype data. The results
emerging from these advances provide new opportunities for computation-driven
data science with phenotype data, and specifically for natural biodiversity a
unique resource for data science-enabled phenotype descriptions is the
[Phenoscape KB].

### About the Phenoscape Knowledgebase (KB)

The Phenoscape Knowledgebase (KB; <http://kb.phenoscape.org>) is a resource
containing evolutionary phenotype data from more than 150 comparative
morphology studies, with a focus on the vertebrate fin-to-limb transition and
comparative fish morphology. The KB offers programmable (API) access to natural
language phenotype descriptions annotated with formal ontologies so that
machines can understand and compute with the semantics of descriptions at
scale. Using shared ontologies for morphological, spatial, and other
requisite domain knowledge, the KB links these data to phenotypes reported in
genetic perturbation studies for pertinent model organisms (zebrafish and
mouse), and to human genetic disease phenotypes.

For query answering the KB uses machine reasoning to match data by its
semantics. The API also gives access to other machine reasoning-based
algorithms. These include synthesizing characters and states that are implied
by but not expressly asserted in the original studies; and finding evolutionary
phenotype transitions semantically similar to gene phenotypes.

Further details, including relevant publications, KB data model, and API
documentation can be found at the workshop wiki:
<https://github.com/phenoscape/KB-DataFest-2017/wiki/Learning-about-the-KB>

### Motivation and Goals

The overall objective of the workshop is to foster broader adoption, reuse,
and interoperability of computable phenotype data in general, and of the
data in the [Phenoscape KB], and its machine reasoning capabilities, in
particular.

More specifically, the event aims to enable more tools, resources, and
researchers to better integrate with and take advantage of the data and
computational services provided by the KB. As a desired side-effect, this
will ultimately help the Phenoscape team to establish concrete use cases
driven by community needs, inform requirements, and prioritize targets for
future development of the KB, its API, and its services.


## Organizing Team

* Scott Chamberlain (rOpenSci)
* Matthew Collins (University of Florida, iDigBio Informatics)
* Melissa Haendel (Oregon Science & Health University, Monarch Initiative PI)
* Hilmar Lapp (Duke University, Phenoscape co-PI)
* Emily Jane McTavish (UC Merced, Open Tree of Life)

[Phenoscape]: http://phenoscape.org
[Phenoscape KB]: http://kb.phenoscape.org
[About the KB]: #about-the-phenoscape-knowledgebase-kb
[Code of Conduct]: https://github.com/phenoscape/KB-DataFest-2017/wiki/Code-of-Conduct
