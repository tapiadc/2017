## Welcome to the Tapia 2017 Doctoral Consortium Website

The Doctoral Consortium is a one-day workshop that provides an opportunity for doctoral students to discuss and explore their research interests with a panel of established researchers in computing.

Doctoral students must have submitted an application during the Tapia 2017 Call for Participation to be selected for the Doctoral Consortium.

The Tapia 2017 doctoral consortium is Chair by [Dr. Aubrey Rembert](http://tapiaconference.org/about/committees/aubrey-rembert) and [Dr. Christan Grant](http://tapiaconference.org/about/committees/christan-grant).


#### Location
Saturday, September 23, 2017 — 8:00AM - 3:00PM <br/>
[Hyatt Regency Atlanta](http://tapiaconference.org/venue/) <br/>
Room: Cortland <br/>


### Schedule:

---

#### This will change slightly

**Breakfast**: 8:00am - 8:45am  <br/>
<br/>
Opening/Intro: 8:45am - 9:00am <br/>
Session 1: 9:00am - 10:30am ([Presentation 1](#shubbhi-taneja), [Presentation 2](#imani-palmer))<br/>
**Coffee break** <br/>
Session 2: 11:00am - 12:30am ([Presentation 3](#shadi-noghabi), [Presentation 4](#vijay-rajanna))<br/>
<br/>
**Lunch break**: 12:30pm - 1:00pm <br/>
<br/>
Session 3: 1:00pm - 2:30pm ([Presentation 5](#martha-o-perez-arriaga), [Presentation 6](#hoda-aghaei-khouzani))<br/>
**Coffee break** <br/>
Session 4:  2:45pm - 4:45pm ([Presentation 7](#samuel-gutiérrez), [Presentation 8](#shreyasee-mukherjee), [Presentation 9](#sultanah-alshammari))<br/>
Closing: 4:45pm - 5:00pm <br/>
<br/>
**Dinner**: 5pm
<br/>

---


### For Presenters

- The room will not have a lab. If possible, please be prepared to use your own laptop to present.
- Each presenter will give a 30 minute presentation with about 15 minutes for questions.
- Please send a **1-slide/1-minute self-introduction slide** to the Doctoral Consortium co-chair cgrant@ou.edu before **September, 23 Friday midnight US eastern time**. Please follow the [slide template](https://sites.google.com/site/tapia15dc/tapia-dc-slide-example-taoxie.pptx) to prepare your slide. This slide will be presented by you during the opening of the Doctoral Consortium to allow other consortium attendees to know more about you before the networking throughout the consortium.
- Please refer to [this blog post](http://programanalysis.blogspot.com/2012/10/splash-2012-doctoral-symposium.html) when preparing your 30-minute presentation at the Doctoral Consortium (advice information on [Tao Xie's advice portal](http://web.engr.illinois.edu/~taoxie/advice/) can be also useful).


### Presenters

| Names | Affiliation | Title |
| ------------ |------------------ | --------------------------------------- |
| Shubbhi Taneja | Auburn University | [Thermal-aware High Performance Clusters](#shubbhi-taneja) |
| Vijay Rajanna | Texas A&M University | [A Gaze-Assisted Multimodal Approach to Rich and Accessible Human-Computer Interaction](#vijay-rajanna) |
| Imani Palmer | University of Illinois at Urbana-Champaign | [Improving the Efficacy of Digital Forensics](#imani-palmer) |
| Shadi Noghabi | University of Illinois at Urbana-Champaign | [Building a Scalable Distributed Online Media Processing Environment](#shadi-noghabi) |
| Martha O. Perez-Arriaga | University of New Mexico | [Automated Generation of Semantic Data Models from Scientific Publications](#martha-o-perez-arriaga) |
| Hoda Aghaei Khouzani | University of Delaware | [Runtime Solutions to Apply Non-volatile Memories in Future Computer Systems](#hoda-aghaei-khouzani) |
| ~Ifeoma Adaji~ | ~University of Saskatchewan~ | ~[Improving E-commerce Shoppers’ Experience using Personalization & Persuasive Technology](#ifeoma-adaji)~ |
| Samuel Gutiérrez | University of New Mexico | [Dynamically Accommodating Thread-Level Heterogeneity in Coupled Parallel Applications](#samuel-gutiérrez) |
| Sultanah Alshammari | University of North Texas | [Computational Framework to Assess the Risk of Global Epidemics at Mass Gatherings](#sultanah-alshammari) |
| Shreyasee Mukherjee | WINLAB, Rutgers University | [Towards Pervasive Heterogeneous Wireless Access at the Edge](#shreyasee-mukherjee) |


#### Shubbhi Taneja 
We have developed a thermal-aware job scheduling strategy called tDispatch tailored for MapReduce applications running on Hadoop clusters. The scheduling idea of tDispatch is motivated by a profiling study of CPU-intensive and I/O-intensive jobs from the perspective of thermal efficiency. More specifically, we investigate the thermal behaviors of these two types of jobs running on a Hadoop cluster by stress testing data nodes through extensive experiments. We show that CPU-intensive and I/O-intensive jobs exhibit various thermal and performance impacts on multicore processors and hard drives of Hadoop clusters. After we quantify the thermal behaviors of Hadoop jobs on the master and data nodes of a cluster, we propose our scheduler to alternatively dispatch CPU-intensive and I/O-intensive jobs. We apply our strategy to several MapReduce applications with different resource consumption profiles. Our experimental results show that tDispatch is conducive of creating opportunities to cool down multicore processors and disks in Hadoop clusters deployed in modern data centers. Currently, we are extending these experiments on a Spark cluster installed in a HPC room. For the ongoing experiments, along with the temperatures, we are also considering parameters like energy consumption of the worker nodes, height of the nodes in the rack, thermal patterns in HPC room and the number of nodes. For the same purpose, we are using a big data benchmark suite called HiBench. We will be developing thermal models based on the utilization patterns of these nodes. Our findings can be applied in other thermal-efficient job schedulers that are aware of thermal behaviors of CPU-intensive and I/O-intensive applications submitted to Hadoop and Spark clusters

#### Vijay Rajanna
Recent advancements in eye tracking technology is driving the adoption of gaze-assisted interaction as a rich and accessible human-computer interaction paradigm. Gaze-assisted interaction serves as a contextual, non-invasive, and explicit control method for users without disabilities; for users with motor or speech impairments, text entry by gaze serves as the primary means of communication. Despite significant advantages, gaze-assisted interaction is still not widely accepted because of its inherent limitations: 1) Midas touch, 2) low accuracy for mouse-like interactions, 3) need for repeated calibration, 4) visual fatigue with prolonged usage, 5) lower gaze typing speed, and so on.1~

This dissertation research proposes a gaze-assisted, multimodal, interaction paradigm, and related frameworks and their applications that effectively enable gaze-assisted interactions, while addressing many of the current limitations. In this regard, we present four systems that leverage gaze-assisted interaction: 1) a gaze- and foot-operated system for precise point-and-click interactions, 2) a dwell-free, foot-operated gaze typing system. 3) a gaze gesture-based authentication system, and 4) a gaze gesture-based interaction toolkit. In addition, we also present the goals to be achieved, technical approach, and overall contributions of this dissertation research.

#### Imani Palmer
The digital forensics investigative process involves the collection, preservation, and analysis of electronic data. The analysis of evidence is largely reliant on the knowledge of each examiner and their specific examination process. This data is key to ascertaining a likelihood of an occurrence of events. The assigning of this likelihood requires a reasoning about digital evidence. The digital forensic investigative process is in need of a more reliable method to produce calculated conclusions from digital evidence. This paper aims to further aid examiners on interpreting complex, low-level data with reliable scientific methods in order to abstract human behaviors.

#### Shadi Noghabi
Media has become dominant in all aspects of human lives, from critical applications such as medical, military, and security (e.g. surveillance cameras) to entertainment applications such as social media and media sharing websites. Billions of massive media objects (e.g., videos, photos, documents, etc.) are generated every second with high diversity among them (in terms of sizes and formats). These objects have to be stored and retrieved reliably, with low latency and in a scalable while efficient fashion. Additionally, various types of processing are done on media objects, from simple compressions and format conversion, to more complex machine learning algorithms detecting certain patterns and objects.

Existing large-scale storage and processing systems face several challenges when handling media objects. My research focuses on building an unified storage and processing environment tailored specifically for media objects, while maintaining high efficiency and scalability. I have built a scalable, load-balanced, efficient storage system optimized for media objects based on their unique access patterns. Currently, I am working on developing an efficient media processing system and integrating these two systems into one framework.


#### Martha O. Perez-Arriaga
The traditional problems to analyze information in digital publications scale with the ever-increasing volume of data. Other challenges on analyzing publications include the lack of standards in some areas, different formats and standards, different types of data, and diverse areas of knowledge. These challenges hinder detecting, understanding, sharing and querying information promptly.

We propose an investigation to use publications’ text and tables embedded in publications to build semantically enriched data models. These models allow integration, sharing, management, and querying information from publications.

Our work develops automated methods for information extraction, semantic analytics, information modeling, and information retrieval. It enables users to 1) detect, extract and organize information from tables within digital publications, 2) interpret and enrich tables with semantic relationships using text, vocabularies and ontologies, 3) characterize semantic data models in a machine readable format, and 5) use semantic data models to facilitate retrieval, integration, management, sharing and interoperability in publications.

#### Hoda Aghaei Khouzani
Main memory has been the performance and energy bottleneck of almost all computer systems. For dozens of years, the continuous advances of system design, applications, and technology makes the role of main memory more critical. Moreover, DRAM as the mainstream main memory technology is experiencing many technology scaling challenges that make its capacity, energy-efficiency, and reliability questionable. Fortunately, with the emergence of new memory technologies, a new path to address the limitations of DRAM has appeared. These technologies are non-volatile and have the advantage of higher scalability beyond DRAM with near zero static power consumption. In my PhD thesis, the applicability of two of these technologies, namely Phase Change Memory (PCM) and Domain Wall Memory (DWM) as a replacement for DRAM is explored. Alongside their benefits, PCM suffers from limited write endurance, long write latency, and high write energy, while the main challenge to employ DWM is due to its sequential access structure which requires shift operations to align the data of interest to the access port. Three different solutions are proposed to either hide these shortcomings or use them with respect to the system’s advantage. Specifically, for PCM-based main memory, first a wear-resistant page allocation algorithm is designed by leveraging the existing segment information in OS, so as to prolong PCM lifetime to the maximum extend with almost no extra overhead. Then to hide the write performance and energy limitations of PCM, a hybrid DRAM-PCM main memory is applied, and a conflict miss aware page allocation algorithm is proposed to further improve it. At last, the latency of page table accesses in a DWM-based main memory is reduced using a pre-shift scheme which, based on the state of each entry in page table, pre-aligns the access port to hide read and write latency.

#### Ifeoma Adaji
Simply selling products online can no longer guarantee profits for e-businesses especially for new comers to the e-commerce industry as the competition among companies is more intense. In order to keep existing customers and make new ones, e-businesses have to provide products and services that feel personal to their clients. This can be done with the use of personalization and persuasive strategies.

This research proposes a framework for improving e-commerce shopper’s experience that combines shopper type and personality type of customers to create an online persona for the client. Using the persuasive principles of the Persuasive Systems Design (PSD) framework, the consumer’s persona will then be matched to persuasive strategies that will likely lead to behavior change. The contributions of this research are novel and relevant because they will introduce an innovative approach to improve shoppers’ experience in e-commerce that is personalized and persuasive in nature. When implemented, my proposed solution will lead to an improved user experience in e-commerce platforms, especially new entrants to the market.

#### Samuel Gutiérrez
Hybrid parallel program models that combine message passing and multithreading (MP+MT) are becoming more popular, extending the basic message passing (MP) model that uses single-threaded processes for both inter- and intra-node parallelism. A consequence is that coupled parallel applications increasingly comprise MP libraries together with MP+MT libraries with differing preferred degrees of threading, resulting in thread-level heterogeneity. Retroactively matching threading levels between independently developed and maintained libraries is difficult; the challenge is exacerbated because contemporary parallel job launchers provide only static resource binding policies over entire application executions. A standard approach for accommodating thread-level heterogeneity is to under-subscribe compute resources such that the library with the highest degree of threading per process has one processing element per thread. This results in libraries with fewer threads per process utilizing only a fraction of the available compute resources.

In this work we study and evaluate novel approaches for accommodating thread-level heterogeneity in phased MPI+X applications comprising single- and multi-threaded libraries. Our current approach enables full utilization of all available compute resources throughout an application’s execution by providing programmable facilities to dynamically reconfigure runtime environments for compute phases with differing threading factors and memory affinities. We show that our approach can improve overall application performance substantially in real-world production codes.


#### Sultanah Alshammari
Due to the unique nature of the global mass gatherings and the public health hazards they pose, comprehensive studies of disease spread during these events are needed. The massive influx of spectators from different regions presents serious health threats and challenges for hosting countries and the countries where participants originate. The travel patterns at the end of global events could cause a rapid spread of infectious diseases affecting a large number of people within a short period of time. Mathematical and computational models provide valuable tools that help public health authorities to estimate, study, and control disease outbreaks at challenges settings such as mass gatherings. In this study, we present a computational framework to model disease spread at the annual global event of the Hajj (Muslim pilgrimage to Makkah, Saudi Arabia), where over two million pilgrims gathered from over 189 countries. We used the travel and demographic data of five Hajj seasons (2010-2014), and spatial data of the holy sites where the rituals are performed. We simulate the interactions of pilgrims using an agent-based model where each agent represents a pilgrim and maintains related demographic attributes and health information. The proposed model includes several simulations of the stages of Hajj with hourly or daily time steps. At each stage, the agent-based model of pilgrims is integrated to simulate their interactions within space and time frames of that stage.


#### Shreyasee Mukherjee
With over 6 billion cellular mobile devices in use today, the Inter- net is fast approaching an inflection point where the number of mobile devices far exceeds the number of fixed hosts and servers. Wireless access is not only limited to cellular or Wi-Fi connectivity through hand-held smart devices, but also includes a variety of wire- less sensors, Internet-of-Things (IoT), and smart-vehicle to vehicle (V2V) communication. Such ubiquitous wireless access scenarios pose architectural challenges to the existing TCP/IP based Internet framework, which has not undergone any major change since its inception. This work aims to support flexible wireless access to mobile devices in the future Internet, based on the MobilityFirst future Internet architecture, now under development. Mobility- First provides a clean-slate solution to emerging wireless access characteristics such as temporary disconnections, varying link qual- ity, mutlihoming and multicasting and provides a unified network framework that supports a wide range of mobile access scenarios. In our research, we focus on building key MobilityFirst protocol components such as routing support both intra and inter-domain for multihoming, efficient multicasting as well as low overhead and low latency protocols for smart resource-limited devices such as IoTs. These protocol designs are then evaluated for representative wireless/mobile use cases.



