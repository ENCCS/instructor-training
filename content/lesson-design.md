```{instructor-note}
   - 20 min teaching
   - 20 min exercises
   - 45 min practice (optional)
```   

# Lesson Design

```{questions}
- How can we design lessons to work with, rather than against, memory constraints?
```

```{objectives}
- Understand the principles behind backwards lesson design.
- Remember a few tricks for facilitating memory retention.
```

## Backwards lesson design

When composing new instructional material - lessons - we can take a “reverse” approach to instruction, 
as described in Wiggins and McTighe’s 
[Understanding by Design](http://www.worldcat.org/title/understanding-by-design/oclc/56491025),
that keeps the focus firmly on learning outcomes. The order of preparation in this case becomes

- Determine your learning objectives.
- Decide what constitutes evidence that objectives have been met, and design assessments to target that evidence.
- Design instruction: Sort assessments in order of increasing complexity, 
  and write content that connects everything together.

### Deciding what to teach: visual guide

```{figure} https://carpentries.github.io/instructor-training/fig/what-to-teach.png
:width: 60%
```


### Working with learning objectives

Lessons should have a clear *learning objectives* section.
Good learning objectives are quite specific about the intended effect of a lesson on its learners.
We should aim to create learning objectives that are specific, accurate, and informative for 
both learners and instructors.

In practice, it's best to start defining your target audience by answering to questions
such as:
- **What is the expected educational or skill level of my audience?** 
- **Have they been already exposed to the technologies I am planning to teach?** 
- **What tools do they already use?** 
- **What are the main issues they are currently experiencing?**

Once you clarified your target audience, it is useful to create
**learner personas**. This will help you during the development process by
providing concrete examples of potential learners showing up at your
workshops. 

- For each **learner persona**, try to think of what is **useful to them**. 
- What do they **need** to remember/understand/apply/analyse/evaluate/create (see Bloom's taxonomy below).
- Then, you create a sequence of exercises which test incrementally
  progressing tasks and acquisition of the new skills.
- Finally, you write material to teach the gap between exercises.


```{figure} img/learner_personas.png
:width: 80%
Image credit: ChatGPT4o
```

| | Alex the Data Scientist | Maria the CFD Engineer |
| --- | ---- | ---- |
| **Age** | Late-20s | Mid-30s|
| **Occupation**| Data Scientist at an SME | CFD Engineer at a large company |
| **Skills** | Proficient with tools like TensorFlow, <br>PyTorch, and scikit-learn. Experienced <br>with cloud services and Python, R, SQL. | Proficient with commercial CFD packages like <br>Ansys Fluent and COMSOL Multiphysics. Experienced <br>in managing complex workflows on local servers. |
| **Experience**| 5 years in data science, focusing on <br>machine learning models and optimization. | Experienced in running simulations on local <br>clusters and analyzing 3D fluid dynamics. |
| **Pain Point**| Limited by local computing resources <br>and cloud costs for large-scale projects. | Needs  higher spatial resolution and wants to migrate to open <br>source software to avoid prohibitively high licensing costs.|
| **HPC Experience**| None, eager to learn how to scale <br>AI workloads using HPC. | Has experience with smaller on-prem clusters but needs to <br>transition to EuroHPC for massively parallel simulations. |
| **Learning Style**| Prefers hands-on learning, real-world <br>examples, and collaborative environments. | Hands-on, enjoys working with complex <br>technical systems, and prefers practical challenges. |
| **Goal**| To learn how HPC can enhance AI model <br>performance and optimize workflows. | To master running highly parallel OpenFOAM simulations <br>on EuroHPC for faster, more efficient results.|


### Using Bloom's Taxonomy to write effective learning objectives

[Bloom's Taxonomy](https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/) is a framework for 
thinking about learning that breaks progress down into discrete, hierarchical steps.
While many ideas have come and gone in education, Bloom's has remained a useful tool for educators, 
in particular because the
hierarchy seems to be reasonably valid: outcomes at the top of the hierarchy cannot be achieved 
without mastery of outcomes at
the bottom. 

```{figure} https://carpentries.github.io/instructor-training/fig/Blooms.png
Image credit: Vanderbilt University Center for Teaching
```

```{challenge} How do you design? (10 min)
Discuss either in groups or via collaborative document:
- How do you start when you design a new lesson/presentation?
- Has your approach changed over the years? If yes, how?
```

---

## Memory management

Learning involves memory. For our purposes, human memory can be divided into two different 
layers, **long-term** and  **short-term**. 
Long-term memory, which we use to store persistent information, is essentially unbounded but is 
slow to access. Short-term memory (also called working memory), which we use to actively think 
about things, is much faster but also much smaller. It has been estimated that the average 
adult's short-term memory can hold 7±2 items for a few seconds before things start to drop out. 

```{figure} img/cognitive-architecture.png
Figure adapted from [Teaching Tech Together](https://teachtogether.tech/en/index.html), licensed under [CC-BY-NC-4.0](https://creativecommons.org/licenses/by-nc/4.0/)
```

If we present our learners with large amounts 
of information, without giving them the opportunity to practice using it (and thereby 
transfer it into long-term memory), they will not retain the material as well as if we 
present small amounts of information interspersed with practice opportunities. 

When designing lessons we can try to maximise memory retention through a number of strategies:

- **Chunking**: Our minds can store larger numbers of facts in short-term memory by creating 
  chunks, or relationships among separate items, allowing them to be remembered as a single 
  item. Connecting information makes it easier to remember.
- **Formative assessment to support memory consolidation**: Formative assessment helps 
  learners solidify their understanding and begin transferring ideas into long-term memory.
  Limitations of short-term memory are one reason why assessments should be frequent: short-term memory is limited not only in space, but also in time.
- **Group work**: Elaboration (explaining your work) supports transfer to long-term 
  memory. This is one reason why teaching is one of the most effective ways to learn! Group 
  work can feel uncomfortable at first and consumes time in a workshop, but learners often 
  rate group work as a high point for both enjoyment and learning in a workshop.   
- **Opportunities for reflection**: Reflection is another tool that can help learners review 
  things they have learned, strengthen connections between them, and consolidate long-term 
  memories. Asking learners for feedback can be an effective consolidating prompt as providing 
  feedback demands some reflection on what has been learned.
- **Counting new concepts**:  It is important to limit the number of concepts introduced in a lesson, but
  this can be hard! Planning your lesson with a concept map can help you not only identify key 
  concepts and relationships, but also to notice when you are trying to teach too many things at 
  once.

```{callout} Formative and summative assessment
*Formative assessment* takes place during teaching and learning. It sounds like
a fancy term, but it can be used to describe any interaction or activity
that provides **feedback to both instructors and learners about learners' level of understanding** 
of the material. For learners, this feedback can help focus their study efforts. For instructors, it 
allows them to refocus their instruction to respond to challenges that learners are facing.
Used continuously.
 
*Summative assessment* is used to judge whether a learner has reached an acceptable level of competence.
Usually, at the end of a course learners either "pass" or "fail" a summative assessment.
```

````{challenge} Reflection (3 minutes)
What is one key goal of backwards lesson design?

1. To focus on the sequence of exercises
2. To prioritize what instructors want to teach
3. To focus on what learners should achieve by the end of the lesson
4. To use as much information as possible in a short time

```{solution}
The correct answer is *3. To focus on what learners should achieve by the end of the lesson*.
```
````

---

## Designing formative assessment

Well designed formative assessment tasks -- i.e. quick questions and exercises -- 
can go a long way towards correcting misconceptions and expanding the mental models of learners.

Here are some suggestions to keep in mind when designing exercises:

- Not every exercise has to be an amazing hand-on example. Mixing with smaller, more conceptual 
  things can reduce [cognitive load](https://enccs.github.io/instructor-training/interactive-teaching/#cognitive-load).
- Try to make your exercises relevant, meaningful and connected to previous knowledge. 
  Connect the exercises to the real world. When learners understand the meaning of new concepts 
  it will be easier for them to remember.
- Create more involved exercises that can be optional for more advanced learners.
  This is a way to meet the needs of participants with a wide range of background knowledge. 

```{callout} Good exercises are the most important factor in a good lesson
Even if you are preparing the rest of 
the lesson mostly alone, consider a good long brainstorming session to go from "list of topics to 
cover" to "sequence of exercises".
```

When you are stuck thinking "how can I make an exercise that covers X", look through the lists below for
inspiration. Not every exercise has to be an sophisticated hands-on thing, so don’t be afraid to use 
different types:

**Types of exercises**:

- Multiple choice (easy to get feedback via a classroom tool; try to design each wrong answer so that it identifies a specific misconception).
- Code yourself (traditional programming).
- Code yourself + multiple choice to see what the answer is (allows you to get feedback).
- Minimal fix (given broken code, make it work).
- Parsons problems (working solution but lines in random order, learner must "only" put them in proper order).
- Fill in the blank, [faded problems](https://en.wikipedia.org/wiki/Worked-example_effect).
- Tracing execution.
- Tracing values through code flow.
- Reverse execution (find input that gives an output).
- Theme and variations (working code, adapt to other type of situation/problem).
- Refactoring.
- Draw a diagram.
- Label diagram.
- Matching problem: two sets of Q/A, match them.

**Tip**:

When designing exercises, consider that some participants will get stuck
and may want to re-join at a later exercise. In other words it is nice
if exercises build up on each other but not at the cost that if participants
get stuck at exercise 2, they will not be able to do exercises 3 to N.


```{figure} img/conceptmap-assessment.png
Adapted from [Teaching Tech Together](https://teachtogether.tech/en/index.html), licensed under [CC-BY-NC-4.0](https://creativecommons.org/licenses/by-nc/4.0/)
```

````{discussion} Using formative assessment to identify misconceptions
Formative assessment can be used to tease out misconceptions using for example multiple choice 
questions (MCQ). When designed carefully, MCQs can target anticipated misconceptions with surgical 
precision. 

For example, suppose we are teaching children multi-digit addition. A well-designed MCQ could be:

Q: what is 27 + 15 ?
- a) 42
- b) 32
- c) 312
- d) 33

What misconceptions do the wrong answers reveal?

```{solution}
- If the child answers 32, they are throwing away the carry completely.
- If they answer 312, they know that they cannot just discard the carried ‘1’, but do not understand that it is actually a ten and needs to be added into the next column. In other words, they are treating each column of numbers as unconnected to its neighbors.
- If they answer 33 then they know they have to carry the 1, but are carrying it back into the same column it came from.
```
````

```{challenge} Design formative assessment to identify misconceptions (10 min)

Individually or in groups, choose a topic that you have taught in the past or that you want to 
teach later. 
- What relevant misconceptions might a novice learner bring to the classroom?
- Create your question. How many choices can you think of that will diagnose a specific misconception?

Type your question into the shared document and explain the diagnostic power of each choice.
Discuss the question in the classroom.
```

```{challenge} Design a faded example (10 min)
This exercises assumes that you are teaching a technical topic like programming or similar.

- Try to design a faded example, i.e. an example code where learners should fill in the blanks.
- Think of the level of your learners. How much would you fade out for a novice? How about a 
  competent practitioner?
- How did you decide what to fade out?
- Present your example in a small group and let others in your team guess which level you intended 
  the example for!
```

---

## Practice backwards design


```{discussion} Discuss the backwards-design of a lesson

Let's take as an example the *[HPC Carpentry lesson](https://carpentries-incubator.github.io/hpc-intro/)*

**Target audience**
  - What is the expected educational level of my audience?
      - A PhD student, postdoc or young researcher.
  - Have they been already exposed to the technologies I am planning to teach?
      - The word **HPC** is not new to them and they may have already used an HPC but are still not capable of giving a proper definition of HPC. In addition, we do not expect them to know much about parallelism and they cannot make any distinction between various available parallelism paradigms.
  - What tools do they already use?
      - serial codes, multi-threaded codes, data parallelism; usually out-of-the-box tools.
      - they may have tried to "scale" their code (multiprocessing, threading, GPUs) with more or less success.
  - What are the main issues they are currently experiencing?
      - they cannot solve their problems either because they would like to run the same code but with many different datasets or because their problem is larger (more computations/memory).
      - most of the time they know their codes can run on HPC (from the documentation) but never really had the opportunity to try it out.
      - Very few will have their own codes where they may have tried different things to speed it up (threading, task parallelism) but have no clear strategy.

**Learner persona**
  - Sonya is a 1st year PhD student: she recently moved to Oslo and joined the
    Computational and Systems Neuroscience group. She will be using the
    [NEST](https://nest-simulator.readthedocs.io/), a simulator for spiking
    neural network model. She used NEST during her master thesis but on her
    small cluster: **she never used an HPC resource** and is really excited about it.
  - Robert is a field ecologist who obtained his PhD 6 months ago. He is now
    working on a new project with Climate scientists and as a consequence will
    need to run global climate models. He is **not very familiar with command
    line** even though he attended a Software Carpentry workshop and the idea to
    use HPC is a bit terrifying. He knows that he will get support from his
    team who has extensive experience with HPC but would like to become more
    independent and be able to **run his own simulations** (rather than copying
    existing cases).
  - Jessica is a postdoc working on a project that investigates numerically the
    complex dynamics arising at the tip of a fluid-driven rupture. Fluid
    dynamics will be computed by a finite element method solving the
    compressible Navier-Stokes equations on a moving mesh. She **uses a code she
    has developed** during her PhD and that is based on existing libraries. She
    has mostly ran it on a local desktop; her work during her PhD was very
    limited due to the lack of computing resources and she is now very keen is
    **moving to HPC**; she knows that it will requires some work, in particular to
    parallelize her code. This HPC training will be her first experience with
    HPC.

**Learning outcomes**
  - Understand the difference between HPCs and other local/remote machines
  - Understand the notion of core, nodes, cluster, shared/distributed memory, etc.
  - Understand the notion of login nodes.
  - Understand the need for a scheduler and how to use it appropriately
  - Understand why optimising I/O is important on HPC and how to best use HPC filesystems
  - Understand the need to parallelize (or use existing parallel) codes and in which cases HPCs is a must (when communications is required)
  - Understand how to get your code ready to use on HPC (access to libraries, installation of your own libraries/software, etc.)
  - Understand that an HPC is an operational machine and is not meant for developing codes.

**Exercises**
  - Get basic information such the number of CPUs, memory from your laptop and try to do the same on a HPC. Discuss outcomes.
  - Try to create files on the different filesystems on your HPC resource and access them.
  - Create different types of job scripts, submit and check outputs.
  - Make a concrete example to run a specific software on your HPC (something like GROMACS).
```

```{challenge} Backwards-design a lesson (45 min)
Choose a simple lesson topic and apply backwards lesson design.  You
won't get all the way through, but come up with a logical
progression of exercises.

The section you pick should require **screen sharing** and be of some **follow-along
task** (preferably using a shell).

Some suggestions:
- Regular expressions
- Making papers in LaTeX
- Making figures in your favorite programming language
- Linux shell basics
- SLURM
- Some part of an already existing lesson
- A lesson you always wanted to teach
- Something non-technical, such as painting a room

Exercise (30 minutes):
- Collect notes in a shared document.
- Start with learner personas and learning outcomes.
- Come up with a logical progression of exercises.

Discussion (15 minutes):
- How does this approach compare to other lessons or courses you have designed?
- We read, compare, and discuss our notes.
```


## See also

- CodeRefinery [lesson-design](https://coderefinery.github.io/manuals/lesson-design/) manual
- [The Carpentries Curriculum Development Handbook](https://cdh.carpentries.org)
- [Teaching Tech Together](http://teachtogether.tech/)
- A short [summary](https://coderefinery.github.io/manuals/teaching-tech-together/) of "Teaching Tech Together"
- [Ten quick tips for creating an effective lesson](https://doi.org/10.1371/journal.pcbi.1006915)

```{keypoints}
- Having a semi-rigid lesson design process can **save time** to start drafting and will probably **increase quality and relevance** of the lessons 
```
