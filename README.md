# Chapter 1: Professionalism

- When a professional makes a mistake, _he/she cleans up the mess._

- No one is expecting you to write flawless code but that doesn't mean you aren't responsible for your buggy code.
- You, as a professional, should test your code before giving it into testing - _QA should find nothing._
- Design your code to be easy to test and the best way to do that is to write your tests first, before you write the code that passes them.
- _If you want your software to be flexible, you have to flex it!_ - Every time you look at a module you make small, lightweight changes to it to improve its structure.
- Your career is your responsibility, not your employer's. In a week there are 168 hours. Give your employer 40 and your career another 20. That leaves 108 - 56 for sleep leaves 52 for something else.
- _Doing your daily job is performance, not practice._ Practice is when you specifically exercise your skills outside of the performance of your job. Consider how musicians master their craft. It's not by performing. It's by practicing.


# Chapter 2: Saying NO

- As a professional you should be able and have the courage to say NO to your manager when you know a certain task is not doable in a X amount of time.

- Sometimes, as a professional, you have to negotiate in order to defend both your work ethic and the company's objectives.
- These negotiations might not be comfortable but the main goal is to agree upon the real possible solution, not upon the wishes of the stakeholders.
- By working overtime/in the weekends or by giving up on your work ethic just for the sake having the task done on time, DOES NOT make you a hero.
- Sometimes, memos of the negotiations / conversations that you had with the stakeholders might help you in future discussions.


# Chapter 3: Saying YES

- _**Say. Mean. Do.**_

- Telltale signs of **non-commitment**:
	- Need/should.
	- Hope/wish.
	- Let's ( not followed by "I..." )
- Telltale signs of **commitment**:
	- “I will do something... by this certain date...”
- "Try" can have 2 different definitions:
	- extra effort in achieving something
	- maybe, maybe not
- If you depend on someone's work to get your job done, do what you can to get what you need to move forward - adapt.
- Bring up blockers or red flags as soon as you discover them.
- Professionals are not required to say “yes” to everything that is asked of them. However, they should work hard to find creative ways to make the “yes” possible.


# Chapter 4: Coding

- Don’t write code at 3 A.M or after your personal life just punched you in the face, take your time to cool down, otherwise you will have to re-visit that code again.

- If something personal is bothering you, before starting to work, spend some time trying to eliminate those thoughts.
- _**The Zone.**_ Code written in the Zone may come out faster, but you'll be going back to visit it more, because most of the times you lose some of the big picture while you are in the Zone, so you will likely make decisions that you will later have to go back and reverse.
- Be prepared to be interrupted and help someone — it’s the professional thing to do.
- Software development is a marathon — not a sprint.
- Regularly measure your progress against your goal, and come up with three fact-based end dates: best case, nominal case and worst case.
- Do not incorporate hope in your estimates!
- You should not agree to work overtime unless:
	1. you can personally afford it
	2. it is short term, 2 weeks or less
	3. your manager has a fall-back plan in the the overtime effort fails
- Ask for help - a fresh perspective over a situation can be a profound catalyst for solving it.


# Chapter 5: TDD

- Good written tests can function like a good written documentation.

- TDD is a discipline that enhances _certainty, courage, defect reduction, documentation, and design._
- **The 3 laws of TDD:**
	1. You are not allowed to write any production code until you have first written a failing unit test.
	2. You are not allowed to write more of a unit test than is sufficient to fail - and not compiling is failing.
	3. You are not allowed to write more production code that is sufficient to pass the currently failing unit test.


# Chapter 6: Practicing

- Practicing is what professional software developers do in their own time.

- Practicing => sharpening your skills => getting paid better
- Note the difference between practicing and learning.
- An effective way to practice is doing katas. A kata simulates a problem that, most probably, you already faced at least once and you know the solution to it. How solving a kata should help you is by making you practice the movements and decisions involved in solving that specific problem.

# Chapter 7: Acceptance Testing
- Common problem in software development: Business people want to know exactly what they're going to get before they authorize a project. Developers want to know exactly what they are supposed to deliver before they estimate the project

