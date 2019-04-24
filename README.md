# Prepare to Teach

Doing and teaching are different skills.  Studying code to teach is not the same as studying code to program.  You will need to learn to code a bit yourself, but more imprtanlty you'll need to learn what concepts and skills are most challenging for novices and how to teach them.  This is called Pedagogical Content Knowledge - knowing how to teach a thing not, not just do it.

Helping your students transition to full-on programming can take a bit of preparation  You'll need to familiarize yourself with your students' programming language & environment, create exercises & projects, and ideally figure out how to integrate programming with other subjects your students are learning.  Knowing the environment and langauge from your student's perspective will allow you to make the best exercisees and projects.

Fortunately some of the most effective programming exercises are also the easiest to prepare, with a little modification you can turn your own practice scripts into a series of exercises that you already know inside and out. 

Unfortunately, programming outside of Turtle drawings or Scratch is not as immediately rewarding for students.  A working program no longer result in an engaging animation or game.  This creates for you the challenge (and opportunity!) of integrating programming into other subjects, treating it less as a separate subject and more like the applied & embedded skill that it is outside of school.

### Index:
* [Choose a Language and Environment](#choose-a-language-and-environment)
* [Pedagogical Content Knowledge](#pedagogical-content-knowledge)
* [Practice Coding and Prepare Exercises](#practice-coding-and-prepare-exercises)
* [Use Integrative Projects](#use-integrative-projects)
* [Plan Off-Line Interactions](#plan-off-line-interactions)
* [Coding is not about Code](#coding-is-not-about-code)
* [Resources](#resources)

--- 

## Choose a Language and Environment

Language and environment are both important, and intimately related.  It's not possible to pick any combination of language & environment you like.  So consider your students, your learning objectives, and decide which is more important.  

If your students will need the support of blocks, you will be restricted in your choice of languages.  If your students are best served by applied computing projects, then Python might be the best option and you will have to pick the best environment to match.

Good beginner text-based languages (check out [transitional learning environments](https://github.com/blocks-to-text/transitional-learning-environments) for help choosing a programming environment):
* [Python](https://www.python.org/about/)
    * This is a great first language for students approaching programming with no mathematical or theoretical background
    * Syntax is easy to read and relatively intuitive
    * Most of best beginner programming environments and study tools are designed around Python
    * Students can immediately engage with interesting real-world data, algorithms, and applications via Python modules or API calls
* [Racket](https://racket-lang.org)
    * Ideal first language for students approaching programming from a mathematical or theoretical background
    * Scheme-like syntax and language design make transparent the connections between formal notation and code, helping to see how programming is really just automated mathematics
    * The language itself is programmable, students can explore programming by studying the Racket language itself
    * Allows creating applications, modeling, and data analysis
* [JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
    * As a programing language, JavaScript is not the easiest to learn
    * However, JS's interest for students as the programming language for the web and it's built-in UI (the DOM) can outweigh it's difficulties if taught well
    * There are self-contained learning environments to teach JavaScript like code.org, but consider using something like [Repl.it](https://repl.it) or [glitch](https://glitch.com) instead.  These environments may provide less support for students, but the ability to host their projects live online, remix other projects, and learning to work from a directory structure can outweigh the support from sites like code.org


Blocks-based languages/environment pairs that go beyond basic animations:
* [General Purpose Blocks (GP)](http://gpblocks.org)
    * Blocks for adults and the serious programmer
    * Can do everything Scratch can do
    * Can also accompany learners through systems modeling, data manipulation & analysis
    * Can access API's and cloud data
    * Build and deploy projects 
    * Connect to and program hardware
* [Snap](https://snap.berkeley.edu/snapsource/dev/snap.html)
    * Racket and other Scheme-like functional languages or extensions
    * Explore the connections between mathematics, computing theory & programming
    * Study programming languages by extending Racket
    * Build applications for modeling and analysis
    * Share and extend projects between students


[TOP](#prepare-to-teach)

---

## Pedagogical Content Knowledge



After choosing a language and environment, the next thing to do is some experimenting, observing and reading to figure out what will be most challenging for your students.  In teaching it's more important to know how you students will (mis)understand a concept than it is to know it perfectly yourself.  Being able to identify and correct their misconceptions is more valuable to their learning than you knowing concepts they won't encounter for several months.

What you can learn about your students' most-likely difficulties should shape your personal study.  Remember: you're not studying to become a developer, you're studying to teach the foundations of programming.

* [What is Pedagogical Content Knowledge?](https://github.com/webyrd/zoo/blob/master/interview-notes/ep6-mark-guzdial.org)
    * The knowledge about how to teach the specific domain. Phil Sadler came up with a way to measure pedagogical content knowledge: “First time, please answer the questions as correctly as you possibly can. Second time, please answer the questions in the way you think your students will get it wrong.” 
* [Know Thy Student](https://www.aft.org/ae/spring2016/sadler-and-sonnert)


[TOP](#prepare-to-teach)

---

## Practice Coding and Prepare Exercises

With a little bit of planning it's possible to study and prepare class materials at the same time.  Seeing as some of the most effective types of exercises ask students to work with pre-written code (parsons problems, code completion, finding single bugs, and modifying behavior of existing code), it doesn't take much more effort to create exercises than to write your own notes.  

By simply keeping a collection of the most helpful or challenging snippets you encounter in your own study, you can build up the raw material for the exercises you use in class. After studying go back through your collected snippets and make a series of practice exercises out of each one: create permalinks to [the parsonizer](https://blocks-to-text.github.io/parsonizer/), change variable names and constants then permalink to [Python Tutor](http://www.pythontutor.com/visualize.html#mode=edit), remove a line and replace it with a comment, introduce a single error.  Small changes that feel trivial to you can actually turn a familiar snippet into real challenge for students to understand.


Recommended study resources:
* [CS Principles: Big Ideas in Programming](https://runestone.academy/runestone/static/StudentCSP/index.html) - an outstanding course and reference for learning Python and how to use it.  Even if it is too much for your students to follow, it will not only teach you coding but how to teach it

[TOP](#prepare-to-teach)

---


## Use Integrative Projects


The final result of a program written outside of Scratch and similar environments simply isn't as interesting.  Instead of a fun movie or game programs will now be outputting numbers or text.  Some students may love the pure challenge and puzzle of programming, but that won't work for everyone.  On the other hand, after a while students will often get bored of Scratch in search of some way to 

As students transition from animation-based learning environments to "authentic" data-focused programming, it becomes more important to integrate programming into real-world cross-disciplinary projects.  How can programming be part of a history project? or how can students write use code to make something useful with the math they are learning?

Not only will this be more interesting for students, but it is also a more realistic exposure to how programming is used on a daily basis.  Treating programming as an isolated and "pure" skill set is not only an untruth but can scare away students who aren't strong programmers at the beginning or who are not interested in typing on a computer all day long. 

One practical steps you can take to build these projects and to support your students through integrating code across the curriculum is to provide (nearly) completed code for different stages of your projects.  Not only will this help them learn to program faster, but it will free more of their attention to think about what role the code plays in the larger project.  Also by providing examples of the code at different levels of completion students can explore incremental development and see first hand that even you their teacher writes programs in little steps.




* [Coding across disciplines](https://www.educationdive.com/news/contextualizing-coding-across-subjects-enhances-entire-curriculum/540258/)
* [5 ideas](https://www.kidsdiscover.com/teacherresources/5-ways-to-get-your-students-coding-across-the-curriculum/)

[TOP](#prepare-to-teach)

---

## Plan Off-Line Interactions

Real-world programming is a very social activity.  Add to that the benefits of social learning and it would be silly not to plan coding projects around peer-to-peer interactions. 

Some simple things to try include:
* Putting two students on one computer
* Attaching an extra monitor so more students can see what is happening
* Having only one computer per group and taking turns to code
* Make students present their code in groups - mistakes they made, how they fixed them, and what they would add next
* Break work time into on & off-computer chunks where students have to alternately plan and write code

[TOP](#prepare-to-teach)

---

## Coding is not about Code


Finally, remind your students and yourself that learning to program isn't really the goal. Programming requires a set of technical tools including code and computers, but those tools are the result of a much longer tradition logic and problem solving mentality.  

Prepare students to understand their world, to know they have a say in how it's shaped, and to think critically about how they interact with our digital world.  Learning to code will follow if it needs to.


* [Successfully learning to code follows from a successful mindset](https://slate.com/human-interest/2018/12/against-teaching-kids-to-code-creativity-problem-solving.html), not the other way around

[TOP](#prepare-to-teach)

---

## Resources

* [Teach Together](http://teachtogether.tech/en/)
* [Worst Practices](https://www.youtube.com/watch?v=ZpxxwZ9f_bo)
* [What (else) should CS educators know?](https://pdfs.semanticscholar.org/ed79/fed87136ff81129b31af57a167dff0b754dc.pdf)
* [teaching teens to code](https://medium.freecodecamp.org/how-to-teach-programming-to-teenagers-2ecd43846f0d)



[TOP](#prepare-to-teach)

___
___
### <a href="http://github.com/blocks-to-text/top" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Blocks to Text</a>
