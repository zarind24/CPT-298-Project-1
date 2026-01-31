# Project Proposal

## 1. Project Identification
- **Project Title: Discord Bot for students to ping for cpt_program data
- **Course: CPT-298
- **Term: Spring 2026
- **Student Name(s): Zarin Deane, Hayden Allen
- **Primary Contact: Zarin Deane
- **Proposed Start Date: 2-2-2026
- **Proposed End Date: 3-8-2026

---

## 2. Project Selection & Motivation
Describe why you selected this project and why you are a good fit.

Include:
- Personal or professional motivation
- Alignment with career goals
- Relevant interests or prior exposure

We selected this project because we feel like we would have an easy time completing this project and fulfilling the expected results. We both use discord and understand its layout and workarounds. We also both understand Python which will be the code we plan to use to complete this project. We both enjoy coding and use discord bots in our own servers. We both plan to be a coder of some kind, coding various things for different companies. We have both been interested in discord bots and have even looked into the coding side of how they work. 

--- 

## 3. Problem Statement
Clearly describe the problem, need, or opportunity this project addresses.

Answer:
- What problem exists?
- Who is affected?
- Why does this problem matter?

Limit to 1–2 focused paragraphs.

The problem that exists is there is no way for CPT students, taking a class with Brett Bisesti, to figure out information that would be very useful and time saving. For starters, CPT students want to be able to see how well their participation score is in the Discord. Their participation score is a direct reflection of how well their participation grade is. Students also want to be able to easily have access to their information they have put in for different programs. This could include their username to the Virtual Machine. If a student were to for some reason forget their CPT username, or if the set up is to request it to find out their username in the start of the semester, the bot will be able to answer that for you with a command. !username will prompt the student their username. 

These two problems alone matter because students want to have an easily accessible and much faster response to common issues. If they have to wait for the professor or someone else to help them that could take much longer than an automatic response from a bot.   

---

## 4. Proposed Solution Overview
Provide a high-level description of your proposed solution.

Include:
- What you intend to build, deploy, or configure
- Core features or capabilities
- Explicit exclusions (what the project will *not* include)

We plan to build a discord bot that answers a lot of the basic questions students have. Anything from requesting username to requesting discord participation status. This bot is intended to help save time on the student and professor, answering basic questions that don't need to take hours to get answered. We plan to add a !username command that will prompt the students username that only the student who prompted it can see. Then we have a !status command that shows how good their participation is with a meter and a !rank command to show their rank compared to others in the class. Then we will have a !classes command that shows what classes you are taking that semester to the discord to help show others what classes you are in. This could spark conversations with others and make it easy to find help if they are in the same classes. Another command we will implement is the office hours of the professor, 

---- Brett Note ------

!office hours aswell as !classtimes so students can easily figure out when they can schedule a meeting with the professor and when his class times are. 

Note: This may be challenging to do - I would want to tie this in automatically with my O365 calendar and getting school approval for the API keys required is not likely to happen.  Having an easy way to get at the bookings link to schedule office hours (which has my updated meeting and class schedule!) would probably be a lot easier!



The !classtimes command will also be useful if students forget what time their class starts. This bot will however, not include a way to schedule these meetings. The bot will also not include information about classes such as: grades, due dates, and what the description of the class is. This bot will also not include a !password command to ensure their account can stay secure. 

Note: Same as the above here - linking this to Anthology would likely be a non-starter.  That said I think the items you mentioned above that are 100% within the purview of my classes (and technical control) are an EXCELLENT idea and exactly what I was thinking about for this project!

---- End Brett Note ------

---

## 5. Technical Stack & Tools
List the technologies you expect to use.  Please note that this solution MUST live within the cpt.internal network and must be maintainable by future students.

- **Operating System(s): we expect to use Linux but this will work on windows machines as well.
- **Programming Language(s): Python
- **Frameworks / Libraries: discord.py, python-dotenv, pillow, colorama, emoji
- **Databases / Storage: sqlite3
- **Infrastructure (VMs, containers, etc.): schools server and VM
- **Tools (Git, CI, monitoring, APIs, etc.): GIT, GitHub

---- Brett Note ------

Note: If you could "dockerize" this application that would be awesome!  You'd need to research:

- Dockerfile
- Docker Compose

for creating a docker image than running it.  It's an extra step but would make it super portable!  Entirely optional but worth learning about and utlilizing!

---- End Brett Note ------

---

## 6. Prerequisite Knowledge & Skills
Assess your readiness for this project.

Include:
- Skills you already have
- Skills you need to learn
- Relevant coursework completed
- Prior projects or experience

Be honest—this section helps scope the project appropriately.

We have a decent understanding of python and the willingness to do research on what we don't know. We may need to learn some extra python language in order to complete the assignment. We have completed intro to python at CMCC and have taken other coding languages so we are pretty familiar with code all together. We have set up a whole website in intro to web development which shows our ability to create something from scratch. We have both done research into discord bots and how they kind of operate.

---

## 7. Project Scope & Deliverables
Define what success looks like.

Include:
- Minimum viable deliverable (MVP)
- Required outputs (application, scripts, documentation, etc.)
- Optional stretch goals (if time permits)

The absolute minimum would be a bot that gets the job done and doesn't have super fancy additives to it such as: fancy pictures, extra colors, and anything above and beyond the necessary base output. We plan to have easy to read/edit code that future students can read/edit to make changes or understand how the bot works. We also plan to set up a bot that not only gets the job done, but has a bit of flair to it so it looks nice and students actually want to interact with it. Our stretch goal would be to come back to the bot near the end of the semester and make changes after it has been used for a couple weeks, and has received input from others. 

