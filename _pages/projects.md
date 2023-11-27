---
title: "Projects"
permalink: /projects/
author_profile: true
---
<link href="https://fonts.googleapis.com/css?family=Comfortaa:300,400,700|Righteous" rel="stylesheet">

###  <i class="fa fa-pencil-square-o" aria-hidden="true"></i> Live Programming for Formal Methods
Current model development environments are rather “bare bones”, providing no guidance or feedback other than the output itself, and limiting the revision process to the age-old “edit and check”. We are exploring how to combine live programming innovations with the strengths inherent to modeling languages to provide a range of contextualized feedback during the development of software models. For instance, code completion is a common modern IDE feature that does not currently exist for modeling languages. We are exploring how to provide relevant and meaningful formula completion suggestions as the user types their model.

###  <i class="fa fa-fw fa-clipboard-check" aria-hidden="true"></i> Explainable AI
Machine learning is a popular, growing field. However, machine learning systems are very different in nature to our previous definitions of software programs. As we start to integrate machine learning systems into our daily lives, there is a pressing need to make sure these systems are correct, but the decisions of machine learning systems are often black-box. Thus, we need methods to build end user *trust* in their output. In collaboration with [Dr. Jacbor Luber](https://luberlab.org/), we are exploring methods to annotate the output of medical-based machine learning systems in such a way that a doctor can trust the output enough to deploy the system in practice.

###  <i class="fa fa-fw fa-bug" aria-hidden="true"></i> Testing and Synthesis of Formal Methods
Modeling languages can greatly increase the reliability of software systems. Unfortunately, modeling languages are hard to develop in, which brings us to a double edge sword: the software model needs to be correct in order to actually verify the software system. We investigate techniques to both test software models (in all their declarative execution weirdness) and even synthesize key portions of the model for the user.

## <i class="fa fa-fw fa-code" aria-hidden="true"></i> Testing tools for Alloy
* **[Alloy Analyzer Plus IDE:](https://alloyanalyzerplus.github.io/)** A testing-oriented IDE for Alloy that includes test coverage, mutation testing, fault localization and automated repair.
* **[Crucible:](https://github.com/Crucible-Alloy/Crucible)** Tool to graphically create AUnit test cases.
* **[MuAlloy:](https://github.com/MuAlloyT/mualloy_temporal)** Mutation testing tool for Alloy (updated to support linear temporal logic).
* **[AlloyFL:](https://AlloyFL.github.io)** Alloy Analyzer extension that provides automated fault localization of Alloy models.

## <i class="fa fa-fw fa-code" aria-hidden="true"></i> Synthesis tools for Alloy
* **[ARepair:](https://github.com/kaiyuanw/ARepair)** Tool for automated repair of Alloy models. The tool firsts performs fault localization to narrow in on the buggy portion of the model, then uses synthesis techniques to fix the model.
* **[ASketch:](https://github.com/kaiyuanw/ASketch)** Tool to synthesize parts of an Alloy model using sketching.

## <i class="fa fa-fw fa-code" aria-hidden="true"></i> Testing Tools for Prolog
* **[ProFl:](https://github.com/geoorge1d127/ProFl)** Tool for automated fault localization of Prolog models.

###  <i class="fa fa-fw fa-sitemap" aria-hidden="true"></i> Model-Based Testing of Systems 
Formally verifying a system is the first step in ensuring system reliability. However, a crucial next step is ensuing the corresponding implementation is a faithful reproduction of the formal model. An important challenge is to link highly assured formal methods of systems to the actual implementations of those systems. We explore avenues for creating valuable output from software models, which can facilitate testing of the implementation.
 
## <i class="fa fa-fw fa-code" aria-hidden="true"></i> Scenario Enumeration Tools for Alloy:
* **[Abstract Instances:](https://github.com/jringert/alloy-absinst)** An interactive enumerator tool for Alloy that allows users to view what portions of the instance are necessary to allow subsets of formulas to be true.
* **[HawkEye:](https://github.com/alloy-hawkeye/Hawkeye)** An interactive enumerator tool for Alloy that allows users to control how the next scenario enumated by Alloy differs from the current one.
* **[Seabs:](https://github.com/Allisonius/Seabs)** Tool to allow the user to guide solution enumeration for an Alloy model using abstract functions.



 

