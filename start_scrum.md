#Getting Started with Scrum 1.0

##Table of Contents
* Introduction
* What is Scrum?
* User Stories
* Roles
* Sizing and Estimation
* Artifact
* Process

##Introduction
With the ever changing requirements in today's software development industry, software providers must adapt and respond. Gone are the days of rigid process. Defining everything, down to the essential details even before the development process begins, is a thing of past. Nowadays we must focus on feedback and communication.

Agile is a development process focused on responding to changes, tight feedback loop, open communication, and being receptive of stakeholder feedback. In the real world, requirements constantly change; what you conceptualized several months ago might not exactly reflect your requirements now.

Scrum is an Agile framework with a focus on management structure rather than engineering. It gives you significant leeway to apply it in conjunction with several engineering practices like pair programming, Test Drive Development, Automated Testing, etc., as it doesn't explicitly require a specific engineering approach.

##What is Scrum?
Scrum is an iterative and incremental approach in product, project and/or product development. These iterations are called **sprints**, usually done between 1 - 4 weeks time. At the start of the sprint the **scrum team** selects from the list of requirements from a prioritized list. Each item is accompanied by the story the selected items are expected to be delivered by the end of the sprint. Every end of the sprint the team should, at the very least, deliver the potentially shippable or a working increment of the product.

However, it is encouraged that you tweak scrum to better fit your scenario. Since it is a management practice you are not bound by industry specific restrictions. As a matter of fact, Scrum is practiced outside the software development industry.

##User Story
User story is the form where requirements are written in Scrum. They are written from the perspective of the user of that feature.

**Example:**
````
As a user, I want to be able to register into the site using my email address
````

Each user story is accompanied with a size (estimate) indicating the effort required to accomplish it.

##Sizing and Estimation
User stories need have a indicator with them to determine (guess) the effort required to accomplish them. Estimates need not to be accurate, but it has to be consistent all throughout the project.

You can just write stories and provide the size later; this helps us in avoiding arbitrarily sizing stories that we do not understand quite well yet.

The canon sizing method is with planning poker cards. However, there is no strict rule prohibiting you from adopting a different sizing method. Often times, teams devise their own sizing strategy. What is important is you have a great knowledge and understanding of Scrum to effectively modify it without losing its core principles.

###Methods

####Five Fingers
```1, 2, 3, 4, 5 ```


####Powers of 2
```1, 2, 4, 8, 16 ```

####Fibonacci Sequence
```1, 2, 3, 5, 8```

####Shirt Sizes
```S, M, L, XL```

##Artifacts

###Product Backlog
The master list of all project/product requirements, managed by the Product Owner. The product owner is also responsible in prioritizing the items. High priority items should be placed on top.

###Sprint Backlog
List of items to completed in a sprint. The items placed in this list is taken from the ***Product Backlog***.

###Burndown Chart
Graph of the user story points completed by the team. This is a negative graph where the points accomplished are deducted to the total points in the sprint. The aim is to show ***0 (zero)*** points remaining at the end or before the end of the sprint.
##Roles

###Scrum Team
The scrum team consists of members of varying capabilities. From an app development perspective it is composed of developers, designers, testers, etc. The recommended size of a scrum team is 7+/-2. However, in large and complex projects what is usually done is you have **scrum of scrums** wherein you have a large team subdivided to smaller teams, each tasked in delivering a certain component of the project.

###Product Owner
Product Owner represents the external stakeholders for the project. He/She acts as the point-of-contact of stakeholders (users, managers, executive team, etc) to relay their feedback to the development team. This is done to limit the noise in conversation and have a directly responsible individual in mapping out deliverables, timelines, and expectations regarding the project. He/She is ultimately responsible on what goes into the **product backlog**.

###Scrum Master
The primary function of the Scrum Master is to facilitate the Scrum process and ensure it is religiously followed. Guiding the team, product owner, and upper management in navigating their way into Scrum  is an essential part in the role of being the Scrum Master. Contrary to popular notion, Scrum Master is not responsible for the project deliverables. His/Her responsibility primarily lies on ensuring that the process is followed along with transparency and tight feedback loop.

##Process
Scrum revolves around sprints. An entire development process is encapsulated in a sprint, with each sprint having a defined deliverable. The premise of scrum is to provide a consistent and predictable stream of output.

###Sprint Planing Meeting
Before the start of each sprint, the scrum team together with the product owner and scrum master discuss priority tasks, goal of the sprint, and deliverables expected by the stakeholders. This meeting revolves around the Product Owner talking about the priorities and expected deliverable. Defining the sprint deliverable is a collegiate process. Setting a realistic expectation is key, based heavily on the track record and skill level of the team. At the end of the meeting there should be sprint backlog for the team to follow.

###Sprint
This is the actual development process where the product is done, tested, and sent for acceptance. The key in doing sprints is to set a consistent, predictable, and sustainable pace for your development. We do not want to burn out our team by having too many tasks for that specific sprint.

###Daily Scrum
In the duration of the sprint, every day the entire team meets for 15-minutes. During the 15-minute meeting each and everyone answers three questions. Those questions are:

1. What did I do yesterday?
2. What will I do today?
3. Is/Are there anything that impedes me from accomplishing my task(s)?

The goal of the Daily Scrum is to inform the entire team of each members' tasks and current status. Discussion on issues is not encouraged during Daily Scrum. A separate meeting composed only of those involved should be set.

###Sprint Review Meeting
At the end of the sprint we will review the deliverable. This is best done through a demo wherein the scrum team would present what was accomplished.

In this meeting, stakeholders (management, users, etc) can be invited but they can only watch. If they have comments and/or feedback, it is best coursed through the Product Owner so he/she can consolidate them and present them to the team in a structured form.

The goal of the Sprint Review Meeting is to provide a first hand insight on what was accomplished and also to learn the perspective of the time on how they see the product taking shape. This can also be considered a Release meeting wherein all of those involved in the project are present to see each iteration of the product/project.

###Sprint Retrospective Meeting
While the Sprint Review Meeting focuses on the ***what*** (deliverable), the Sprint Retrospective Meeting focuses on the ***how*** (process). The goal of this meeting is to improve productivity of the team and make them work together more seamlessly.

During the retrospective meeting, each member of the team would answer these questions:

1. What works?
2. What does not work?
3. What we should start doing?

How to improve estimates and maximizing work during sprints should also be tackled in this meeting.

##References
- Deemer, P., Benefield, G., Larman, C., Vodde, B., (2012) THE SCRUM PRIMER: A Lightweight Guide to the Theory and Practice of Scrum Version 2.0.
*http://www.scrumprimer.org/scrumprimer20.pdf*
- Scrum: Tools and Techniques for Estimating Tasks in a Scrum Projects (November 21, 2014) Retrieved from
*http://scrum-study.blogspot.com/2014/11/scrum-tools-and-techniques-for.html*