---- Brett Note ------

Excellent!  Definitely make sure you have a "readme.md" file in this project which outlines some high level concepts of what your bot is, how it functions, and gives a starter for others who may want to modify it.  I'd also recommend renaming your project to something (for lack of better words) "cooler/sexier/what-have-you"  Really sell it!  This way we can have this project live on in perpetuity through additional feature requests like you mentino above and you'll have a public repository which shows your GitHub users contributing to open projects!

---- End Brett Note ------

---


## 8. Milestones & Timeline
Provide a rough timeline broken into phases.

Example:
- Phase 1: Research & Design
- Phase 2: Core Implementation
- Phase 3: Testing & Refinement
- Phase 4: Documentation & Presentation

Dates do not need to be exact, but planning is required.

Week 1: Research and set up/agree on the look and operation
Week 2: Start coding with place holder information
Week 3: Finish code and start testing
Week 4: Finish testing and presentation

---

## 9. Risks, Constraints & Dependencies
Identify potential challenges.

Include:
- Technical risks
- Time constraints
- External dependencies (APIs, credentials, access)
- Mitigation strategies

Discord could potentially get overwhelmed with too many messages to the bot causing the bot to crash. User data could get leaked if someone had malicious intent. The bot could accidentally leak someone's information such as their password if something goes wrong with the privacy feature. 4 weeks to get extra knowledge, complete the bot, and make sure it works properly is a short window considering we have other classes. The bot would rely solely on discord and if the school were to deny discord access that could scrap the whole project. A mitigation strategy we have is to not include a way for students to ask the bot for a password to their account. This will help reduce the risk of leaking personal information that could harm them and the school. 

---- Brett Note ------

Discord access is no problem, and I can get you a read-only service account to the cpt_program database as well as the appropritae views/tables when you're ready for it!  Can also provide you with alternative tables/views if you need them.  Like I mentioned O365 and Anthology access is likely not going to happen but the BULK of your features we should be able to complete without them!  My recommendation would be to scrap those features and just focus on the "core" which is username access and participation checking!  

---- End Brett Note ------

---

## 10. Security, Ethics & Safety Considerations
Address any relevant concerns, such as:
- Authentication and authorization
- Data sensitivity
- Network exposure
- Logging, monitoring, or automation impact
- Ethical considerations

A brief assessment of all of these is required, even if it is "N/A".

The bot will only show the user their username and discord participation meter but will show every a leaderboard with the !rank command. This will ensure that everyone doesn't know personal info and that others can't guess grades of other students. They can see a leaderboard but the person on the bottom doesn't mean they have a bad grade. The bot will only store non sensitive data to ensure there isn't a major security risk. The bot communicates only with the Discord API over secure HTTPS connections. No external APIs or services are contacted, reducing the risk of data leaks. Bot permissions are limited to only what is necessary for commands. Logging is limited to basic bot activity and errors for debugging. The bot follows a privacy-first approach, minimizing data collection and avoiding sensitive information. 

---

## 11. Team Structure (If Applicable)
If working in a group, describe:
- Team roles
- Communication plan
- Conflict resolution approach
- Workload distribution

Zarin: Researches, codes, and is the Captain of the project, main speaker.

Hayden: Researches, codes, and plays a major role in the development.

The work will be split evenly. We will ensure the project comes first and if there is any argument we wont let it affect the quality of work.
---

## 12. Documentation & Knowledge Transfer Plan
Explain how this project will be documented.  Please note that this should include documentation in the UVDesk knowledgebase at the very least.  Programming projects should include readme.md files. 

Include:
- README or user documentation
- Deployment or maintenance guides
- How another student or administrator could continue the project

There will be a README document explaining how the bot works and a list of all the commands and what they do. There will be a document on how to deploy the bot into the discord and a detailed list walking a person through the code. There will also be a document listing what we didn't want to implement, and if we think of other things, what we would've liked to implement.

---

## 13. Faculty/cpt.internal Resources Requested
List any required resources:
- VM access
- Network access
- Credentials or APIs
- Special permissions
- Hardware (if applicable)

Please be sure to consider any future tickets you may need to submit to complete this work as those will need to be generated and assigned to the appropriate groups as soon as feasibly possible once the project kicks off to ensure timely delivery.  I will step in to help where required but you will likely be working with students in other classes so please be cognizant of their time!

A group VM to have access to work on the project together without having to both do the code separately or one person does all the code. We may need a way to have the bot live in the schools system. 

A future ticket to consider could be improving the bot with any feedback from students in the future or adding a better version of the bot that includes other things related to the school.  

---- Brett Note ------

My recommendation for development would be to utilize this GitHub repository and complete it on your VMs.  This will get you practice with source control and sharing a project (learn about branches/merges/pull requests!) and allow both of you to develop simultaneously!  You could also utilize the "Issues" feature within GitHub for bug reports and new feature requests!  

As for "publshing" the bot - I can either build you a production VM OR if possible I would love to host it on our (yet to be created) docker production instance.  This way we can host several of these "services" within our infrastructure in the same accessible environment!  

---- End Brett Note ------

---

## 14. Acknowledgement of Expectations
By submitting this proposal, I acknowledge that:
- This is a self-directed technical project
- I am responsible for research and troubleshooting
- Evaluation will consider process, documentation, and professionalism

**Signature (Name & Date):**

Student 1:  __Zarin Deane__________________________ Date: __1-30-2026_____________
Student 2:  __Hayden Allen__________________________ Date: ____1-30-2026___________
Student 3:  ____________________________ Date: _______________
Student 4:  ____________________________ Date: _______________

Instructor: ____________________________ Date: _______________
