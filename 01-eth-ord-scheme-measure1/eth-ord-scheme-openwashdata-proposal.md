# Proposal full title

Open WASH data by building Open Science Competencies and Community

Proposal Acronym: openwashdata

# Background and Motivation

## The Water Sanitation and Hygiene (WASH) Sector

The goal of the Water, Sanitation, and Hygiene (WASH) sector is to
reduce the burden of disease by providing contaminant water in
sufficient quantities, safe toilets that are hygienic and affordable, as
well as solid waste management to reduce the spread of vectors
(e.g. rats), especially within urban areas. Practitioners in the field
produce several types of data: 1. Geodata (e.g. the location of a water
pump along with data on its functionality); 2. Household data
(e.g. demographic data related to income and a family’s willingness to
purchase a toilet); 3. Operational data (e.g. the number of trucks and
the type of waste they deliver to a dumpsite); or 4. Experimental data
(e.g. the concentration of pathogens that die as a function of chlorine
added to a water sample). All of these data are important to design
programs and policies, and of course publish papers. However, despite
being technical experts, professionals working in the WASH sector are
not well-versed in the computational tools for research data management,
including data analysis, visualization, or communication. They have not
been exposed to sharing data following FAIR data principles and would
not know where to start \[1\]. Typically, research projects in the WASH
sector all have a common data management and publication workflow:

1.  Primary data is collected using survey tools or spreadsheet-based
    data collection tools
2.  Secondary data is shared by email, or using cloud-based tools file
    sharing tools
3.  Data is stored in spreadsheet-based software
4.  Data analysis is performed in spreadsheet-based software or in
    scripted proprietary software
5.  Results are copied and pasted into documents written in office word
    processing software
6.  Reports are exported to PDF documents
7.  PDF reports are published on funders websites, or in an academic
    publication which may be hidden behind a paywall making it difficult
    for practitioners without specialized subscriptions to access it
8.  Data remains unpublished or may be linked to an academic publication
    as an appendix
9.  If data is published, then in non-machine readable formats without
    metadata or documentation

Due to this lack of computational competency and/or data literacy, ORD
practices that allow (research) results to be disseminated, including
reproducible publications, data, software, hardware and protocols, are
not employed. There are initiatives that have started to establish data
standards, but they are either limited to one specific topic (e.g. Water
Point Data Exchange \[2\]) or are lacking ORD practices themselves as
recommendations are not turned into reusable formats (e.g. \[3\]).
Further, none of these initiatives address the gaps in skills and
competencies that are needed to employ standards. When ORD frameworks
exist, then they are top-down initiatives by larger international donors
or development banks \[4\], rather than grassroots approaches and
community-driven initiatives.

The benefits for academics to apply ORD practices to their work are well
researched and understood \[5\], but are not as clear for professionals
that are working at the policy, implementation or evaluation components
within a WASH project. As a result, data remains unpublished (or
published not following FAIR principles \[1\]), collaboration is
stifled, resources are wasted, and the wheel is constantly reinvented at
extensive cost to donors and project beneficiaries. Further, the lack of
competencies can make it difficult to establish partnerships between
researchers applying ORD practices and partners that are not \[6\].

## Data Science @ Global Health Engineering

