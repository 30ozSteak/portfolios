# Victoria Vasys - M4 Portfolio

## Area of Emphasis
This inning, I hoped to learn the basics of a new language, JavaScript & implement the pillars of OOP that we learned for Ruby & Rails in a similar way with it. By graduation, I aimed to have passed all assessments & projects, build a capstone I was proud of & could share with people who would use it, reach out to 10+ company contacts, and have a couple interviews.

## Assessment

Include your final outcome (pass/fail) and a reflection based on answering the following questions:

* What was your biggest technical challenge?
* What did you like the most about the challenge?
* How did you solve that challenge? What was your approach?
* What did you learn?

## Quantified Self

* What was your biggest technical challenge? 
I think the biggest challenge for me in QS was firstly trying to navigate the DOM; I didn't realize until about 3/4 of the way through that WebDriver opens an iframe on your page, so when you are trying to debug in the console, it returns objects instead of the html you're looking for unless you manually open the iframe & the body inside it within the sources tab. I also found it really challenging trying to TDD with WebDriver as it would unpredictably not be able to find various css on my page even when I included wait.until.

* How did you solve that challenge? What was your approach?
It became much easier to identify that I was listening for the correct css after I realized the iframe problem. I'm still struggling to understand what makes WebDriver tick. But overall, I think I understand object-oriented JS much better and am able to fairly cleanly traverse & manipulate the DOM.

* What did you like the most about the challenge?
It was really exciting and satisfying to see immediate changes on the browser! It's pretty amazing how powerful javascript is & I'm excited to dig into other frameworks that use it. I'm really happy I got to see first-hand the various difficulties faced with the asynchronous capabilites of JS & I gained a pretty good understanding on how to control order (but could still use practice with that!)

* What are three technical concepts you learned during this project?
I learned what "asynchronous JS" is, why it's so powerful (allows tasks on the thread to continue to be processed while other tasks are being completed), and how to control it (mostly). I also learned how to be more object-oriented with JS by extracting modules into "classes", creating controllers to extract logic out of the "routes" file & naming anonymous functions to be able to pull them out from document.ready. Finally, I learned some more advanced DOM manipulation techniques like on blur & adding promises to a DOM query.

* If you could change one thing about your technical approach, what would it be and why?
I would have decided to move away from TDD on the front-end earlier and just built tests for maintenance instead because WebDriver was unpredictable and I spent too much time trying to make it give me consistent results; I could've used that time to refactor and make our app more object-oriented instead.

* What was the experience like working with a pair while learning something new?
It could be really difficult sometimes because we were continuously trying to incorporate new techniques we were learning, but it helped to pair when we wanted to incorporate something new & work on our own when we were approaching things we had some experience with in order to expedite feature completion.


## Capstone Project

Include a reflection answering the following questions:

* What was your biggest technical challenge?
* How did you solve that challenge? What was your approach?
* What did you like the most about the challenge?
* What are three technical concepts you learned during this project?

## Feedback

What's one piece of meaningful feedback you received during B4? What have you done or going to do regarding this feedback?

## Gear Up

Write a reflection about the process of planning/revising a Gear Up session and facilitating the session. Did you enjoy the experience? What was challenging? What was most rewarding?

## Community Involvement

How else did you give back to the community this inning? Why do you think this is a required part of the Turing experience?

## Going Forward

What three skills (professional and/or technical) are you going to take forward with you during your next job post-Turing?



<!-- # Victoria Vasys - M3 Portfolio

## Areas of Emphasis

> I didn't fully know what to expect this module, but wanted to strengthen my Rails skills and start to explore more advanced techniques & some front-end complexities.

## Self-Assessment

| Section | Category | Score (optional) |
| --- | ----- | --- |
| A | **End-of-Module Assessment** | 3.5 |
| B | **Individual Work & Projects** | 3 |
| C | **Group Projects** | 4 |
| D | **Professional Development** | 3.5 |
| E | **Feedback & Community Participation** | 4 |

>* This mod was incredibly challenging as the workload, range of topics, difficulty, and professional development requirements all ramped up greatly compared to Mod 2. I really enjoyed the learning and was very pleased that I got to focus on what I wanted to for my individual contribution to group projects, but at the same time, there wasn't enough opportunity to practice all of the really interesting & useful things we explored. It would be really beneficial if we could try to pull a few classes/practice pieces (eg. email, background workers, jquery) back to Mod 2 where things are fairly relaxed & multiple classes repeat.
>* I assessed myself at a 3 in for Individual Work & Projects because I didn't make it as far on APIcurious as I would have liked & should have spent more time & effort practicing SQL on my own. I assessed myself sub-4 for PD because although I spent quite a bit of time on most facets, I didn't spend enough time actually researching companies, reaching out to people for coffees, or generally networking. I'm going to try to put together an alumni-student get-together either over break or at the beginning of next mod.

-----------------------


## A: Individual Work & Projects

