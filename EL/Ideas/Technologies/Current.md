(also see Papers based on [[Papers Based on Existing work]])

<font color="#00b050">Learn Coding</font>
- [ ] Research: 
	- [ ] Parallel Courseware effectiveness (ask engineering students and nonCS to test each objective/benefit - see Parallel Courseware paper)
	- [ ] deploy/test (COSC 111,121 and APSC177) and analyze how the student use the platform.
- [ ] Development:
	- [ ] Connect to Canvas 
	- [ ] Instructor level access rights (i.e. who can access what).
	- [ ] Motomo test/improvements 
	- [ ] UI improvement (Home Screen)
	- [ ] Touch screens, reactive, etc.
	- [ ] Create a 'textbook' that can be viewed on  tablets/touchscreens. the textbook has the same material and features as the website
- [ ] Content: 
	- [ ] Lesson cover artwork (lesson image)
	- [ ] Add Videos 
	- [ ] Links (replace "link" with an actual link)
	- [ ] Advanced / Beginner
	- [ ] Summary at end of each lesson
	- [ ] Try-it yourself or Python Tutor whereever appropriate (see lessons original html)
	- [ ] badges to modules
	- [ ] More Courses:: Apply for a FUNDING to create another course!!!
- [ ] ... see proposal

<font color="#00b050">Course Planner</font>
* Development: 
	* <font color="#00b050">Planner</font>: 
		* generic plan, other degrees, minor/major
		* AI companion (choices explanation, suggestions based on advising, etc )
	* <font color="#00b050">Scheduler</font>: send schedules back to Workday  
	* <font color="#00b050">Transcript</font>: read/integrate
	* <font color="#00b050">Degree</font>: read degree  requirements, verify degree vs courses, etc.
		* Find a way to read the degree requirements from UBC public data (e.g. scrape websites, read directly from Workday database, ..)
		- Figure out a way to formally model the degree requirements (e.g. json object) so they can be used in the program
		- Find a way to compare and allocate courses to the degree and show the result of how many requirements are satisfied/not satisfied.
	* <font color="#00b050">Advising</font>: AI refining (still not accurate), more resources (read from reddit etc), host LLM
	* <font color="#00b050">Course Insignts</font>: social media posts (reddit), ratemyprof, grade history, etc.
	* **General**: 
		* Error Handling/Boundaries
		* Unit test
* Research: 
	- [ ] Optimizer (CoursePlanner:)
		- [ ] Java -> Web
		- [ ] Gabriella's bug from before (when optimization more than once)
			- [ ] Screen freeze when: optimize->accept changes ->lock a course 121 ->  optimize again -> accept -> Index 0 out of bounds for length 
		- [ ] Rajveer's work?
	- [ ] Optimizer (Scheduler )
	- [ ] deploy and test

<font color="#00b050">NuTeach</font> 
- Connect Canvas
- Deploy/test
- More features , e.g.:
	- integrate AI Tutor to help with studying
	- gamification components: e.g. game-currency/rewards, daily visits, etc.

<font color="#00b050">TA Allocator</font>
- [ ] Java -> Web
- [ ] Alternative Solutions (instead of one optimal sol)
- [ ] Sensitivity analysis.
* Specific Features
	- [ ] Add Gui with stats/info about TAs/CoursesToSched/etc. (maybe top bar?)
	- [ ] TA reasoning for not being able to TA a section
	- [ ] more error handling?
	- [ ] what if csv headers changed? use enum? settings? etc? e.g. enum SEC_TYPE=settings.getSecTypeHeader(); then used SEC_TYPE everywhere.
	- [ ] toOptimize option for courses/labs: UI and model
	- [ ] mustMarkOwnlab option per course (now implemented as an attribute in Courses) + UI

<font color="#00b050">Inactive Technologies</font>
- [ ]  DataPlayground: **Study** of Effectiveness
- [ ] Akshat: Learning Data structures by example
- [ ] Larry: Spaced Repetition 
- [ ] Collaborative Filtering Quizzes