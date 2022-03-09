---
title: "Projects"
permalink: /projects/
author_profile: true
---
<link href="https://fonts.googleapis.com/css?family=Comfortaa:300,400,700|Righteous" rel="stylesheet">

### <i class="fa fa-fw fa-cogs" aria-hidden="true"></i> Research Projects

## <i class="fa fa-fw fa-bug" aria-hidden="true"></i> Verification and Synthesis of Formal Methods
AUnit introduces the first testing infrastructure for Alloy, namely: test case, test execution and coverage. With this infrastructure in place, we can now explore how to bring well-established imperative v&v techniques (automated test generation, fault localization, mutation testing, regression testing, etc) into the Alloy language. Additionally, AUnit enables automated repair and synthesis techniques for Alloy. These frameworks ease the burden of developing Alloy models, which is a non-trivial task. Based on the success of AUnit, we plan to explore verification and synthesis techniques for a broader range of formal modeling languages. 

## <i class="fa fa-fw fa-book-reader" aria-hidden="true"></i> Testing and Verification Machine Learning Systems
Machine learning is a popular, growing field. However, machine learning systems are very different in nature to our previous definitions of software programs. As we start to integrate machine learning systems into our daily lives, there is a pressing need to make sure these systems are correct. We need to know that these black-box decisions coming out of the machine learning system can be trusted. We are exploring avenues to improve and define "testing" and verification for these systems.

## <i class="fa fa-fw fa-robot" aria-hidden="true"></i> Model-Based Testing of Autonomous Systems 
Formally verifying a system is the first step in ensuring system reliability. However, a crucial next step is ensuing the corresponding implementation is a faithful reproduction of the formal model. I am working with an interdisciplinary team to develop methods to link highly assured formal methods of autonomous systems to the actual implementations of those systems. Due to the many collaborators on this project, we will be able to develop these practices over operational autonomous systems in the Department of Defense.

## <i class="fa fa-fw fa-car-side" aria-hidden="true"></i> Autonomous Vehicle Verification 
Autonomous vehicles are a future technology that many expect to come to fruition. The software systems associated with autonomous vehicles will inherently be safety critical and we will need rigorous techniques to ensure these system never fail. Our work focuses on approaches leveraging formal methods to develop novel techniques to verify the design, subsystem interactions, and the underlying machine learning subsystem.

<center><img src="../images/auto2.png" alt="SAE-GM Autodrive Challenge"> &nbsp;&nbsp;&nbsp;<img src="../images/auto3.png" alt="SAE-GM Autodrive Challenge"></center>

### <i class="fa fa-fw fa-code-branch" aria-hidden="true"></i> Tools

An important component of research is ensuring that the research efforts can be utilized by others. Ultimately, we want to  transition research ideas into tools that are used by the software development community.
  * Scenario Enumeration Tools for Alloy:
     * **[HawkEye:](https://github.com/alloy-hawkeye/Hawkeye)** An interactive enumerator tool for Alloy that allows users to control how the next scenario enumated by Alloy differs from the current one.
     * **[Seabs:](https://github.com/Allisonius/Seabs)** Tool to allow the user to guide solution enumeration for an Alloy model using abstract functions.
  * Testing tools for Alloy
    * **[AUnit Analyzer:](https://sites.google.com/view/aunitanalyzer)** Extension to the Alloy Analyzer that provides support for AUnit (test creation, test execution, coverage).
    * **[MuAlloy:](https://github.com/kaiyuanw/MuAlloy)** Mutation testing tool for Alloy 
    * **[AlloyFL:](https://AlloyFL.github.io)** Tool for automated fault localization of Alloy models.
  * Synthesis tools for Alloy
    * **[ARepair:](https://github.com/kaiyuanw/ARepair)** Tool for automated repair of Alloy models. The tool firsts performs fault localization to narrow in on the buggy portion of the model, then uses synthesis techniques to fix the model.
    * **[ASketch:](https://github.com/kaiyuanw/ASketch)** Tool to synthesize parts of an Alloy model using sketching.
  * Testing Tools for Prolog
    * **[ProFl:](https://github.com/geoorge1d127/ProFl)** Tool for automated fault localization of Prolog models.