One of the first people hired by Global Health Engineering once the
position was created, was an Open Science Specialist. \[TODO: publish
Job Description on <https://github.com/Global-Health-Engineering/>\]. As
a natural extension, we designed and now offer an undergraduate course
for engineers which is the first of its kind at ETH: Research Beyond the
Lab – Open Science and Research Methods for a Global Engineer
(141-8102-00L, FS2022) \[7\]. In the first half of the course we teach
the methods required to conduct real-word data collection and in
parallel, we teach students about open science principles with a focus
on: (1) Collaboration and version control with Git and GitHub, and (2)
Research data management (i.e. open licenses, documentation and
metadata). Students work in groups of three to design their own data
collection tools (i.e. questionnaire, data collection tools for waste
measurement) and collect their own primary data in collaboration with
Entsorgung und Recycling Zurich (ERZ). In the second half of the course,
we teach data science skills using R and the RStudio IDE. Lectures
follow teaching methods of participatory live coding, peer instruction,
and pair programming, with the majority of time spent on practising the
learned competencies on their own collected data. At the end of the
course, every group submits one group report contained in one git
repository that was created collaboratively using git and GitHub. This
course was the first step in developing a cohort of students that could
then take on larger research, apply reproducible workflows and ORD
practices to tasks within our group or elsewhere.

For practitioners, a “Building Communities to engage in ORD practices”
workshop has been hosted three times; 181 email contacts were gathered
through Zoom registrations. The workshop itself and all its materials
are published under open licenses (CC-BY) \[8\]. A Slack Channel was
established which 30 participants joined, and a Twitter handle
(<https://twitter.com/washdata>) was started to share news about the
further development. Of those that participated in the three workshops,
56 filled out a questionnaire after the workshop which helped us to
gather an understanding about their starting point and interest in the
topic. The results show that:

-   more than half of the participants had at least some experience
    using a programming language, while also about half had no
    experience using R statistical software
-   Nearly three-quarters of the participants store data in MS Excel
    Worksheets
-   Non-Governmental Organisations and Academia made up 60% of the
    participants
-   Only one participant expressed that there would be no interest in a
    12-week course on data science

We asked participants about their perceived barriers for participation,
where fees and time availability were perceived as barriers for the
majority of participants. Therefore, we are pursing this Explore Call to
design free online teaching material to follow up on these novel,
self-funded offerings.

## Problem Statement

The Global Health Engineering group at ETH Zurich works at the nexus of
WASH research, anti-colonial development, and as a tool to achieve the
latter two, open science. Yet, having worked internationally in the WASH
sector as researchers, teachers, and consultants, we have seen how many
resources are wasted in producing data, how much data is lost before it
is made accessible, and how unmanageable the data that is accessible,
is. This is equally true for colleagues in the Global South as it is for
colleagues in Switzerland. We also know how intimidating data science
can seem either because of the technology, the culture (which appears to
many as being mostly young, white, and male), or the fear of failure.

*The goal of this program therefore, is to develop a) a community of
international and local students, and practitioners who are empowered to
engage in open science concepts in order to b) create a platform to host
WASH-related data which can be accessed and analyzed openly while c)
researching the technical, pedagogical, and political factors that will
allow us to expand and replicate the program to become the most
comprehensive WASH hosting and training entity in open science.*

# ORD Project plan

This Project consists of 5 main Work Packages: WP0: Infrastructure
design and installation; WP1: Mobilize community; WP2: Mobilize data;
WP3: Data cleaning; and WP4: Data sharing and data publishing, which are
elaborated in detail below.

## WP0: Infrastructure Design and Installation

<div>

> **Goal: Prototype ORD tools at ETH for teaching and collaboration that
> can sustainably run and be used beyond the scope of the Explore
> projects funding**
>
> **RQ 0.1:** What are the costs and requirements for ORD tools to be
> hosted and maintained within the ETH domain?
>
> **Activity 0.1:** Collaborate with ETH IT Services to establish
> Virtual Machines and RStudio Server (open source version) for 50
> learners
>
> **Activity 0.2:** Evaluate the advantages and disadvantages of three
> open source tools for communication (Slack, Discord, Matrix Protocol)
>
> **Activity 0.3:** Compare hosting costs and technical overhead
> (maintenance) of RStudio Cloud by RStudio PBC with Virtual Machines
> hosted at ETH Zurich.

</div>

The goal of this WP is to prototype ORD tools for teaching and
collaboration. We will use open source infrastructure that is commonly
applied throughout modern data science and statistics classes \[9\],
including: R and RStudio Server for programming; Quarto scientific and
technical publishing system for authoring \[10\]; Git and GitHub for
version control and collaboration; Matrix protocol for real-time
communication ; Mailing list server for regular updates directly to
email.

These tools are not only necessary for teaching, collaboration, and
community building for this project proposal, but are tools that we use
for teaching purposes at ETH, and for collaboration within our research
group. For long-term sustainability of this project, we need this
infrastructure to be hosted and maintained with ETH on self-hosted
servers. This work package and our learning will contribute to the
greater understanding of how open source software can be integrated into
the ETH infrastructure environment. WP0 will start before the other WPs,
but will also continue in parallel as the needs and challenges of the
growing community emerge and are accounted for.

## WP1: Mobilize Community

<div>

> **Goal: Create and grow an international network of data-curious
> practitioners and students who may be interested in pursuing one or
> more of the subsequent activities.**
>
> **RQ 1.1:** What are the demographic and competence characteristics
> associated with engagement as a function of communication
> channel/format?
>
> **Activity 1.1:** Advertising the opportunities to contribute to the
> openwashdata community
>
> **Engagement 1.1:** Read email, post, message and click to find
> information about the openwashdata program
>
> **RQ 1.2:** What are the expressed and observed successes and
> challenges associated with live-coding events and how do these
> translate into program retention outcomes?
>
> **Activity 1.2:** Weekly live-coding event to engage early adopters
> and demonstrate the low-barrier of entry to the data-sceptical
>
> **Engagement 1.2.1:** Watch a live-coding event
>
> **Engagement 1.2.2:** Follow along live-coding event

</div>

