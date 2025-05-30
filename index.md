---
layout: home
# title: Concurrent Programming 24/25 (CC3037)
---

The goal of this course is to introduce students to the fundamental theoretic and practical principals of concurrency, with emphasis on the correctness, design and implementation of models of concurrent computation using shared memory architectures.

 - __The 1st part__ of the course is more fundamental and is given by Nelma Moreira. More information [here](https://www.dcc.fc.up.pt/~nam/Teaching/progcon2425/).
 - __This 2nd part__ of the course will focus on the programming aspect, using the Scala language to study several concurrency patterns and libraries in Java Virtual Machines.
- Other links:
   - [Moodle](https://moodle2425.up.pt/course/view.php?id=6292): management of the presence of students and other links;
   - [Sigarra@FCUP](https://sigarra.up.pt/fcup/pt/ucurr_geral.ficha_uc_view?pv_ocorrencia_id=548313): the official plan of this course.


 <!-- - __Summaries__ and __assignments__ are placed in the associated [Moodle website](https://moodle2324.up.pt/course/view.php?id=1748). -->


# Lectures

- __27 Mar 25__: [T] Introduction to the second module ([1-intro.pdf](slides/1-intro.pdf)). Overview of Scala ([2-scala.pdf](slides/2-scala.pdf)).  
[P] Exercises on Scala ([ex-scala.pdf](exercises/ex-scala.pdf)).
- __3 Apr 25__:  [T] Introduction to the Java Memory Model ([3-javamemory.pdf, slides 1-26](slides/3-javamemory.pdf)).  
[P] Exercises on the Java Memory Model ([ex-javamemory.pdf](exercises/ex-javamemory.pdf)).
- __24 Apr 25__ (planned): [T] Waiting and notifying; Graceful shutdown ([3-javamemory.pdf, slides 28-end](slides/3-javamemory.pdf)). Executors and ExecutionContext; atomic variables ([4-concblocks.pdf](slides/4-concblocks.pdf)).  
[P] Continuation of exercises on the Java Memory Model with waiting states ([ex-javamemory.pdf](exercises/ex-javamemory.pdf)); Execution contexts ([ex-concblocks.pdf](exercises/ex-concblocks.pdf)).
- __15 May 25__: [T] Recall Executors and ExecutionContext; atomic variables; using compare-and-swap; the ABA problem; processes outside the JVM; lazy values and hidden locks ([4-concblocks.pdf, slides 4-28](slides/4-concblocks.pdf)).  
[P] Continuation of exercises on concurrency building blocks, using atomic variables and lazy concepts ([ex-concblocks.pdf](exercises/ex-concblocks.pdf))
- __22 May 25__: [T] Concurrent structures: thread-safe queues and maps ([4-concblocks.pdf, slides 28-36](slides/4-concblocks.pdf)); Actor in Akka: creation, execution, and behaviour ([5-actors.pdf, slides 1-15](slides/5-actors.pdf)).  
[P] Recalling atomic variables ([ex-concblocks.pdf](exercises/ex-concblocks.pdf)); deploying actors in Akka ([ex-actors.pdf](exercises/ex-actors.pdf)]); support for the [practical assignment](exercises/cp-project-2425.pdf).
- __29 May 25__:[T] Futures and promises: creating, using, poling, and composing futures. Actors in Akka: actor hierarchy amd relation with CCS ([5-actors.pdf, slides 20-32](slides/5-actors.pdf)).  
[P] Exercises on Futures & Promises ([ex-futures.pdf](exercises/ex-futures.pdf)); deploying actors in Akka ([ex-actors.pdf](exercises/ex-actors.pdf)]); support for the [practical assignment](exercises/cp-project-2425.pdf). 


<!-- 
- __18 Apr 24__: [P] Exercises on the Java Memory Model ([ex-javamemory.pdf](exercises/ex-javamemory.pdf)). [T] Waiting and notifying; Graceful shutdown ([3-javamemory.pdf, slides 28-end](slides/3-javamemory.pdf)). Executors and ExecutionContext; atomic variables ([4-concblocks.pdf, slides 1-9](slides/4-concblocks.pdf)).
- __2 May 24__: [P] Continuation of exercises on the Java Memory Model with waiting states ([ex-javamemory.pdf](exercises/ex-javamemory.pdf)); Execution contexts ([ex-concblocks.pdf](exercises/ex-concblocks.pdf)). [T] Using compare-and-swap; the ABA problem; lazy values and hidden locks ([4-concblocks.pdf, slides 8-33](slides/4-concblocks.pdf)).
- __9 May 24__:[P] Continuation of exercises on concurrency building blocks, using atomic variables and lazy concepts ([ex-concblocks.pdf](exercises/ex-concblocks.pdf)). [T] Processes outside the JVM ([4-concblocks.pdf, slides 34-36](slides/4-concblocks.pdf)); Actor in Akka: creation, execution, and behaviour, hierarchy and lifecycle ([5-actors.pdf, slides 1-19](slides/5-actors.pdf)).
- __23 May 24__:[P] Recalling atomic variables ([ex-concblocks.pdf](exercises/ex-concblocks.pdf)); deploying actors in Akka ([ex-actors.pdf](exercises/ex-actors.pdf)]); support for the [practical assignment](exercises/cp-assignment-2324.pdf). [T] Actors in Akka: relation with CCS, handling exceptions, termination, remote actors ([5-actors.pdf, slides 20-32](slides/5-actors.pdf)), support for the [practical assignment](exercises/cp-assignment-2324.pdf).
-->

# Literature and Material

### Slides
1. [Introduction to the second module](slides/1-intro.pdf)
2. [Scala primer](slides/2-scala.pdf)
3. [Java Memory Model](slides/3-javamemory.pdf)
4. [Basic building blocks of concurrency](slides/4-concblocks.pdf)
5. [Actor model](slides/5-actors.pdf)


### Exercises

1. [Exercises on Scala](exercises/ex-scala.pdf)
2. [Exercises on Java Memory](exercises/ex-javamemory.pdf)
4. [Exercises on building blocks of concurrency](exercises/ex-concblocks.pdf)
5. [Exercises on the actor model](exercises/ex-actors.pdf)
6. [Exercises on futures and promises](exercises/ex-futures.pdf)

<!--
3. [Exercises on Java Memory](exercises/ex-javamemory.pdf)
4. [Exercises on building blocks of concurrency](exercises/ex-concblocks.pdf)
5. [Exercises on the actor model](exercises/ex-actors.pdf)
 -->

### Examples of exams and tests
- [2023-2024 - Test for the second module (at _época normal_)](https://fm-dcc.github.io/pc2324/exercises/cp-test-normal24.pdf)
- [2018-2019 - Test for the first module (authentication needed - during the semester)](https://www.dcc.fc.up.pt/~nam/Teaching/progcon2324/ligacoes/index.html)


### Assignment

- [Practical assignment on Concurrent Programming 2024/25](exercises/cp-project-2425.pdf)
- Chose your group [via Moodle](https://moodle2425.up.pt/mod/choicegroup/view.php?id=186186) - there should be two people in each group.

<!-- - Submit your assignment [via moodle](https://moodle2324.up.pt/mod/assign/view.php?id=180761) (only one of the group members needs to submit it, and the latest submission is used) -->
<!-- - Book your presentation using this [shared spreadsheet](https://docs.google.com/spreadsheets/d/1HZqn6nFbYI_LbvfNnqcqlh0gF30DGociU0w0wfwkiyg/edit?usp=sharing) (you must login with your google account from the faculty, e.g., "up202000000@g.uporto.pt") -->


### Main book

- [Learning Concurrent Programming in Scala](https://www.amazon.com/Learning-Concurrent-Programming-Scala-Second-dp-1786466899/dp/1786466899/ref=dp_ob_title_bk), _Aleksandar Prokopec_; ISBN: 1786466899


### Previous years

- (2023/24): [https://fm-dcc.github.io/pc2324](https://fm-dcc.github.io/pc2324/)
- (2018/19): [https://www.dcc.fc.up.pt/~nam/Teaching/procon20/](https://www.dcc.fc.up.pt/~nam/Teaching/procon20/)
  
<!-- 
### Complementary Bibliography

- ...
 -->


# Teaching methods and learning activities

Lectures; intermediate test (mandatory) and final test  or final exam.

The lectures mix the presentation of new material (introducing concepts, main algorithms and some results) with interactive discussion of their application when solving real problems.

The homework focus is on practical application of algorithmic concepts, consolidating the learned material. 

The final exam and intermediate tests (closed book), globally evaluates the knowledge acquired by the students.


# Evaluation Type

Distributed evaluation with final exam

### Assessment Components

|designation | Weight (%)|
|------------|-----------|
|Exam |70,00|
|Assignment | 30,00|


<!-- ### Amount of time allocated to each course unit

|designation | Time (hours)|
|------------|-------------|
|Home study | 56,00|
|Attendance time | 56,00|
|Assignment | 56,00|
|**Total:** | 162,00| -->


# Eligibility for exams

Students must attend at least 75% of the practical classes to be admitted to the exams.


# Calculation formula of final grade

Distributed evaluation will include both modelling (EM) and program implementation (EI). The final grade (FG) is obtained by weighting the distributed assessment scores and final exam (FE) as follows:

 - __FG__ = 3 * EM + 3 * EI + 14 * FE.


# Lecturers

  - 
    + ![Nelma Moreira's photo](assets/img/photos/nam.jpg)
    + <a></a>
      * [Nelma Moreira](https://www.dcc.fc.up.pt/~nam/)
      * <a></a>
        + DCC 1.20
        + nelma.moreira<span>(at)</span>fc.up.pt
        + meet: tba <!-- thu afternoon (email before) -->
        {: .myInterests}
      {: .myMemberSubItems}
    {: .myMemberItems}
  - 
    + ![José Proença's photo](assets/img/photos/jp.jpg)
    + <a></a>
      * [José Proença](https://jose.proenca.org)
      * <a></a>
        + DCC 1.69
        + jose.proenca<span>(at)</span>fc.up.pt
        + meet: tba <!-- thu afternoon (email before) -->
        {: .myInterests}
      {: .myMemberSubItems}
    {: .myMemberItems}
  {: .myMembers}


   


Edit the content of this page [here](https://github.com/FM-DCC/cp2425/blob/main/index.md).
{: .editNote}
