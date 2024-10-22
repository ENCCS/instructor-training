```{instructor-note}
   - 20 min teaching
   - 30 min exercises   
```

# Good Interactive Teaching Practices

```{questions}
- What is cognitive load and how does it affect learning?
- Why is motivation important?
```

```{objectives}
- Distinguish desirable from undesirable cognitive load.
```

## Cognitive load

Memory is not the only cognitive resource that is limited. Attention is constrained as well, which 
can limit the information that enters short term memory in the first place as well as interfere with 
consolidating into long-term memory. 
While many people believe that they can "multi-task", the reality is that 
attention can only focus on one thing at a time. Adding items that demand attention adds more things 
to alternate between, which can reduce efficiency and performance on all of them.

There are different theories of cognitive load. In one of these, [Sweller posits](https://doi.org/10.1207/s15516709cog1202_4) that people have to attend to three types of things when they are learning:

- Things they have to think about in order to **perform a task** ("intrinsic").
- Mental effort required to **connect the task** to new and old information ("germane").
- **Distractions** and other mental effort not directly related to performing or learning from the task ("extraneous").

Cognitive load is not always a bad thing! There is plenty of evidence that some difficulty is 
desirable and can increase learning. However, there are limits. Managing all forms of cognitive 
load, with particular attention to extraneous load, can help prevent **cognitive overload** from 
impeding learning altogether.


```{figure} img/conceptmap-cognitive-load.png
Adapted from [Teaching Tech Together](https://teachtogether.tech/en/index.html), licensed under [CC-BY-NC-4.0](https://creativecommons.org/licenses/by-nc/4.0/)
```


---

## Live demos and type-along sessions

One way to manage cognitive load as tasks become more complex is by using guided practice: creating 
a structure that narrowly guides focus on specific skills and knowledge in a stepped fashion, with 
feedback at each step before transferring attention to a new feature.

Worked examples, i.e. step-by-step demonstrations of how to perform particular tasks,  
can [reduce cognitive load](https://en.wikipedia.org/wiki/Worked-example_effect#Faded_worked_examples) 
as they provide the scaffolding needed for learners to transfer 
knowledge from working memory to long-term memory. Type-along sessions are particularly useful 
as learners get to develop their "muscle memory" while the instructor slowly walks through 
and explains each step. Splitting the task into well defined steps also helps learners 
see the underlying structure of a problem and how it can be transferred to other types of 
problems.

Exercises which learners should solve by themselves can build on the type-along 
sessions but with some of the scaffolding removed so that they need to complete some 
problem steps (faded examples). 

### Stick to the script

Learning can be enhanced by combining multiple information sources, for example by showing 
a piece of code (or a graphic or list of bullet points) while explaining it aloud. 
But make sure to stick to the script! 
Conflicting information splits the attention and leads to unnecessary cognitive load.

### Copy-pasting vs manual typing  

Manually typing out code into a programming environment takes significantly longer time than 
copy-pasting it from lesson material, but learners usually strongly prefer it. Typing out 
every single code covered in a workshop might be too much, but instructors should try to 
manually write out as much as is reasonable to do.

### Good software practices

We shouldn't assume that all learners are aware of best software development 
practices. It is therefore a good idea to adhere to good practices
in demos and type-along sessions (e.g. by following style conventions or using version control 
and testing in code examples), so that participants become acquainted with them as a side 
benefit of attending a workshop.

---

## The importance of going slow

It takes work to actively assess mental models throughout a workshop; this also takes time. This can 
make Instructors feel conflicted about using formative assessment routinely. However, the need to 
conduct routine assessment is not the only reason why a workshop should proceed more slowly than you 
think.

### Expert awareness gap 

Because your learners’ mental models will likely be less densely connected than your own, a 
conclusion that seems obvious to you will not seem that way to your learners. It is important to 
explain what you are doing step-by-step, and how each step leads to the next one.

Note that the expert awareness gap is also referred to as "expert blind spot". 

### Taking advantage of errors

Experts can quickly diagnose errors which may seem cryptic to novices or competent practitioners. 
If faced with an error message while teaching, an expert will often automatically diagnose and solve 
a problem before a novice has even finished reading the error message. Because of this, it is very 
important while teaching to be explicit about the process you are using to engage with errors, even if 
they seem trivial to you, as they often will.

When faced with an error message, take the time to explain what happened and how the error message 
can be understood. This will not only teach learners to understand and read stack traces, but also 
give them confidence from seeing that even an expert makes mistakes!


### Meta-talk

Don't just teach, also make sure you guide the learners through the
course.

- You know what you just discussed, and what is coming next, but
  learners are often stuck thinking about what is happening right now.
- Give a lot of "meta-talk" that is not just about the topic you are
  teaching, but how you are teaching it.
- Examples
  - **Why** you are doing each episode
  - What is the purpose of each exercise
  - Clearly state what someone should accomplish in each exercise and
    how long it will take - don't assume this is obvious.
  - What is the point of each lesson.  How much should people expect
    to get from it?  Should you follow everything, or are some things
    advanced and optional?  Make that clear.


---


````{challenge} What are the top issues new instructors face? (10 minutes)
Brainstorm about what issues new teachers/instructors might face in interactive workshops.
Write down your thoughts in the shared document.
 
```{solution} Some suggestions
Addressing participant issues:
 -  Get the speed correct: not too fast and not (far) too slow. 
 -  Don't make exercise sessions too short to "save time". Better to have them as long as possible.
 -  Don't expect too much of learners during exercises - just reading and understanding the task takes time.
 -  Cater to participants with different backgrounds and at different levels of experience.
 -  Learners may not have software prerequisites installed correctly and thus not able to follow along.
 Instructor mistakes:
 -  Trying to accomplish too much or go through everything - it's OK to cut out and adapt to the audience. 
 -  Explaining *how*, but not *why*.
 -  Not using good screen sharing practices (font size, terminal history, portion of screen)
 -  Assuming learners remember everything you've covered earlier in a workshop.
 -  Forgetting to take sufficiently many breaks (minimum 10 minutes per hour)
```
````

---

## Keeping learners motivated

People learn best when they care about a topic and believe they can master it with a reasonable 
investment of time and effort. A distinction is often made between **extrinsic motivation**, 
which we feel when we do something to avoid punishment or earn a reward, and **intrinsic motivation**, 
which is what we feel when we find something personally fulfilling.

According to [self-determination theory](https://en.wikipedia.org/wiki/Self-determination_theory), 
the three drivers of intrinsic motivation are:

- **Competence**: the feeling that you know what you’re doing.
- **Autonomy**: the feeling of being in control of your own destiny.
- **Relatedness**: the feeling of being connected to others.

Well-designed lessons and teaching encourage all three. 

**Belonging**

- It's been estimated that nearly 70\% of individuals will experience 
  signs and symptoms of impostor syndrome at least once in their life! Research shows that 
  this phenomenon is not uncommon for students who enter a new academic environment.
- If learners feel that they belong and are accepted in a learning environment they will 
  be more motivated to learn. 
- Having, discussing, and enforcing a Code of Conduct provides a framework for positive 
  communication to occur.


**Invite Participation**

- Encourage learners to learn from each other. Working in pairs or in groups encourages learners to 
  talk through their learning process, reinforcing memory and making it more likely that confusion 
  will be expressed and resolved. This can also address challenges of varying background experience: 
  asking more advanced learners to help beginners can maximize learning for both. In these cases, 
  make sure the beginner is doing the typing!
- Acknowledging when learners are confused. Acknowledging and exploring confusion with kindness 
  rewards learners for sharing vulnerable information. Formative assessments can pinpoint misunderstandings. When learners see that 
  others are confused, they are more likely to share their own uncertainties.

**Any questions?**

Instructor may accidentally dismiss learner confusion by asking for questions in a way that 
reveals that they do not actually expect that anyone will have them. 
Instead of asking "Does anyone have any questions?" and then quickly moving on, 
consider asking instead "What questions do you have?" and leaving a good pause for 
consideration. This establishes an expectation that people will, indeed, have questions, and 
should challenge themselves to formulate them.


**Do no harm!**  

Here are a few things you should not do in your workshop:

- Talk contemptuously or with scorn about any tool or practice, or the people who use them. 
  Regardless of its shortcomings, many of your learners may be using that tool, and may have invested many years in learning to do so. 
- Dive into complex or detailed technical discussion with the one or two people in the audience who 
  clearly don't actually need to be there. Reserve those conversations for breaks or follow-up emails.
- Pretend to know more than you do. People will actually trust you more if you are frank about the 
  limitations of your knowledge, and will be more likely to ask questions and seek help. 
- Use the J word ("just") or other demotivating words. Experts sometimes want to convey that 
  a task is as easy as they think it is, but these signal to the learner that the instructor thinks 
  their problem is trivial
- Take over the learner's keyboard. It is rarely a good idea to type anything for your learners. 
  Doing so can be demotivating for the learner (as it implies you don't think they can do it themselves or that you don't want to wait for them). It also wastes a valuable opportunity for your learner to develop muscle memory and other skills that are essential for independent work.
- Express surprise at unawareness. Saying things like "I can’t believe you don’t know X" or "You’ve 
  never heard of Y?" signals to the learner that they do not have some required pre-knowledge of the 
  material you are teaching, that they don’t belong at the workshop, and it may prevent them from 
  asking questions in the future.

**Does your motivation matter?**

- Learners respond to an instructor’s enthusiasm. The more motivated you are, the more motivated 
  they will be!
- Instructors are learning to teach. This also takes motivation. Deliberative practice, seeking 
  feedback, and reflecting on mistakes in the context of your own busy work life is a challenge. 
  What will keep you energised to stay engaged with your learning process?

---

## Giving feedback for live coding examples

Teaching by live coding is a
[performance art which requires practice](https://teachtogether.tech/en/index.html#s:performance).
These exercises aim at learning to give feedback. We will watch videos of (pretend) teaching and 
give feedback on two axes: positive vs. negative and content vs. presentation. 
We will use a [rubric](http://carpentries.github.io/instructor-training/demos_rubric/) (used during 
The Carpentries teaching demos) to help take notes.

Each person in the class adds one point to a 2x2 grid on a whiteboard or in the shared notes 
without duplicating any points.
For online instructor training event, use breakout room (4-5 persons per group) to facilitate discussion. Then each group reports to the shared notes.

```{figure} img/2x2-rubric.png
Adapted from [Teaching Tech Together](https://teachtogether.tech/en/index.html), licensed under [CC-BY-NC-4.0](https://creativecommons.org/licenses/by-nc/4.0/)
```

`````{challenge} Live coding example 1 (20 min)
This exercise highlights some typical pitfalls that most instructors
fall into sooner or later, and also shows how to avoid them.
Watch closely since we will be giving feedback!
- Watch these two videos: [video 1](https://youtu.be/bXxBeNkKmJE) and
  [video 2](https://youtu.be/SkPmwe_WjeY)
- What was better in video 1 and what was better in video 2?
- Please give feedback in the shared workshop document in the 2x2 rubric.

````{solution} Template for feedback rubric
```
Positive Content:
- 
- 
- 

Content Opportunities for Growth:
- 
- 
- 

Positive Delivery:	
- 
- 
- 

Delivery Opportunities for Growth
- 
- 
- 
```
````
`````

```{challenge} (Optional) Live coding example 2

As a group, we will watch [this video of teaching](https://www.youtube.com/watch?v=-ApVt04rB4U).
The instructor is making several mistakes, but can you also observe anything positive?

As before, give feedback on two axes: positive vs. negative and content vs. presentation. 
What did other people see that you missed? What did they think that you strongly agree or disagree with?
```



