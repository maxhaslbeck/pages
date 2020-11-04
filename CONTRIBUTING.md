---
title: Contributing to the Survey
permalink: /CONTRIBUTING
---

# Contributing to the Survey

We welcome contributions from the community to keep this website as complete and up-to-date as possible.
To ensure the scope and quality of the material we have the following guidelines, restrictions and notes on how the process works.

### Scope of Survey

- We restrict the list to algorithms and data structures that appear in standard algorithms textbooks. 

- We only accept peer-reviewed publications and formalizations from some archive (like [AFP](https://www.isa-afp.org/)). 
In some cases official technical reports and theses are okay.
To keep the list compact, we will reject arbitrary links.


### Structure

- For organizing the list we use the structure in "Introduction to Algorithms" by Cormen et al (CLRS).
- Material that is not covered by CLRS but clearly goes into one of its sections should be included there.
- Algorithms that do not fit into the structure but still are "textbook" should go into the section [Additional Textbook Algorithms](Additional_Textbook_Algorithms.md).
- While the survey only talks about material that already has been formalized we would like to add a list of "yet unverified" material. 
This should motivate to tackle this material (like e.g. [Wiedijk's 100 theorems list](https://www.cs.ru.nl/~freek/100/)) in order to remove them from that list.
The section [Unverified(?) Textbook Algorithms](Unverified_Textbook_Algorithms.md) should give a quick overview which textbook algorithms are unverified, or not known to be verified.


### How to contribute

- The preferred way of contribution is through a [pull-request](https://opensource.guide/how-to-contribute/#opening-a-pull-request) to the [github project](https://github.com/maxhaslbeck/pages).
- You can also send interesting references that are in scope of this list via email to <haslbema@in.tum.de>.
- We will try to answer your pull-requests and contributions within 2 weeks.
- Add a reference: add an bullet point item into the correct section, with a succint answer to the following questions:
  - what algorithm was it?
  - what was proven? (functional correctness, running time)
  - which system was used?
  - where can the reference be found? (add a link and a abbreviation containing the conference/journal and a two digit number for the publishing year)
- Add an algorithm/data structure to the [Additional Textbook Algorithms](Additional_Textbook_Algorithms.md) or [Unverified(?) Textbook Algorithms](Unverified_Textbook_Algorithms.md): add a section to the respective list and state which text books mention this algorithm.
- If you find a dead link or spelling mistakes, we welcome corrections.

### **Working on your first Pull Request?**
You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github) 



