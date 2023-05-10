---
title: 2023 GHC Contributors' Workshop
published: 2023-03-01
daterange: June 7-9, 2023
status: active
location: Rapperswil, Switzerland
summary: A hands-on introduction to working on GHC, colocated with Zurihac 2023
---


We are excited to announce the **2023 GHC Contributors' Workshop, June 7-9 2023**, organized by the GHC developers, the Haskell Foundation, and the OST Eastern Switzerland University of Applied Sciences! This is a workshop for those who want to get started working on GHC, those who want to understand GHC's internals to better diagnose issues with their own code, and those who want to transfer lessons learned in GHC to other compilers. The primary aim of the workshop is to broaden the base of contributors to GHC.

In this three-day event, held on the lakeside campus of OST in lovely Rapperswil, Switzerland, you can learn what you need to know in order to get started working on GHC, right from the core team itself. Because the workshop is immediately prior to [Zurihac 2023](https://zfoh.ch/zurihac2023/), there will be time to work on your project and ask questions.

## The Workshop

At this workshop, you can learn the ins and outs of working on GHC, including practical techniques for minimizing rebuilds and diagnosing compiler bugs. The fundamental concepts and idioms of key compiler subsystems will be presented, along with tips and tricks for understanding how they are working in a running compiler. This is a practical workshop: any theory presented will be in service of building things, and we expect that you will arrive with a checkout and build of the source tree ready to go.

Additionally, the speakers will be available to answer questions and to provide mentorship during Zurihac itself, so this is a great opportunity to finish your first MR.

We expect that participants already know Haskell and have worked on some form of programming language implementation in the past, whether as students, at work, or just for fun. Concepts such as parsing, type checking, unification, and code generation should be familiar, but we don't expect participants to already be experts.

## Presenters

The workshop will be instructed by seasoned contributors to GHC. So far, we have confirmed that the following GHC developers will present.

### Ben Gamari

Ben has been contributing to GHC for over a decade and been working as a full-time compiler engineer at Well-Typed since 2015. In that time he has worked across the compiler, from parsing to code generation to release management and development infrastructure. His contributions include GHC's non-moving concurrent garbage collector, GHC's type-reflection implementation, and numerous improvements in profiling. He tends to find himself working near the back end of GHC's compilation pipeline and runtime system.

### Cheng Shao

Cheng Shao is a full-time software engineer at Tweag, where he has been working since 2018. His main contribution to GHC is the WebAssembly backend, which grew out of his early research project, a Haskell-to-WebAssembly compiler codenamed Asterius. He focuses on maintaining the GHC WebAssembly backend, adding new functionality, as well as other GHC work that involves code generation and the runtime system.

### Ryan Scott

Ryan has contributed to GHC since 2015, and has worked on type class deriving, Template Haskell, pattern-match coverage checking, and various odds and ends in the type checker. He has worked as a research engineer at [Galois, Inc.](https://galois.com/) since 2020, where he works on a variety of program analysis tools such as [Cryptol](https://cryptol.net/), [Crux](https://crux.galois.com/), and [SAW](https://saw.galois.com/). In addition, Ryan maintains a large number of libraries on Hackage, and as a result, he contributes to the maintenance of [head.hackage](https://gitlab.haskell.org/ghc/head.hackage), which makes it possible to check if upcoming changes to GHC will affect the code that he maintains.

### Sam Derbyshire

Sam is a GHC contributor who joined the Well-Typed team in late 2021. Despite being relatively new to GHC, Sam has already made significant contributions to the project, such as overhauling representation-polymorphism checking and more recently the handling of duplicate record fields. He attributes this success to the wonderful community of GHC contributors who helped him become familiar with the project. In addition to his work on GHC, Sam also developed a graphics shader library in Haskell; his latest project involves typesetting Japanese sheet music for the shakuhachi.

### Sebastian Graf

Sebastian is currently a PhD student at Karlsruhe Institute of Technology. Ever since he had started his Master's thesis, he is deeply invested in the Core optimisations and static analyses of GHC and regularly contributes improvements and bug fixes in those areas. In particular, his GHC interests revolve around demand analysis, arity analysis, specialization, the simplifier and pattern-match coverage checking. At university, Sebastian assists lectures in basics of Functional Programming as well as (imperative) Compiler Design and found research interest in programming language semantics as well as Abstract Interpretation. He also is an enthusiastic trumpet player.

### Simon Peyton Jones

Simon is an Engineering Fellow at Epic Games. Until 2022, he was a researcher at Microsoft Research in Cambridge, England, where he started in 1998. He’s also an Honorary Professor of the Computing Science Department at Glasgow University, where he was a professor during 1990-1998. Simon is interested in the design, implementation, and application of lazy functional languages. He was one of the original designers of Haskell, and much of his work is focused around the Glasgow Haskell Compiler and its ramifications. Simon's earlier work was instrumental in discovering how to generate efficient code for lazy languages on stock hardware, but today, he focuses on the GHC type checker, constraint solver, and simplifier.

### Sylvain Henry

Sylvain has a background in high-performance computing and has been contributing to GHC since 2015. He joined IOG in 2019 to work full-time on GHC. Since 2022, he has led a small team of engineers working on improving Haskell tooling. His contributions include `ghc-bignum` (an improved implementation of GHC's support for big numbers), improvements to GHC's constant-folding capabilities, various fixes to the RTS, and a lot of refactoring to make GHC's code more modular and to make GHC a better cross-compiler. In 2022, his team added a new JavaScript backend to GHC, adapted from GHCJS.




## Participation

Due to space constraints and to enable scholarships for student participants, there will be a fee for full on-site participation.
Fees will be used to cover travel costs for presenters and students who don't have other funding to attend.
The fee depends on participant category:

 * _Enrolled students_ ($$40) are participants who are enrolled full-time at an educational institution. 

 * _Individual professionals_ ($$400) are no longer students and are interested in working on GHC for their own purposes. 

 * _Corporate participants_ ($$1200) are being paid by their employer to attend so that they can use the knowledge that they gain on the job. Corporate participants will have their company name on their name tag and their company will be listed on the event web page as a supporter of the event.
 
All fees are in US dollars.
We want the event to be as accessible as possible, given our limitations, so if the fee is a barrier to attending, please contact David Thrane Christiansen at [david@haskell.foundation](mailto:david@haskell.foundation) to discuss a reduced or waived fee—this goes for all three categories of participant.

A certificate of completion will be available on advance request to students who attend the entire event.

Remote participation will make use of the Zurihac infrastructure. We will do our best to stream presentations and to post recordings as quickly as possible, and we will also have a chat system for remote participants.

If you or your company would like to sponsor the event, enabling more students to have financial support to attend, please contact David Thrane Christiansen at [david@haskell.foundation](mailto:david@haskell.foundation).

Applications for the event are now closed.

<div class="flex flex-wrap items-center justify-center"><a class="block w-48" style="margin-right: 4rem"><img src="/assets/images/partners/ost_logo-400.png"></a><a class="block w-48" style="margin-left: 4rem;"><img src="/assets/images/logos/hf-logo-400px-alpha.png"></a></div>
