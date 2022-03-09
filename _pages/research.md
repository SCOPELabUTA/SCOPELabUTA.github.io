---
title: "Research"
permalink: /research/
author_profile: true
---

<h4>"The world always seems brighter when you've just made something that wasn't there before."</h4>
 
 *~Neil Gaiman*

I am the advisor for SCOPE Lab where we work on techniques for **S**howing **C**orrectness **O**f (all) **P**rogram **E**xecutions. 


### <i class="fa fa-fw fa-code-branch" aria-hidden="true"></i> Tools

I am interested in applied research, and the efforts to transition research ideas into real tools to be used by the software development community.
  * **[HawkEye:](https://github.com/alloy-hawkeye/Hawkeye)** An interactive enumerator tool for Alloy that allows users to control how the next scenario enumated by Alloy differs from the current one.
  * **[Seabs:](https://github.com/Allisonius/Seabs)** Tool to allow the user to guide solution enumeration for an Alloy model using abstract functions.
  * **[AUnit Analyzer:](https://sites.google.com/view/aunitanalyzer)** Extension to the Alloy Analyzer that provides support for AUnit (test creation, test execution, coverage).
  * **[MuAlloy:](https://github.com/kaiyuanw/MuAlloy)** Mutation testing tool for Alloy 
  * **[AlloyFL:](https://AlloyFL.github.io)** Tool for automated fault localization of Alloy models.
  * **[ARepair:](https://github.com/kaiyuanw/ARepair)** Tool for automated repair of Alloy models. The tool firsts performs fault localization to narrow in on the buggy portion of the model, then uses synthesis techniques to fix the model.
  * **[ASketch:](https://github.com/kaiyuanw/ASketch)** Tool to synthesize parts of an Alloy model using sketching.
  * **[ProFl:](https://github.com/geoorge1d127/ProFl)** Tool for automated fault localization of Prolog models.


  
### <i class="fa fa-fw fa-cogs" aria-hidden="true"></i> Research Projects

## <i class="fa fa-fw fa-book-reader" aria-hidden="true"></i> Formal Methods Education
Software models can help improve software reliability. Yet, many developers do not use software models. Why? Often, people have the perception that software modeling is too difficult, time consuming and not practical for real world systems. My research looks to break this perception by developing novel techniques and tools to streamline formal methods education for both writing specifications and analyzing specifications. 

## <i class="fa fa-fw fa-robot" aria-hidden="true"></i> Model-Based Testing of Autonomous Systems 
Formally verifying a system is the first step in ensuring system reliability. However, a crucial next step is ensuing the corresponding implementation is a faithful reproduction of the formal model. I am working with an interdisciplinary team to develop methods to link highly assured formal methods of autonomous systems to the actual implementations of those systems. Due to the many collaborators on this project, we will be able to develop these practices over operational autonomous systems in the Department of Defense.

## <i class="fa fa-fw fa-car-side" aria-hidden="true"></i> Autonomous Vehicle Verification 
Autonomous vehicles are a future technology that many expect to come to fruition. The software systems associated with autonomous vehicles will inherently be safety critical and we will need rigorous techniques to ensure these system never fail. Our work focuses on approaches leveraging formal methods to develop novel techniques to verify the design, subsystem interactions, and the underlying machine learning subsystem.

<center><img src="../images/auto2.png" alt="SAE-GM Autodrive Challenge"> &nbsp;&nbsp;&nbsp;<img src="../images/auto3.png" alt="SAE-GM Autodrive Challenge"></center>

## <i class="fa fa-fw fa-bug" aria-hidden="true"></i> Verification and Synthesis of Formal Methods
AUnit introduces the first testing infrastructure for Alloy, namely: test case, test execution and coverage. With this infrastructure in place, we can now explore how to bring well-established imperative v&v techniques (automated test generation, fault localization, mutation testing, regression testing, etc) into the Alloy language. Additionally, AUnit enables automated repair and synthesis techniques for Alloy. These frameworks ease the burden of developing Alloy models, which is a non-trivial task. Based on the success of AUnit, we plan to explore verification and synthesis techniques for a broader range of formal modeling languages. 
