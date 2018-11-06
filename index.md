---
layout: conf
color: "#00478E"
logo: NY Database Day 2018
---

New York Database Day is a workshop targeting the database researchers and research-oriented practitioners in the New York area. New York has an incredibly strong database presence, and it is prime time for folks to get together. The [Database Group at Columbia University](https://cudbg.github.io) will host the inaugural NYDBDay on November 10th at Columbia University. The purpose is for researchers in the area to learn about each others’ research, have discussions on important database directions, and look for ways to grow and foster the research+industrial community.

* Date: Saturday 11/10 9:45AM - 6PM
* Location: Columbia Computer Science Dept, Mudd 451, [500 W 120th St](https://goo.gl/maps/3j1L69NpGZS2)

<!-- As part of the agenda below, we have two blocks of times for presentations. Before lunch, academic researchers will share an overview of their research directions. After lunch, friends in industry will give 5-minute lightning talks about their work. We invite participants to submit short 1-2 paragraph abstracts for research talks, lightning talks, or posters.-->

<style>
.abstract {
  display: none;
}
h2 {
  text-align: center;
}
</style>

## Agenda

* **9:45-10:00**: Welcome and Intro
* **10:00-12:00**: [Short research talks](#research) (10m+5m Qs)
* **12:00-1:30**: Lunch
* **1:30-2:15** [Lightning talks](#industry) (10m+5m Qs)
* **2:15-3:45**: [Panel Discussion](#panel): Human-in-the-Loop Data Analysis
  * Moderator: Julia Stoyanovich
  * Panel: TBA
* **4:00-6:00**: Poster session, Snacks

<!--
  * Data Integration
  * Specialized systems designs for interfaces and applications
  * DB and society (human in the loop, crowdsourcing, ethics)
  * DB and ML (lifecycle upstream from ML ~ DB for ML, ML to help solve DB problems)
  * Suggestions?
-->


<a name="research"></a>
## Short Research Talks

Talks are 10 min + 5 minutes for questions.

[Wendy Hui Wang](https://www.cs.stevens.edu/~hwang4/) (SIT)
* Abstract: Crowdsourcing has raised several security concerns. One of the concerns is how to assign sensitive tasks in the crowdsourcing market, especially when there are colluding participants in crowdsourcing. In this presentation, I will talk about our work on sensitive task assignments in crowdsourcing markets with colluding workers. 

[Amélie Marian](https://www.cs.rutgers.edu/~amelie/) (Rutgers)
* Abstract: Digital traces of our lives are now constantly produced by various connected devices, internet services and interactions. These “personal digital traces” are different from traditional personal  files; they are typically (but not always) smaller, heterogeneous, and accessible through a wide variety of portals and interfaces or directly stored on our devices.  Users have very few tools to organize, understand, and search the digital traces they produce. The DigitalSelf project at Rutgers University proposes models and techniques to integrate, aggregate, organize, and search personal information within a collection of a user’s personal digital traces. First, I will present our current work --based on an intuitive data model which classifies personal digital traces along the basic six dimensions: what, when, where, who, why, and how-- on searching personal data using dynamic frequency- and learning-based ranking functions. Then, I will discuss how we integrate and connect traces through the use of episodic scripts to create personal narratives. Finally, I will discuss possible extensions of this work in various real-world applications such as senior care, or privacy-preserving personalization.  

[Senjuti Basu Roy](http://cs.njit.edu/people/senjuti-basu-roy) (NJIT)
* Abstract: In this talk, we will present an overview of the research projects undergoing at the Big Data Analytics Lab (BDaL), at the New Jersey Institute of Technology. Broadly speaking,  at BDaL, we focus on an alternative computational paradigm that involves ""humans-in-the-loop"" for large scale analytics problems . These problems arise at different stages in a traditional data science pipeline (e.g., data cleaning, query answering, ad-hoc data exploration, or predictive modeling), as well as from emerging applications. We study optimization opportunities that come across because of this unique man-machine collaboration, and address data management and computational challenges to enable large scale analytics with humans-in-the-loop. These research projects are funded by National Science Foundation, Office of Naval Research, National Institute of Health, and Microsoft Research.  The talk will have two parts - in the first part, we will describe how we can substitute expensive domain expertise without compromising much on the quality or latency by  leveraging multiple human workers (such as students, amateur scientists, or even lay crowdsourced workers) in problems that arise in a traditional data science pipeline. We will highlight our solutions to address computational challenges and optimization opportunities. In the second part of the talk - we will describe  problems that come from emerging applications to enable collaboration among a group of individuals and machine algorithm. We will present an overview of our proposed approach and conclude by outlining some research challenges."

[Dennis Shasha](https://cs.nyu.edu/shasha/) (NYU)
* Abstract: My research group does work in verified concurrent algorithms for data structure, a meta-algorithm for machine learning that allows the refusal of a predication in order to guarantee a correctness rate, energy-efficient blockchains, and a few other topics. My talk will give an overview of the research areas and focus on the energy-efficient blockchain design under fail-stop and traitorous failures.

[Julia Stoyanovich](https://engineering.nyu.edu/faculty/julia-stoyanovich) (NYU)
* Title: Algorithms and Systems for Responsible Data Science 
* Abstract:  In this talk I will give my perspective on data science, a field that employs elegant algorithmic insights and generalizable systems advances to meet important societal challenges.  I will give this perspective through the lens of the ongoing projects in my research group.  These include the Portal project -- a formal framework for analysis of evolving graphs, instantiated in an open-source system based on Apache Spark, and DB4Pref -- algorithms and systems for analysis of preferences and votes that branches into computational social choice.  The main focus of my talk will be on the Data, Responsibly project that frames managing data in accordance with ethical and moral norms, and legal and policy considerations, as a core system requirement. I will highlight some of our recent algorithmic advances, and will discuss the over-all framework in which responsibility properties are managed and enforced through all stages of the data lifecycle.

[Torsten Suel](http://engineering.nyu.edu/~suel/) (NYU)
* Abstract: My research group focuses on web search engines, and in particular on efficiency issues and on search engine architecture. Current interests include basic indexing and query processing techniques, efficiency in cascading search architectures used to implement complex ranking functions, and load balancing and query routing in distributed (sharded) search architectures. In this talk,  I will give a brief overview of current research directions in my group.

[Kenneth Ross](https://www.cs.columbia.edu/~kar/) (Columbia)
* Abstract: Specialized hardware offers the potential for higher performance with a lower power and transistor budget than general purpose hardware. For common workloads such as data analytics, it may pay to invest in a Database Processing Unit (DPU) analogous to a GPU for graphics workloads. In this talk, I will present the Q100 architecture, designed to support SQL query processing. I will outline the Q100 design and evaluation, including the selection of individual tiles to perform component operations such as sorting, joins, and aggregations. The internal network connecting the components can be specialized to favor common data paths for better area and/or performance.

[Eugene Wu](http://www.eugenewu.net) (Columbia)
* Abstract: I will give a biased view on the future of interacting with data and the related infrastructure, algorithmic, and design questions involved.


<a name="industry"></a>
## Industry Lightning Talks 

Talks are 10 min + 5 minutes for questions.


[Evan Jones](https://www.evanjones.ca/) (BlueCore) 
* Data at Bluecore
* A walk through of what Bluecore is and what data products we use. I'll briefly talk about our data problems we have run into, which mostly relate to "manageability" and connecting data between different systems.

[Adam Marcus](http://www.marcua.net) (B12)
* Abstract TBA

[Dmitri V. Kalashnikov](https://www.ics.uci.edu/~dvk/)  (ATT Labs)
* Many corporations often have a large corpus of databases created for different purposes. A data analyst, given a task at hand, needs to find the right dataset(s) from this corpus to use for her task. This often turns into a challenging exercise due to several reasons. One such reason is that technical metadata, such as table and column names, are often abbreviated, e.g. “cust_acct” instead of “customer_account” for a column name. At the same time, column “cust_acct” might not have any business metadata, i.e., human-generated column descriptions, associated with it. Hence, the analyst searching for “customer_account” might not find “cust_acct” column due to the keyword mismatch. 
* In our Automated Keyword Generation (AKG) project at AT&T we have developed a machine learning approach that learns “tag expansions” from a small corpus of business metadata. The approach is based on supervised learning from noisy data, as column descriptions can have a tangible amount of noise. When a tag has multiple meanings, the approach is able to leverage context to better choose the most likely meaning. The approach has been deployed at AT&T as part of a larger system that allows the user to navigate and search the metadata for a very large corpus of databases.



<a name="panel"></a>
## Panel Discussion

TBA


# Additional Information

### Important Dates

* Registration and Submission deadline: 10/30/2018
* Submission Notifications: 11/3/2018
* Workshop: 11/10/2018

### Submission and registration

Please register so we can order an appropriate amount of food.  Optionally submit talk and poster abstracts.

{:.link}
[Submit and Register](https://goo.gl/forms/DQcfAMCzqg6hmaVJ3)


### Organizers

* [Eugene Wu](http://www.eugenewu.net) (Columbia)
* [Julia Stoyanovich](https://engineering.nyu.edu/faculty/julia-stoyanovich) (NYU)
* [Divesh Srivastava](https://divesh.net/) (AT&T)
