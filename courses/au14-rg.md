---
content_type: md
layout: main
title: PLSE Reading Group
permalink: au14-rg/
---

## UW PLSE Reading Group (Autumn 2014)

### *Wed 3:30pm in CSE 203*

We'll be reading and discussing exciting recent papers from the programming
languages and software engineering communities.  Participants should
subscribe to the [590p mailing
list](https://mailman.cs.washington.edu/mailman/listinfo/cse590n). Note the
list also has many current and former department members interested in
programming languages.

Some paper links may point into the ACM Digital Library or the
Springer online collection. Using a UW IP address, or the UW
libraries' off-campus access, should provide access.

### First Program Draft

[concurrent-haskell]: /courses/concurrent-haskell.pdf
[concurrent-haskell-extended]: /courses/concurrent-haskell-extended.pdf
[coeffects-paper]: http://www.cl.cam.ac.uk/~dao29/publ/coeffects-icfp14.pdf
[chlipala-linking]: http://adam.chlipala.net/papers/CitoOOPSLA14/CitoOOPSLA14.pdf
[haskell-resource-limits]: http://ezyang.com/papers/ezyang13-rlimits.pdf
[code-quality]: http://baishakhir.github.io/uploads/lang_study.pdf
[bidirectional-elaboration]: http://www.cs.mcgill.ca/~fferre8/papers/BidirectionalElaboration.pdf
[late-data-layout]: http://infoscience.epfl.ch/record/200963/files/ldl-oopsla14_1.pdf
[wcet-estimation]: http://drops.dagstuhl.de/opus/volltexte/2014/4600/pdf/3.pdf
[jq]: https://cs.au.dk/~amoeller/papers/jquery/paper.pdf

|----|------------------------------
| ID | Paper Assignment 
|----|------------------------------
| Oct 1 | [concurrent haskell][concurrent-haskell] ([extended version][concurrent-haskell-extended]) (dmoon, jrw)
|----|------------------------------
| Oct 8 | [coeffects][coeffects-paper] (ecr, p92)
|----|------------------------------
| Oct 15 | [chlipala linking something something][chlipala-linking] (dwoos, asnchstr)
|----|------------------------------
| Oct 22 | (affiliates)
|----|------------------------------
| Oct 29 | [resource limits haskell][haskell-resource-limits] (jtoman, cloncaric)
|----|------------------------------
| Nov 5 | [A Large Scale Study of Programming Languages and Code Quality in Github][code-quality] (kivanc, carlod)
|----|------------------------------
| Nov 12 | [bidirectional fancy][bidirectional-elaboration] (konne, epdtry)
|----|------------------------------
| Nov 19 | [late data layout][late-data-layout] (bholt, perelman)
|----|------------------------------
| Nov 26 | (thanksgiving eve)
|----|------------------------------
| Dec 3 | [wcet][wcet-estimation] (emullen,billzorn)
|----|------------------------------
| Dec 10 | [Determinacy in Static Analysis for jQuery][jq] (darioush, edward)
|----|------------------------------

### Suggestions

    p92 oopsla 14   rate types
 
    icfp 14     pattern matching w/out k
  
    Concurrent Haskell
    SPJ, POPL'96
    http://dl.acm.org/citation.cfm?id=237794

    Bidirectional Elaboration of Dependently Typed Programs
    Brigitte Pientka, PPDP'14
    http://www.cs.mcgill.ca/~bpientka/papers/reconstruction-long.pdf
  
    Programmers’ Build Errors: A Case Study (at Google)
    Caitlin Sadowski, Edward Aftandilian, Robert Bowdidge, ICSE'14
    http://static.googleusercontent.com/media/research.google.com/en/us/pubs/archive/42184.pdf
  
    Spyware: a change-aware development toolset
    (ICSE 2008)
    http://dl.acm.org/citation.cfm?id=1368219
  
    Software Developers’ Perceptions of Productivity
    (FSE 2014)
    Pre-print: http://research.microsoft.com/apps/pubs/default.aspx?id=228971
  
    Developers’ Code Context Models for Change Tasks
    (FSE 2014)
    Pre-print: https://www.merlin.uzh.ch/contributionDocument/download/7220
  
    A Large Scale Study of Programming Languages and Code Quality in Github
    (FSE 2014)
    Pre-print: http://baishakhir.github.io/uploads/lang_study.pdf
  
    A Formally Verified WCET Estimation Tool
    André Maroneze1 , Sandrine Blazy1 , David Pichardie2 , and Isabelle Puaut1
    http://drops.dagstuhl.de/opus/volltexte/2014/4600/pdf/3.pdf
  
    Verification modulo versions: towards usable verification
    PLDI
    http://dl.acm.org/citation.cfm?id=2594326
  
    Distributed REScala: An Update Algorithm for Distributed Reactive Programming
    OOPSLA
    Pre-print or something: http://www.guidosalvaneschi.com/attachments/papers/2014_Distributed_REScala_An_Update_Algorithm_for_Distributed_Reactive_Programming_pdf.pdf
  
    Compiler Verification Meets Cross-Language Linking via Data Abstraction
    Chlipala's OOPSLA paper
    http://adam.chlipala.net/papers/CitoOOPSLA14/CitoOOPSLA14.pdf
  
    Maximal Sharing in the Lambda Calculus with letrec
    ICFP
    http://www.few.vu.nl/~cgr600/linkedfiles/maxsharing-ICFP-proceedings.pdf
  
    Worker/Wrapper/Makes It/Faster
    ICFP
    http://dl.acm.org/citation.cfm?id=2628142
  
    Coeffects: A Calculus of Context-Dependent Computation
    ICFP
    http://www.cl.cam.ac.uk/~dao29/publ/coeffects-icfp14.pdf
  
    End-to-End Verification of Stack-Space Bounds for C Programs
    http://www.cs.yale.edu/homes/qcar/data/veristack-paper.pdf
  
    A Theory of Changes for Higher Order Languages
    http://arxiv.org/pdf/1312.0658v1.pdf
  
    Getting F-Bounded Polymorphism into Shape
    http://www.cs.cornell.edu/~blg59/resources/doc/effing-bound-polymorphism.pdf
  
    Resource Limits for Haskell (EZYang)
    http://ezyang.com/papers/ezyang13-rlimits.pdf
  
    Probabilistic relational verification for cryptographic implementations
    POPL
    http://dl.acm.org/citation.cfm?id=2535847
  
    CakeML
    https://cakeml.org/popl14.pdf
  
    Verve
    http://research.microsoft.com/pubs/122884/pldi117-yang.pdf
  
    VeriC
    http://vst.cs.princeton.edu/download/VerifiableC.pdf
  
    b: late data layout (oopsla 14)
       stream jit (oopsla 14)
  
    jrw: towards a formally verified proof assistant (or: nuprl in coq)
    (super secret work)
         VERDI related work
  
    d: jquery @ oopsla 14 (hybrid staged thing)
  
    vu et al. PLDI 14
  
    “Compiler Validation via Equivalence Modulo Inputs”
    Vu Le, Mehrdad Afshari, Zhendong Su
    PLDI 2014
    http://www.cs.ucdavis.edu/~su/publications/emi.pdf