In WP1, we will mobilize WASH practitioners to join and contribute to
the openwashdata community. Specifically, we will engage with our vast
network of WASH students and professionals around the world by promoting
the opportunity to a) learn more about open science tools and practices
for improving the accessibility of their own work and, for the less
engaged, b) offer the opportunity to publish their data in an open
format. Although option a) is the more sustainable and preferable
option, we recognize that the culture, tools, and terminology around
data can be intimidating. We therefore hope to create as low a barrier
to entry as possible, and hopefully, through small, consistent steps,
move even the most reluctant, paper-loving researcher, through
introductory steps, building their confidence and interest in the
process.

We will engage through social media, email lists, professional networks
(combined 30 years’ experience in WASH) and the established
communication tools (combined 30 years’ experience in WASH). We will
advertise the opportunities available to become a data sharer, data
cleaner, or data publisher and communicator , and how to gain
recognition (through permanent Digital Object Identifiers), and improve
ORD practices, which, we anticipate will be attractive to the broader
network, in exactly that order.

A weekly live coding stream using Twitch and Twitter will be one of our
first entry points. Using the hashtags \#TidyTuesday \#openwashdata, we
will advertise the weekly events in which an untidy (in our context
unstructured data set) is shared and community members are challenged to
tidy the dataset and produce visualisations and other data communication
products. The live stream will use participatory live coding as a
teaching technique, and participants can use the infrastructure provided
(WP0: Prototyping ORD tools) to follow along the live coding \[11,12\].
These events are not designed to convert die-hard pen-and-paper
practitioners into GitHub stars; rather, they are an opportunity to
create low-stress environments for learning (no testing, no need to show
results), identify community leaders who want to take on a more
important role in dissemination, and share the magic of a
well-structured data set.

There is an increasing understanding of the relevance of communities for
open science and teaching \[13\] and we can see an increased pace at
which they are being started for academics \[14–16\]. As active members
of these communities, we will leverage the materials and experiences
that already exist to build the openwashdata community. We will
contribute back by sharing our experiences with the communities through
open channels (blogs, communication tools, open access journals).

## WP2: Data sharing

<div>

> **Goal: Solicit and receive interest in providing data to be published
> openly; develop an easy-to-use data-collection protocol and tool;
> receive data from interested partners.**
>
> **RQ 2.1:** What are the factors that predict willingness to share
> data and/or engage in self-directed data sharing
>
> **Activity 2.1:** Create a GitHub repository template for submission
> of data, and documentation and metadata that follows general ORD
> standards.
>
> **Engagement 2.1:** Watch video/ read documentation outlining data
> submission procedure
>
> **Activity 2.2:** Reach out to participants identified in WP1 as well
> as pre-identified colleagues who have, but have not made their
> research data open
>
> **Engagement 2.2.1:** Submit data unassisted.
>
> **Engagement 2.2.3:** Engage with program team to assist with
> submission
>
> **RQ 2.2:** What are the observed and stated challenges associated
> with transferring data to a GitHub repository?
>
> **Activity 2.2:** Produce a suite of learning materials (videos
> tutorials, printed instructions, support-group platorms, Wikis) that
> enable interested parties to easily share research data

</div>