> **[APIcurious](http://backend.turing.io/module3/projects/apicurious)**
>* A Ruby on Rails project to practice working with data from public APIs; it attempts to emulate a simplified version of GitHub’s existing UI using its API. Uses the OAuth protocol to authenticate users through the third-party provider, and uses various testing techniques to allow testing against the third-party data.
>* This was a really great project to start getting my feet wet with consuming APIs; I didn't get as far as I would have liked but spent the majority of my time exploring new testing opportunities, which I'm thankful I did. It would have been helpful to have gotten a roadshow of best practices before the practice exam in which we were expected to speed through the process.


## B: Group Work & Projects

> **[Rales Engine](http://backend.turing.io/module3/projects/rails_engine)** 
>* Our first Turing School Mod 3 project: We demonstrate mastery of our Rails skills, built single-responsibility controllers to provide a well-designed and versioned API, developed controller tests to drive design, and implemented ActiveRecord methods & SQL queries to perform complicated business intelligence.
>* We compromised functionality for thorough TDD and paid for it during our eval. I was pretty proud of our accomplishments considering the timeframe and how ill I felt at the very beginning of the mod, but I will be revisiting it to develop better testing & to practice SQL & ActiveRecord.

> **[Cloney Island](http://backend.turing.io/module3/projects/cloney_island/cloney_island)**
The goals of these projects were to create secure, multi-tenancy web applications that have object-oriented & interesting seed files, allow users to upload files, consume external APIs, build internal APIs and use JavaScript to access internal APIs and update the page dynamically. The workflow should implement Agile processes & GitHub pull request templates, reviewing with comments & review approvals. The final projects should emulate the functionality and design of a major website.

> **[Cloney Island Sprint 1: Fairbnb](http://backend.turing.io/module3/projects/cloney_island/prompts/airbnb)** 
>* For Fairbnb, we spent a lot of time planning & wire-framing, built complex search queries, reservation capabilities & internal APIs, consumed external APIs, developed live-messaging through websockets, and finely-tuned the front-end to have a professional and aesthetic UI.
>* This was a gruelling, yet thrilling adventure with a stellar team of all females. I dug into websockets and Action Cable, which were totally new to me & it was really satisfying to get that to function. I also had a really good time putting on the finishing touches to our styling.

> **[Cloney Island Sprint 2: Grab Bag (Dropbox)](http://backend.turing.io/module3/projects/cloney_island/prompts/dropbox)** 
>* This sprint, we dug into "brownfield" code from the previous sprint project Grab Bag, which emulates Dropbox. This project emphasized downloading and uploading of files through the Rails server and Amazon's S3 Bucket service. It implements complex routes that nest folders and files within other folders and files, both globally & privately. We built on it by adding the capability to download folders, adding breadcrumbs for navigating up folder trees, limiting likes to current users & one like per user, drawing from the actual Dropbox API, giving users the ability to move their files to our app, adding background workers to cache data analytics via Redis, and using AJAX to consume our own internal APIs to display animated charts via a D3 wrapper, Dimple.js on an Admin Dashboard.
>* It was incredibly challenging diving into such complex foreign code, especially since the only group member who stayed was sick during the beginning of the sprint. But it was a great learning opportunity to work in brownfield code and I really enjoyed exploring various javascript charting tools and trying to display them in an organized and dynamic way.

| CATEGORY | Rales Engine (scores optional) | Cloney Island 1 (scores optional) | Cloney Island 2 (scores optional) |
| --- | --- | --- | --- |
| **Github Repo** | [Rales Repo](https://github.com/VictoriaVasys/rales_engine) | [Cloney 1 Repo](https://github.com/VictoriaVasys/fair_bnb) | [Cloney 2 Repo](https://github.com/stovermc/grab_bag) |
| **Heroku** | N/A | [Fairbnb](https://fair-bnb.herokuapp.com) | [Grab Bag](https://grabbag.herokuapp.com) |
| **Functional/Client Expectations** | 3 | 4 | 4 |
| **TDD** | 2.5 | 3 | 4 |
| **Code Organization/Quality** | 3.5 | 3 | 4 |
| **API Design** | 4 | N/A | N/A |
| **Queries** | 4 | N/A | N/A |
| **UIX** | N/A | N/A | 3+ |
| **Git Workflow** | N/A | N/A | 3+ |

> Rales Engine evaluation comments:
* Testing is sub-par and wouldn't be acceptable on the job
* General code quality is solid
* SQL queries are functional and complete

> Cloney Island Sprint 1 evaluation comments:
* Messages in chat persist!!!!
* There could be more testing on the models (validations and methods) so keep that in mind!
* There is a little bit of logic in the view that could be pulled into the controller (conversations index). Really nice job, overall!

> Cloney Island Sprint 2 evaluation comments:
* Overall, exceeded expectations & everyone challenged themselves and took risks
* Many tests incorporated complex techniques; haven't checked coverage yet
* The UIX is good but sub-4 because it's not quite professional-design-level
* Waffle was pretty well-maintained & team members made a solid effort to fill out the PR template and make comments & reviews on others' PRs
* There were some nice code refactors & using a decorator is a plus!


## C: Gear Ups

>* [Microagressions](https://github.com/turingschool/gear-up/blob/master/microaggressions_original.markdown)
The microagressions conversation was highly interesting and important. I was very thankful Sal & Ilana were our leaders because they encouraged open & respectful conversation and inspired us to face some harsh realities. As we spoke about our personal experiences, I came to realize that my response to microagressions is completely variant based on my current mood and tolerance. Sometimes I am quick to make others aware of their misstep and stand up for myself, and other times I am either down-trodden, low-energy or wary of saying something considering the consequences (fear of violent retaliation or tender work environments). It was really fascinating and somewhat comforting hearing from others in my class and very useful exploring articles and realistic instances of microagressions.

>* [Tragedy of the Commons](https://github.com/turingschool/gear-up/blob/master/tragedy_of_the_commons.markdown)
This gear-up was definitely unique in that we had an interesting & interactive web app to follow along with. I didn't realize how much individual inactions, let alone shortcomings, affect society as a whole. The dynamic charts were especially revealing as small increases in tolerance made a slight difference, whereas small demands for equality (anti-biases) made huge changes over time. As a group, we had really interesting discussions around diversity quotas as they are clearly anti-biases and make a difference, but sometimes they are a band-aid on a bigger problem and workplace inclusion & support is equally as important. We also discussed how intent can be far removed from impact, especially when desiring to be around/work with like-minded people, and that we need to keep in mind our viewpoints; oftentimes small conflicts and arguments seem larger than they are, but if we remember the scope of the issue, we can identify with each other on a higher level. Overall, we need to keep in mind that our identity is fluid, we should strive to be introspective and consider all the different places we've been and opinions we've had, be open to difficult conversations, and be active in demanding diversity & inclusion. 

>* [Universal (Unconditional) Basic Income (UBI)](https://github.com/turingschool/gear-up/blob/master/universal_basic_income.markdown)
I really loved the way the Mod 4 students ran this gear-up; they made clear that they weren't trying to convince anyone of anything, but to help us formulate an opinion by providing some information and a forum for discussion. They led off with a TED talk, created a temperature gauge for our before-during-and-after opinions on whether UBI should be implemented, and moderated small-and-large group discussions, encouraging us to write our biggest conclusions on the whiteboard so everyone could easily document the gear-up. I learned a lot from the video & discussions, especially some realistic cons (opportunity for exploitation, the potential to devalue currency, possible exacerbation of the problem when not implemented unconditionally), which aren't often addressed, and that entire countries are currently implementing UBI. There's a lot of things to consider when attempting to create the system, but in my opinion, nothing would make a bigger difference on the state of our society; not only would there be an increased standard of living, where everyone would be guaranteed food & shelter (things we decided as a planet were essential to human rights (Article 25 of the UN's Universal Declaration of Human Rights); imho it is deplorable that not everyone can eat every day or have a roof over their head... and that the richest 8 people have the same wealth as the poorest 3.6 billion-- half of the world's population), but also history has shown time & again that when people's basic needs covered are covered, they have time & energy for productive & creative shit!


## D: Community Participation

#### **Community Contribution Option**
  >* [Portfolio Template](https://github.com/turingschool/portfolios/blob/master/BEM3_template.md) - I developed this open-source template for my fellow students to easily construct their portfolios from. 
  >* [Turing Podcast](http://turingschool.libsyn.com/) - I have produced & hosted or co-hosted a total of 7 episodes so far; 4 this mod & 3 last mod. I have explored the experiences of students from both the front-end & back-end programs of each mod and discussed the job hunt process, ins-and-outs of technical interviews, what it means to be a mentee and mentor, and how to progress and excel as a junior developer with various Turing grads. I plan to record an episode or two over break and aim to hone-in on more specific topics & groups of people (veterans, moms, lgbtq, block-chain, React, Elixir/Phoenix; would love ideas on this!)

#### **Armstrong Posse**
  >* I helped coordinate people into research teams using a trello board & contributed to discussion about the goals & future of the posse; I helped dig in to some code from former students who used Solidity and the test block chain in a final project. I will be co-leading the posse next mod.
  >* It was really neat participating in a variety of events with Armstrong; we watched TED talks, had group discussions on the potentials and pitfalls of the block chain, students led lightning talks & tutorial walk-throughs to learn more about the intricacies of using Solidity and Ethereum, a former student outlined how his team's Rails-React-Solidity project worked and let us explore it in-depth, and the posse is connecting with real programmers & meetups that focus on block-chain technologies (we'll be assisting with a future block-chain hack-a-thon led by the Ethereum meetup)
  >* It's been an invaluable experience working with people across mods and connecting with people outside of Turing through Armstrong. The channel is very active, and we set out to coordinate a happy hour & be involved in a meetup organization. I'm very excited to see where next mod leads!

#### **Playing a Part**

  >* I've attended multiple imposter lunches & try to help support struggling students whenever possible. I volunteered to be project manager for our Fairbnb sprint & spent a lot of time keeping us organized & on-track. I have contributed to multiple potlucks to encourage & bolster cohort cohesion and health. I've participated in the after-class work-outs & running and encourage others to get up off their tush! :) I also spent a day tweeting for Turing, documenting student life and various interesting Friday-goings-on.

------------------

## Final Review

> #### Notes ( Leave blank for reviewers )

> #### Outcome ( Leave blank for reviewers ) -->