- Writing acceptance tests helps simplifying the situation for both parties. These are tests written by a collaboration of the stakeholders and the programmers in order to define when a requirement is done
- Professional developers have a single definition of done. It supposes that all code is written, all tests pass, QA and the stakeholders have accepted - **DONE**
- Usually, BA writes the happy path version of tests and QA writes the unhappy path version, edge-cases etc.
- Unit Tests vs. Acceptance Tests - Unit tests are written by the programmers for programmers. Acceptance tests are written by the business for the business.

# Chapter 8: Testing Strategies
- Have the **Test Automation Pyramid** in mind while reading the following lines:

- Unit Tests:
	- intent is to specify the system at the lowest level
	- ideally, coverage should be somewhere around 90%
- Components Tests:
	- intent is that the business should at leas read and interpret these tests if not write them
	- ideally, these kind of tests cover roughly 50% of the system
- Integration Tests:
	- intent is to assembly groups of components and test how well they communicate with each other
	- tipically, are written by the system architects
- System Tests:
	- intent is to ensure correct system construction
	- coverage should be somewhere around 10%

# Chapter 9: Time Management
- Two truths about meetings: Meetings are necessary & Huge time wasters.

- Meetings should have a clear agenda and people involved into it should stick to it, in order to have an outcome for every item of the agenda at the end of the meeting.
- You don't have to attend to every meeting from your calendar. Also, it is not impolite to leave a meeting if you can't bring any valuable input in the discussion.
- At the DSU, what you should say is:
	- what you did yesterday;
	- what you are working on today;
	- if you have any blockers;
- A professional developer should understand the prioritization of tasks and respect it.

# Chapter 10: Estimation
- Business likes to view estimates as commitments. Developers like to view estimates as guesses. The difference is profound.

- A professional developer doesn't make a commitment unless he/she knows it can be certainly achieved.
- Avoid as much as possible the word _"try"_. It can be understood differently by the involved parties.
- An effective way to provide more accurate estimates is by using PERT's way of calculating the estimates:
	- **Optimistic**: _The necessary time to achieve the task only if everything goes exactly as it should_
	- **Nominal**: _The necessary time with the highest chance of success_
	- **Pessimistic**: _The necessary time to achieve the task only if everything goes wrong_
- The expected duration of the task can be calculated like: `Duration = (Optimistic + 4 * Nominal + Pessimistic ) / 6`
- Other estimating methods are: _Wideband Delphi, Flying Fingers, Planning Poker_

# Chapter 11: Pressure
- The professional developer should be calm and decisive under pressure. As the pressure grows he adheres to his training and disciplines, knowing that they are the best way to meet the deadlines and commitments.

- Professionals will always help the business find a way to achieve its goals. But professionals do not necessarily accept commitments made for them by the business
- If in a crisis you follow your disciplines ( like TDD ), it means you truly believe in those disciplines.
- Following the disciplines you are comfortable with and you believe in is the best way to avoid getting into a crisis.
- It's important to communicate. Avoid creating surprises, nothing makes people more angry and less rational than unpleasant surprises.

# Chapter 12: Collaboration
- Even though you aren't always in the mood of interacting with people, a software developer does pair-programming frequently.

- It's important to understand that the code is owned by the whole team, not by every individual.
- Professionals also pair because it is the best way to share knowledge with each other.
- The most efficient and effective way to review code is to collaborate in writing it.
- Every team member should be able to play the role of their colleague.

# Chapter 13: Teams and projects
- The dream team is a so-called _"gelled"_ team. In  such a team, each other knows the other's quirks and strengths.

- Teams are harder to build than projects.
- Gelled teams plan together, solve together, and get things done. Basically, such a team can make miracles happen

# Chapter 14: Mentoring, Apprenticeship and Craftsmanship
**_*Personal note:_** A clear & structured distribution of software developers based on the experience can be found by reading about _Masters, Journeymen, Apprentices/Interns_.

- A craftsman works quickly, but without rushing, provides reasonable estimates and meets commitments. A craftsman knows when to say no, but tries hard to say yes. A craftsman is a professional.