# Jared Roth - M1 Portfolio

## Individual

### Areas of Emphasis

Coming into this first module, my primary goal (besides just *passing* the module) was to feel comfortable coding. This means a few different things to me:

1. I am new to using Macs and re-learning an entirely different set of shortcuts was critical for me.
2. I have never used the terminal before in my life, so learning basic commands and becoming comfortable there were critical.
3. Also new: Ruby. Besides one of the basic goals of the module, I wanted to be comfortable with it, not just passing.
4. Lastly, besides these technical goals, I came in desiring to learn, develop, and practice my ability to break down problems outside of code and to think algorithmically.

### Mid-Module Assessment

Assessed By: Andrew

#### Notes:

* Developer did not TDD. Wrote tests retroactively
* Could tell developer is comfortable with figuring things out, but did not aproach things efficiently.
* Overall I think this developer is in a good place and is comfortable/able to code, but needs to use a little more discipline and TDD the whole way.
* Also needs to work a little on how to use best use variables​

## Evaluation

Subjective evaluation will be made on your work/process according to the following criteria:
​
##### 1. Ruby Syntax & API
* 3: Developer is able to comfortably implement solutions in Ruby

##### 2. Ruby Style
* 2: Developer writes code that has unnecessary variables, operations, or steps which do not increase clarity

##### 3. Blocks & Enumerations​
* 3: Developer demonstrates understanding of blocks and can effectively use enumerable methods

##### 4. Testing
* 1: Developer does not integrate testing throughout their development process

##### 5. Workflow
* 4: Developer is a master of their tools, efficiently moving between phases of development

##### 6. Collaboration
* 4: Developer *actively seeks* collaboration both before implementing, while in motion, and when stuck

### End of Module Assessment

Assessed By: Horace

Challenge: Unit Conversion Challenge

#### Notes:

* Quite strong; doing well at digesting the problem quickly and translating into code
* TDD workflow is smooth and effective
* Able to pick up on next steps and translate those into test cases / assertions
* Objects, methods, instance variables, lifecycle stuff seems comfortable
* Workflow is solid; especially appreciate ability to stay in editor while running tests etc.

##### 1. Ruby Syntax & API
* 4: Developer is able to write Ruby with a minimum of reference or debugging

##### 2. Completion and Progress
* 3: Developer completes baseline assignment and makes meaningful progress toward one of the Challenge options.

##### 3. Testing
* 3: Developer writes tests that are effective validation of functionality, but don't drive the design

##### 4. Workflow
* 3: Developer demonstrates comfort with their tools and makes some use of keyboard shortcuts

##### 5. Collaboration
* 3: Developer lays out their thinking before attacking a problem and integrates feedback through the process

##### 6. Enumerable & Collections
* 4: Application consistently makes use of the best-choice Enumerable methods

### Attendance
Missed one Protocol session to go check on my wife who had just cut herself.

### Projects
The following projects were completed on my own.

#### Jungle Beats (Linked List)

