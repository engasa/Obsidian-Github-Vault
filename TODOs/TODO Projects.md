** ALT-2040 **
--------------
- TODO:
    Lists case study => Only Math is done! (now saved under lesson: Loops)
    set case studies to advanced badges

- new quizzes: more discipline based for each chapter?? (e.g. beginnier quizzes?)

- Translation:
    - DONE: Add google french translation
    - Hire someone to proofread

- videos
- links (replace "link" with an actual link)
    
- advanced / beginner
- lesson cover artwork (lesson image)
- css
- Try-it yourself or Python Tutor whereever appropriate (see lessons original html)
- badges to lessons
- summary at end of each lesson

- hire more people
    - translation
    - look and feel
    - ... see proposal

More Courses:
    Apply for a NEW ALT to create another course!!!
    Reach out to collaborator

-------------------
** TA Allocators **
-------------------
- merge Student + gui Applicant -> very easy but need to have the server running for testing purposes (ensure that code changes don't produce invalid output)
- Add Gui with stats/info about TAs/CoursesToSched/etc. (maybe top bar?)
- TA reasoning for not being able to TA a section
- more error handling?

- what if csv headers changed? use enum? settings? etc? e.g. enum SEC_TYPE=settings.getSecTypeHeader(); then used SEC_TYPE everywhere.


- toOptimize option for courses/labs
    - UI and model
    
- mustMarkOwnlab option per course (now implemented as an attribute in Courses)
    - UI
    
---DONE----
- get rid of coursesToSched and sectToSched classes and csv
- CoursesThatNeedTaCurrTerm should be enough!!
- replace SectToSched with Section
- ?remove conflictingSections map - replace with simple method call
- ?merge SectionManager into Section
- Section replace redundant attributes (Course)

---ignore---
- AllCourses hashmap -> use course numeric ID as key. course ID is sometimes an int, e.g. 36, and sometimes it is something like COSC111W1 - need to be consistent!
    -> NO, too much work for little gain


-------------
*** BREB ***
-------------
- Application:
    - If qualitrics is anonymous - maybe keep everything anonymous?
    - Or ask for student name + id - instructor will only have access to anonymous data - identifiable data after course appeal

- Questionnaire 2: ALT 
- Consent form + other docs (see https://isotl.ctlt.ubc.ca/breb-application/)

    
--------------------
** COURSE PLANNER **
--------------------
- Calendar data:
    - I spoke with Tony from IT who offered to provide a CSV file with course info (based on SISC - can be all previous years)
    - Capstone work - use their code ==> not really. see above point.
- BSc STAT : how to implement "Stream Requirements"
- Refactor
    - see note on galaxy notes
- replace terminate with error message!

- Connect UI to Optimization 
- Degree (major/minor, etc)
    - update class so that it has two degrees internally (i.e. don't create two objects of the Degree class for more than a major)
    - have differnt versions of rules for the degree (see degree navigator)
    - email IT or someone to get a copy of the code/rules used on degree navigator
- Add button "Reset optimization" - defaults should be stored somewhere (csv or something)

- Gabriella's bug from before (when optimization more than once)
    Screen freeze when: optimize->accept changes ->lock a course 121 ->  optimize again -> accept -> Index 0 out of bounds for length 0
later
- When closing, only ask if want to save if changes made
- do we really have to load allcoruses.csv? use DB? something else?