In WP2, we will identify community members that are open to share their
data with the community to become “Data sharers”. We established the
openwashdata GitHub organisation with a GitHub repository template
(<https://github.com/openwashdata/openwashdata>) as the entry point for
data submission.

As a first activity, contributors will create an account on
<https://github.com> and will share their GitHub username with the
project team who will add them to the openwashdata GitHub organisation.
The project team will then use the openwashdata template to create a new
public repository in the openwashdata GitHub organisation with push
access to the GitHub username of the contributor. The contributor uses
the GitHub Graphical User Interface (GUI) to add their raw data to the
`~/openwashdata/data/raw_data/` directory and commit the changes to
capture their submission as a contribution to the repository. As another
activity, they are asked to create a persistent digital identifier on
<https://orcid.org/> (an ORCID iD) and add their family names, given
names, and ORCID iD to the CITATION.CFF in the root directory by editing
the file using the GitHub GUI.

These are the minimum required steps to contribute data to the
community. Instead of receiving data by email, we ensure that
contributors are exposed to version control and collaboration with
GitHub and introduce the topic of open and reproducible workflows as an
importance ORD practice \[17\]. We also ensure that each contributor can
be credited for their submission appropriately downstream of the data
sharing.

The highly technical nature of the industry standard reproducibility
tools presents challenges for novices. Therefore, we will use applied
examples, guided instructions and lots of practice to teach
reproducibility as part of the data sharing process \[18\].

Data will be shared come by community members engaged in WP1 as well as
from pre-identified sources. First, the unpublished GHE data is not
currently accessible. Second, the data that was generated during
Prof. E. Tilley’s 5-year tenure at the University of Malawi, Blantyre.
As a research group within the ETH domain Eawag/Sandec’s research
produces scientific knowledge that is paramount for the WASH sector.
However, until this point none of this research has followed ORD
practices and little of the highly valuable data that is generated as
part of projects is published. As both applicants have previously worked
at Eawag/Sandec and have long lasting partnerships, we will engage with
current and former Eawag/Sandec colleagues as a third source of
guaranteed data for this WP.

## WP3: Data cleaning

<div>

> **Goal: Facilitate user-directed data cleaning (including
> documentation and metadata) to produce a first set of analysis-ready
> open data sets**
>
> **RQ 3.1:** What is the interest of openwashdata community members to
> contribute to data cleaning activities?
>
> **Activity 3.1:** Invite and encourage openwashdata community members
> to contribute to data cleaning activities.
>
> **Engagement 3.1:** Read email, post, message and click to find
> information about the data cleaning activities
>
> **RQ 3.2:** What are the most common and most difficult-to-remedy data
> cleaning issues among openwashdata community members?
>
> **Activity 3.2:** Categorise provided data sources into rubrics of
> “effort for cleaning” and “impact of clean data” to prioritise which
> data to invest in first.
>
> **RQ 3.3:** What is the program adherence rate among openwashdata
> community members between previous WPs and WP3; and between the
> different modes of engagement within WP3?
>
> **Activity 3.3:** Teach a 7-week synchronous online course (3 hours
> per week) for openwashdata community members to learn the competencies
> needed to clean submitted data.
>
> **Engagement 3.3.1:** Attend at least one week of training
>
> **Engagement 3.3.2:** Complete all 7 weeks of the online course
>
> **Activity 3.4:** Host two online hackathons where selected data sets
> are cleaned by participants.
>
> **Engagement 3.4:** Attend a hackathon
>
> **Activity 3.5:** Host a 2-day workshop in-person workshop at a sector
> relevant conference with an element of capacity building
>
> Engagement 3.5: Attend 2-day workshop

</div>

The journey for a “Data sharer” which started in WP2 can end there or
continue into the role of a “Data cleaner” that actively supports WP3
either by using their data cleaning competencies (e.g. hired Research
Assisstant) or by obtaining the competencies after participating in the
learning events offered as part of this WP3. At this stage, other
community members can also become “Data cleaners” without having
submitted their own data in WP2.

As submitted data will vary in its effort to clean and the perceived
impact of clean data, we will categorise the submitted datasets and use
a decision support mechanism to decide which data sets are prioritized
for data cleaning. Shared data will largely be unstructured and we will
follow advice by \[19\] who suggest a minimal structure to share data
for analysis. The GitHub repositories created from the template as part
of WP2 will be used at this stage to add documentation and metadata in
the form of machine-readable codebooks describing each data file. The
project consortium brings in the expertise of the swissdata project,
which aims at improving the machine readability of publicly available
data (<https://github.com/swissdata/demo>) which follows similar goals
to this project. We will use open material to teach open standards
commonly used for reproducibility \[20\] and established guides to build
a better basis for formatting data in spreadsheets \[21\] and how to get
them ready for sharing \[22\].

Data cleaning processes will make up a large part of the workload for
this project. Without the support of the community, it will be
unfeasible to clean all submitted data sets within its duration. Rather
than ticking a box next to a number for cleaned datasets, our goal is to
motivate the community to engage in the data cleaning processes
themselves. We do that through teaching activities, such as a free
7-week online course, hackathons, and workshops at conferences. These
teaching activities will provide community members with the necessary
competencies to clean data themselves and we will have enough resources
from WP2 to use as examples. Beyond this, we hope to create enough
interest in the value of the collected data sets to also engage with the
greater reproducibility communities and R user groups in Switzerland
(e.g. Swiss Reproducibility Network) and internationally (ReproHack,
R4DS Community, AfricaR R user group, R-Ladies, Minority R Users, The
Turing Way, etc.).

## WP4: Data publishing and communication

<div>

> **Goal: Increase reach and impact of data by making it citable and
> creating data communication products**
>
> **RQ 4.1:** How does engagement with, and citation of data, increase
> by providing it following FAIR principles for data sharing and
> providing user-friendly mechanisms for discovery?
>
> **Activity 4.1:** Publish GitHub repository containing data and code
> in general-purpose long-term archiving repository Zenodo.
>
> **Activity 4.2:** Prepare data communication products using published
> data to generate new insights and results.
>
> **Activity 4.3:** Prepare R Data Packages for published data sets with
> the most promising reuse potential
>
> **Activity 4.4:** Aggregate published data sets into websites that are
> data warehouses and data catalogues

</div>

Where WP2 ensures that data is shared and WP3 brings it into an
analysis-ready format, WP4 adds the layer of data publishing and
communication. We understand data publishing as archiving of data in a
long-term repository with curated metadata verified by the community
\[19\], and data communication as the process of using analysis-ready
data generate new insights and communicating them through articles,
presentations, interactive documents, websites, and books. Once again,
community members that have become “data sharers” and “data cleaners”
can become “data publishers and communicators” to learn the final steps
of the process of making their data accessible following FAIR data
principles \[1\].

The GitHub repository that was created for the individual data set is
archived and published on Zenodo, a general-purpose open repository
operated by CERN and recommended by the the Swiss National Science
Foundation (SNSF) as a data repository for long-term archiving and for
making it citeable \[23\]. The publication process is straight-forward
as Zenodo has a GitHub integration and the required documentation and
metadata has already been generated as part of WP2.

To highlight the potential of publishing analysis-ready data openly, we
will use the quarto framework to produce websites that highlight the
research products. The use of quarto allows others to apply their
knowledge within the R programming language that we teach, but also with
Python, Julia, and Observable (JavaScript), making this the most
inclusive and comprehensive data communication framework that exists.

The project aims to produce several websites, but at least, a (1) Global
Health Engineering data warehouse, which highlights self-archived
publications, data, notebooks, and further analysis, (2) openwashdata
data catalogue, which provides a website with a searchable table of all
data sets that are submitted, cleaned, and published by the openwashdata
community. (3) R Data Packages and Research Compendia for the most
promising data sets that were published \[24\].

# Impact

## Sustainability

Extremely. Although this is the first phase and highly experimental, it
has the potential to generate not only a significant amount of data but
also much needed knowledge about the barriers, needs, and challenges
associated with moving a very decentralized, traditional discipline
forward in it’s understanding and appreciation of Open Science
principles and ORD practices. We are confident that we will identify
leaders, both at ETH and internationally, who will be crucial to
extending and scaling up future iterations of this work. By opening the
door and seeing who comes in, we can identify the people, organizations,
and programs that are interested in building on or replicating this work
in the future either through their own networks, as student projects, or
through formal funding mechanisms.

## Addressing a critical problem

Despite the fact that hardware and software is more expensive, harder to
access, and more difficult to support across much of the Global South,
students and researchers have become increasingly dependent on
commercial products that are oftentimes corrupted, pirated, or unstable.
At the same time, the global community is demanding increasing
quantities of data against which payments, punishments, and progress are
judged. Researchers without the skills necessary to meet the
increasingly open scicnece requirements of journals will be left with
fewer publishing options. Empowering the WASH sector with the skills and
data necessary to work openly is the only way to achieve the SDGs.

## Collaborative approach

Our proposal is not only open to all research disciplines, thematic
areas, geographical locations, and levels of expertise with respect to
data literacy, computational competencies, or statistics knowledge, but
we encourage and rely on diversity. To illustrate they diversity we
expect, we have designed four learner personas (Table 1). Writing
learner personas for teaching programming is a concept established by
\[25\] and is a crucial step in understanding the needs and expectations
of the participants.

| persona | in brief                                                                                                                               | domain knowledge | programming knowledge | contribution motivation |
|:--------|:---------------------------------------------------------------------------------------------------------------------------------------|:-----------------|:----------------------|:------------------------|
| Palesa  | Pit emptying business owner that is tired of others asking her for her business data.                                                  | competent        | novice                | low                     |
| Yua     | PhD student that wants to use her programming expertise to support the community.                                                      | novice           | expert                | high                    |
| Mandla  | Master’s student who wants to learn how to use R for data analysis and git version control.                                            | competent        | competent             | high                    |
| Asim    | Senior Researcher with a few years left to retirement who wants to share his career’s worth of data with as little effort as possible. | expert           | novice                | low                     |

Overview of learner personas designed for openwashdata community.

**Palesa** is leading a pit latrine emptying business with 20 employees
and 6 vacuum trucks in Lusaka, Zambia. She has finished high school and
did an apprenticeship in business administration. She is also a
representative for the Sanitation Workers Association of Sub-Saharan
Africa. She knows how to setup a data table using spreadsheet based
software. She tracks all her business information using this software,
but has never had any formal introduction into data organisation in
spreadsheets. When asked to share to data, she shares the relevant
worksheet by email. She is constantly approached by researchers,
consultants, and public servants about sharing data on the amounts of
types of faecal sludge removed from sanitation systems. While she is
willing to share information, she is frustrated by and tired of follow
up questions and the number of requests. She wants to learn how to give
people access to her data at a central location, so that everyone can
access the data from there. She is building a house for her family of
five with the revenues of her business. She juggling many
responsibilities and does not have any time to participate in formal
training.

**Yua** is a Japanese PhD student in Computer Science at ETH Zurich. She
is an active contributor to open source software packages and has a
passiong for Open Science principles. She is proficient in half a dozen
programming languages and uses R and Python for Data Science tasks. She
has an R package for data visualisation on GitHub, which has received
more than 500 stars. Her best friend works in the WASH sector and she
has learned a fair bit about it. Her great experience and expertise in
data cleaning enable her to decode data structures with minimal
metadata. She wants use her technical skills to contribute to open
communities and use her experience to support others in becoming more
proficient in using computational tools. The openwashdata community
provides the ideal starting point for her to do that. She also hopes to
use the wealth of data that is opened by the community to advance her
Computer Science PhD research on barriers to computational
reproducibility. She is introverted and prefers to communicate with
people online.

**Mandla** is in his final year of a Master of Science in Urban Planning
at Makerere University in Kampala, Uganda. He is supporting Senior
Researchers at the university in data collection for WASH related
projects and is highly motivated to learn modern data science tools for
his data analysis tasks. He did well in his high school math classes,
and has watched some free online courses on using R for data analysis.
He is struggling with file management and has recently lost three
months’ worth of data, as his hard drive was corrupted. He knows that
there is a better way to analyse and manage data, but he hasn’t found
the right material and motivation that teaches him the tools that he
needs. He wants to participate in 12-week course that teaches him the
foundational knowledge and wants to apply the learned skills to support
the openwashdata community in their mission to publish open data. He
doesn’t have money to buy a laptop. He uses the infrastructure at the
university, but during the recent student strike at the university the
computer lab was damaged and is currently closed.

**Asim** has been working at a research institute in Aachen, Germany for
25 years. He holds a PhD and is a group leader with a focus on solid
waste management research. Throughout his career, he has supported more
than 100 students and research assistants in their early career research
stages. He has never written a line of code, but is highly proficient in
using MS Excel. He has a particular fear to share data with other
researchers or alongside journal publications, because he believes that
others could judge his practices or may even use his data to write their
own publications. He is very particular about workflows, file and data
management. During the offboarding process of each employee, he has
ensured that generated research data stored on a long-term archive
server, following his guidelines for directory structure and
documentation. He wants to share this data with the openwashcommunity
under the condition that he and every researcher that was involved in
creating the data gets appropriate credit for their work. He has three
more years until retirement is reluctant to learn any new tools and
feels very uncomfortable with anything outside his normal working
environment. He needs someone to show him step by step how to share he
research data with the community.

# Work Packages and milestones

The following Table 2 shows a basic gantt chart against the four work
packages, including program activities and community engagement of the
four defined learner personas. Column “Lead” abbreviations: MB =
Dr. Matthias Bannert. LS = Lars Schöbitz. SA = Scientific Assisstant.
The following Table 3 is a list of research questions associated with
each of the Work Packages and related activities in Table 2. Any
publications derived from this program will be published as open access
material, following ORD practices and Open Science standards for
computational reproducibility and sharing of data and code under FAIR
principles.

Table 2:
https://docs.google.com/spreadsheets/d/1T3NV75vVCeSRcN6FYghOrVFyWWi4WjQT5e4tqwp8jAQ/edit#gid=0

Table 3:
https://docs.google.com/spreadsheets/d/105ZJL6bE-T8-fdm08e9sytFL9Vcj05NBbKnBcC2qkYk/edit#gid=0

# Resources (including project costs)

# Bibliography

<div id="refs" class="references csl-bib-body">

<div id="ref-wilkinson2016fair" class="csl-entry">

<span class="csl-left-margin">1. </span><span
class="csl-right-inline">Wilkinson MD, Dumontier M, Aalbersberg IjJ,
Appleton G, Axton M, Baak A, Blomberg N, Boiten J-W, da Silva Santos LB,
Bourne PE, Bouwman J, Brookes AJ, Clark T, Crosas M, Dillo I, Dumon O,
Edmunds S, Evelo CT, Finkers R, Gonzalez-Beltran A, Gray AJG, Groth P,
Goble C, Grethe JS, Heringa J, ’t Hoen PAC, Hooft R, Kuhn T, Kok R, Kok
J, Lusher SJ, Martone ME, Mons A, Packer AL, Persson B, Rocca-Serra P,
Roos M, van Schaik R, Sansone S-A, Schultes E, Sengstag T, Slater T,
Strawn G, Swertz MA, Thompson M, van der Lei J, van Mulligen E, Velterop
J, Waagmeester A, Wittenburg P, Wolstencroft K, Zhao J, Mons B. [The
FAIR Guiding Principles for scientific data management and
stewardship](https://doi.org/10.1038/sdata.2016.18). Scientific Data.
2016 Mar;3(1):160018. </span>

</div>

<div id="ref-wpdx2022wpdx" class="csl-entry">

<span class="csl-left-margin">2. </span><span
class="csl-right-inline">WPdx. WPdx The Water Point Data Exchange is the
global platform for sharing water point data. 2022. </span>

</div>

<div id="ref-gather2020recommendations" class="csl-entry">

<span class="csl-left-margin">3. </span><span
class="csl-right-inline">Gather. Recommendations for the design of a
data standard for sanitation data. 2020. </span>

</div>

<div id="ref-2022development" class="csl-entry">

<span class="csl-left-margin">4. </span><span
class="csl-right-inline">Development Data Partnership - About.
https://datapartnership.org/about/; 2022. </span>

</div>

<div id="ref-mckiernan2016how" class="csl-entry">

<span class="csl-left-margin">5. </span><span
class="csl-right-inline">McKiernan EC, Bourne PE, Brown CT, Buck S,
Kenall A, Lin J, McDougall D, Nosek BA, Ram K, Soderberg CK, Spies JR,
Thaney K, Updegrove A, Woo KH, Yarkoni T. [How open science helps
researchers succeed](https://doi.org/10.7554/eLife.16800). Rodgers P,
editor. eLife. 2016 Jul;5:e16800. </span>

</div>

<div id="ref-gsma2021innovative" class="csl-entry">

<span class="csl-left-margin">6. </span><span
class="csl-right-inline">GSMA. Innovative Data for Urban Planning: The
Opportunities and Challenges of Public-Private Data Partnerships. Mobile
for Development. 2021. </span>

</div>

<div id="ref-schobitz2022research" class="csl-entry">

<span class="csl-left-margin">7. </span><span
class="csl-right-inline">Schöbitz L, Tilley E. Research Beyond the Lab
Open Science and Research Methods for a Global Engineer.
https://rbtl-fs22.github.io/website/; 2022. </span>

</div>

<div id="ref-schobitz2021data" class="csl-entry">

<span class="csl-left-margin">8. </span><span
class="csl-right-inline">Schöbitz L. Data Science for WASH workshop
hosted at the Colorado WASH Symposium 2021. 2021. </span>

</div>

<div id="ref-cetinkaya-rundel2018infrastructure" class="csl-entry">

<span class="csl-left-margin">9. </span><span
class="csl-right-inline">Çetinkaya-Rundel M, Rundel C. [Infrastructure
and Tools for Teaching Computing Throughout the Statistical
Curriculum](https://doi.org/10.1080/00031305.2017.1397549). The American
Statistician. 2018 Jan;72(1):58–65. </span>

</div>

<div id="ref-allaire2022quarto" class="csl-entry">

<span class="csl-left-margin">10. </span><span
class="csl-right-inline">Allaire JJ, Teague C, Scheidegger C, Xie Y,
Dervieux C. [Quarto](https://doi.org/10.5281/zenodo.5960048). 2022.
</span>

</div>

<div id="ref-brown2018ten" class="csl-entry">

<span class="csl-left-margin">11. </span><span
class="csl-right-inline">Brown NCC, Wilson G. [Ten quick tips for
teaching programming](https://doi.org/10.1371/journal.pcbi.1006023).
PLOS Computational Biology. 2018 Apr;14(4):e1006023. </span>

</div>

<div id="ref-nederbragt2020ten" class="csl-entry">

<span class="csl-left-margin">12. </span><span
class="csl-right-inline">Nederbragt A, Harris RM, Hill AP, Wilson G.
[Ten quick tips for teaching with participatory live
coding](https://doi.org/10.1371/journal.pcbi.1008090). PLOS
Computational Biology. 2020 Sep;16(9):e1008090. </span>

</div>

<div id="ref-azevedo2021culture" class="csl-entry">

<span class="csl-left-margin">13. </span><span
class="csl-right-inline">Azevedo F, Liu M, Pennington CR, Pownall M,
Evans TR, Parsons S, Elsherif M, Micheli L, Westwood S, FORRT. [Towards
a culture of open scholarship: The role of pedagogical
communities](https://doi.org/10.31222/osf.io/ek9m5). MetaArXiv; 2021.
</span>

</div>

<div id="ref-auer2021communityled" class="csl-entry">

<span class="csl-left-margin">14. </span><span
class="csl-right-inline">Auer S, Haeltermann NA, Weissberger TL, Erlich
JC, Susilaradeya D, Julkowska M, Gazda MA, Schwessinger B, Jadavji NM,
Reproducibility for Everyone Team. [A community-led initiative for
training in reproducible research](https://doi.org/10.7554/eLife.64719).
Pérez Valle H, Rodgers P, editors. eLife. 2021 Jun;10:e64719. </span>

</div>

<div id="ref-button2020grassroots" class="csl-entry">

<span class="csl-left-margin">15. </span><span
class="csl-right-inline">Button KS, Chambers CD, Lawrence N, Munafò MR.
[Grassroots Training for Reproducible Science: A Consortium-Based
Approach to the Empirical
Dissertation](https://doi.org/10.1177/1475725719857659). Psychology
Learning & Teaching. 2020 Mar;19(1):77–90. </span>

</div>

<div id="ref-kathawalla2020easing" class="csl-entry">

<span class="csl-left-margin">16. </span><span
class="csl-right-inline">Kathawalla U-K, Silverstein P, Syed M. [Easing
Into Open Science: A Guide for Graduate Students and Their
Advisors](https://doi.org/10.31234/osf.io/vzjdp). PsyArXiv; 2020.
</span>

</div>

<div id="ref-beckman2021implementing" class="csl-entry">

<span class="csl-left-margin">17. </span><span
class="csl-right-inline">Beckman MD, Çetinkaya-Rundel M, Horton NJ,
Rundel CW, Sullivan AJ, Tackett M. [Implementing Version Control With
Git and GitHub as a Learning Objective in Statistics and Data Science
Courses](https://doi.org/10.1080/10691898.2020.1848485). Journal of
Statistics and Data Science Education. 2021 Jan;29(sup1):S132–44.
</span>

</div>

<div id="ref-ostblom2021opinionated" class="csl-entry">

<span class="csl-left-margin">18. </span><span
class="csl-right-inline">Ostblom J, Timbers T. Opinionated practices for
teaching reproducibility: Motivation, guided instruction and practice.
2021 Sep; </span>

</div>

<div id="ref-tierney2020realistic" class="csl-entry">

<span class="csl-left-margin">19. </span><span
class="csl-right-inline">Tierney NJ, Ram K. A Realistic Guide to Making
Data Available Alongside Code to Improve Reproducibility.
arXiv:200211626 \[cs\] \[Internet\]. 2020 Feb; Available from:
<https://arxiv.org/abs/2002.11626></span>

</div>

<div id="ref-community2019turing" class="csl-entry">

<span class="csl-left-margin">20. </span><span
class="csl-right-inline">Community TTW, Arnold B, Bowler L, Gibson S,
Herterich P, Higman R, Krystalli A, Morley A, O’Reilly M, Whitaker K.
[The Turing Way: A Handbook for Reproducible Data
Science](https://doi.org/10.5281/zenodo.3233986). Zenodo; 2019. </span>

</div>

<div id="ref-broman2018data" class="csl-entry">

<span class="csl-left-margin">21. </span><span
class="csl-right-inline">Broman KW, Woo KH. [Data Organization in
Spreadsheets](https://doi.org/10.1080/00031305.2017.1375989). The
American Statistician. 2018 Jan;72(1):2–10. </span>

</div>

<div id="ref-ellis2018how" class="csl-entry">

<span class="csl-left-margin">22. </span><span
class="csl-right-inline">Ellis SE, Leek JT. [How to Share Data for
Collaboration](https://doi.org/10.1080/00031305.2017.1375987). The
American Statistician. 2018 Jan;72(1):53–7. </span>

</div>

<div id="ref-swissnationalsciencefoundationsnsfopen" class="csl-entry">

<span class="csl-left-margin">23. </span><span
class="csl-right-inline">(SNSF) SNSF. Open Research Data: Which data
repositories can be used? Swiss National Science Foundation (SNSF).
https://www.snf.ch/en/WtezJ6qxuTRnSYgF/topic/undefined/en/WtezJ6qxuTRnSYgF/topic/;
</span>

</div>

<div id="ref-marwick2018packaging" class="csl-entry">

<span class="csl-left-margin">24. </span><span
class="csl-right-inline">Marwick B, Boettiger C, Mullen L. [Packaging
Data Analytical Work Reproducibly Using R (and
Friends)](https://doi.org/10.1080/00031305.2017.1375986). The American
Statistician. 2018 Jan;72(1):80–8. </span>

</div>

<div id="ref-wilson2019teaching" class="csl-entry">

<span class="csl-left-margin">25. </span><span
class="csl-right-inline">Wilson G. Teaching Tech Together: How to Make
Lessons That Work and Build a Teaching Community Around Them. Chapman &
Hall/CRC Press; 2019. </span>

</div>

</div>