* [GitHub URL](http://github.com/JaredRoth/jungle-beats.git)
* [Original Assignment](http://github.com/turingschool/curriculum/blob/master/source/projects/jungle_beat.markdown)

The Jungle Beats project is an implementation of a linked list in Ruby that adds the essential feature of playing a string of sounds via the 'say' command in terminal.

Reviewed by Mike

__Comments:__
* 11 tests
* One small side case where you cant append to an empty list
* Needs node tests
* good traverse method
* Good use of blocks
* would like to have seen JB and LL split into separate classes

__Scores:__
* Functional Expectations: 3
* Test-Driven Development: 3
* Encapsulation / Breaking Logic into Components: 3
* Fundamental Ruby & Style: 4
* Looping *or* Recursion: 4

#### Enigma
* [GitHub URL](http://github.com/JaredRoth/enigma.git)
* [Original Assignment](http://github.com/turingschool/curriculum/blob/master/source/projects/enigma.markdown)

Enigma takes various combinations of strings, keys, and dates and either encrypts, decrypts, or cracks the string.

Reviewed by Mike

__Comments:__

* 16 runs, 29 assertions
* It encrypts
* it decrypts
* it does not blend
* test should be in separate files, in a test directory
* cracked does not work, small error due to an unclearness in spec
* Some opportunities to refactor out to additional classes and methods.
* Overall, well written code, good project, next time would like to focus on more division into classes.

__Scores:__

* Overall Functionality: 3
* Fundamental Ruby & Style: 3
* Test-Driven Development: 3
* Breaking Logic into Components: 3

## Team

### Posse Challenges

* [Codebreakers](http://github.com/rossedfort/posse_challenges/tree/master/code_breakers)
 * This was my first experience working with a team as well as my first foray into ruby. I learned a lot from my more experienced posse members and was actually able to contribute despite not knowing much of anything.
* [College Scorecard](http://github.com/rossedfort/posse_challenges/tree/master/college_scorecard)
* [Enumerables](http://github.com/rossedfort/posse_challenges/tree/master/enumerables)
* [People Database](http://github.com/rossedfort/posse_challenges/tree/master/people_database)

### Projects

The following projects were completed with a partner.

#### Hyde

* [GitHub URL](http://github.com/JaredRoth/hyde.git)
* [Original Assignment](http://github.com/turingschool/curriculum/blob/master/source/projects/hyde/index.markdown)

Enigma takes various combinations of strings, keys, and dates and either encrypts, decrypts, or cracks the string.

Reviewed by Andrew

__Comments:__

* Had conversations about refactoring and opportunities to make code cleaner and generally more readable.
* A small bug with going to the root, but nothing to concerning.
* Able to talk about all the code and it was knowledgable
* Didn't use many enumerables but there were not many opportunities.
* Testing was good. Could have have some more edge cases particularly in taking in the args

__Scores:__

* Functional Expectations: 3
* Test-Driven Development: 3
* Encapsulation / Breaking Logic into Components: 3.5
* Fundamental Ruby & Style: 3
* Enumerable & Collections: 3
* Code Sanitation: 4

#### Headcount

* [GitHub URL](http://github.com/jaredroth/headcount)
* [Original Assignment](http://github.com/turingschool/curriculum/blob/master/source/projects/headcount.markdown)

Headcount processes, manipulates, and evaluates certain data for all of the school districts in Colorado. This project involved heavy usage of hashes and CSVs and combining their use appropriately.

Assessed By: Horace


__Comments:__

* Passes spec harness through i5 -- solid 3 on completion
* Overall succesful in managing data flow and processing through the repos
* In general strong style around how we're handling things; only a few quibbles around naming, method division, etc
* Looked at some interesting ideas around how we might pull out handlers for different processes in a more declarative way
* enums, etc are pretty string; using some group by especially; maybe think about reduce instead of each with object
* Where this starts to break down is in the Analyst -- you have the right pieces and some good techniques, but they could benefit from more organizaiton,
especially from the perspective of carving out smaller helper classes to do some of the lower responsibilities
* test coverage and breadth are both great; still would like to see more usage of more curated / specific data and attacking the tests
at lower levels

__Scores:__

* Functional Expectations: 3
* Test-Driven Development: 3
* Encapsulation / Breaking Logic into Components: 3
* Fundamental Ruby & Style: 3
* Enumerable & Collections: 4
* Code Sanitation: 4

### Select Pull Requests and Readme
* [Headcount](http://github.com/JaredRoth/headcount/pull/26)
* [Headcount](http://github.com/JaredRoth/headcount/pull/21)
* [Hyde](http://github.com/JaredRoth/hyde/pull/25)
* [Codebreakers Posse Challenge](http://github.com/rossedfort/posse_challenges/pull/1)

* [Hyde Readme](http://github.com/JaredRoth/hyde/blob/master/README.markdown)

## Community

### DTR Memo

__Project: Hyde__

Jeneve Parrish, Jared Roth

__Key points:__

* Desired Growth
 * Jeneve: looking to gain experience with Ruby syntax and general workflow improvements
 * Jared: looking to improve / establish Git workflow (ideally discovering best-practices)
* Areas of strength
 * Jeneve: Understanding a problem (independent from code)
 * Jared: Workflow: Keyboard shortcuts. Avoiding the mouse. Etc.
* Restrictions
 * Jeneve: has a child and therefor frequently is unable to work into the evening
 * Jared: none at all at this point. Willing to work where/when-ever Jeneve is available.
* Concerns
 * Jeneve: Struggling up until now. Concered by the potential of getting left behind, either mechanically or conceptually
 * Jared: Concerned with his ability to work with others. Especially in the case where he may be required to slow down.
 * Because of both of the above points (individually and taken together), agree to open feedback and the mutual efforts to ensure that we are both on the same page at all times and commit to making an effort that both parties feel equally involved throughout the project.
* Additional notes
 * Agree to work primarily together because: we don't know how to divide projects at this point, and: this project seems pretty linear to us at our current level of understanding

### Giving Feedback

* Jeneve Parrish
>When Jeneve and I paired for the Hyde project, she admitted that she was struggling at Turing. That honesty carried through the rest of our DTR as she was able to both clearly express her desires and current situation, while listening to and demonstrating understanding of mine. Despite her self-claimed struggles, Jeneve quickly demonstrated her ability to comprehend and break down problems algorithmically. As she would tell you herself, her biggest struggle coming into the project was workflow / computer navigation.Although I have observed her getting stronger in this area through intentional effort in each project, I believe this is the one area that will most benefit her when improved.

* Mark Miranda:
>Mark is great at keeping the overall objective in mind and ensuring that whatever we're working on is furthering that goal. While I was getting held up on how to best implement one relatively small aspect of the exercise, he was reminding me of what the time was trying to accomplish.

* Gurusundesh Khalsa:
>While paired with Sunny toady, he was working on refining/revising his most recently evaluated project. He was great at accepting (potentially critical) input regarding some of his choices. He was also great at explaining the problem he was stuck on from the ground up so that I was able to give beneficial feedback from a place of understanding.

* Kriss Foss:
>Kris and I paired during the refactoring exercise. She was great at recognizing duplications which helped in significantly reducing class and method sizes. At times, it seemed as though she was a little hesitant to voice her opinion if I was going in a different direction. Her ideas were great and it would be an improvement if she was comfortable voicing her thoughts on projects.

### Being a Community Member

* Jeneve Parrish:
>Jared and I teamed up to build 'Hyde', a lightweight application for blogging. Both our partnership and our project were a success. Jared is very detail-oriented with a keen eye for making code attractive, readable and orderly; I learned a lot about refactoring from him. He was always very positive and collected even when we faced setbacks. Jared is patient and kind, he thinks fast and is always helping others.

* Gurusundesh Khalsa:
>Jared worked with me on my quick refactor of sorting suite. He had a surprisingly good grasp of my code after only a few minutes and was able to contribute to the process.
I think Jared is well on his way to becoming a better coder.  If he continues to work on understanding the ruby object model, he will get there fast!

* Kriss Foss:
>Jared and I paired during a refactoring exercise and I have worked with him in group projects.  He's extremely good at breaking down problems into logical components and he's very comfortable with Ruby syntax.  He was able to explain binary numbers in a way that made sense to me even though I had never worked with them before.  Jared would be a very strong partner for a project and I'd be eager to work with him again.  I don't have any suggestions on how he could improve, our session was really brief.  But I have no doubts that he will be a great programmer and a tremendous hire for any company.

### Playing a Part

[Blog Post (currently just a gist)](https://gist.github.com/JaredRoth/cb7fcad2cadb2a1f9a60)

Although I never established or ran any formal events, I spent much of the module pairing and helping others work through their projects in an unofficial capacity.

During Jungle Beats in particular I spent a good amount of my time helping a number of students understand some of the key linked-list concepts they were struggling with. Notably: Ji Kim (who decided to re-take the module due to these and other struggles), Jeneve Parrish and Claudia Kiesenhofer.


# Portfolio Rubric

Your portfolio will be evaluated using the following rubric. Earning at least
a three in each category is the baseline for promotion/graduation.

## A: End-of-Module Assessment

A Turing student is able to demonstrate proficiency at programming in accordance
with the module's content and expectations.

* 3: Student achieved a "3" or better on each category of the assessment || excused from assessment


## B: Individual Work & Projects

A Turing student works to maximize their skill growth and demonstrates
that skill across a variety of work.

* 3: Student demonstrates commitment and growth in their work through satisfactory
evaluations of each project or a clearly upward-sloping trend.

## C: Group Work & Projects

A Turing student contributes significantly to group projects, helps the team
develop their technical skills, and delivers a high-quality product.


* 3: Student fully participates in their group work to facilitate group harmony
while achieving consistently satisfactory results.

## D: Community Participation

A Turing student builds up the community around them by participating and
supporting other students, the larger Turing family, and persons outside our
walls who want to develop their own skills.


* 3: Student participates in required activities and does at least one or two
above-and-beyond supports of the community.

## E: Peer & Instructor Feedback

A Turing student accelerates the growth of those around
them by delivering specific, kind, and actionable feedback. They accelerate their
own growth by taking in and acting on the feedback of their peers and instructors.


* 3: Student consistently delivers meaningful feedback for peers and implements
strategies to improve themselves in response to feedback.


OUTCOME: PROMOTED
