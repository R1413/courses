# Multigrid Methods (APPM 6640, Summer 2017)


### Course Information 

* **Class Date/Time**: MTW 2:30-4:30pm 
* **Class Location**: ECCS 1B14 
* **Instructor**: Chris Ketelsen 
* **Prerequisites**: APPM 5600 _or_ CSCI 5646 
* **Office Hours**: MTW 1-2pm in ECOT 731 _or_ by appointment  

### Course Description  

Focuses on multigrid techniques for solving systems arising from the discretization of elliptic and parabolic partial differential equations.  Includes discussion of classic iterative methods, geometric and algebraic multigrid methods, as well as methods for nonlinear problems.  Stresses significant computer science applications and programming. 

### Course Objectives 

* To develop the ability to derive, analyze, and implement multigrid algorithms.
* To recognize the wide use of multilevel methods in applications.
* To extend the concepts learned in previous courses to a wider class of problems.
* To gain a broader knowledge of and appreciation for mathematics and its applications.

### Textbook 

We will use [_A Multigrid Tutorial,](https://www.amazon.com/Multigrid-Tutorial-William-L-Briggs/dp/0898714621/ref=sr_1_1?ie=UTF8&qid=1496677225&sr=8-1&keywords=A+multigrid+tutorial) by Briggs et al., Society of Industrial and Applied Mathematics, 2nd ed., 2000. A digital copy of the book is available for free through the CU Library, but if would prefer a 
paperback copy, it is available through Amazon or through SIAM Publishing. 

### Programming

A central goal of this course is to be able to implement multigrid methods and critically analyze the results relative to the developed theory. Experience in a scientific programming language is a course prerequisite.  For this course we will use Julia in combinations with Jupyter Notebooks. Julia is a fast, open-source scientific programming language that is syntactically similar to Matlab. 

### Homework 

You will complete homework assignments throughout the course.  Each homework assignment will have a theoretical component and a programming component.  The theoretical component may require proofs, derivations, or computer implementation/verification of numerical methods. The implementation components are designed to familiarize you with the individual pieces of the multigrid algorithm, the main goal being your own functioning multigrid code midway through the term.  All homework assignments will be completed in Jupyter Notebook and will be submitted online.  You will be allowed 3 free late days for the semester.  After your late days are expended, a 20\% penalty will be assessed for each day past the due date.  

### Algebraic Multgrid Project 

Towards the end of the course you will complete a group project in which you will implement a particular algebraic multigrid algorithm 
and apply it to an application problem of your choosing.  You will submit a 5-10 page project report and give a group presentation in 
the last week of class.  


### Grade Determination 

Overall, the contributions to the final grades will be: 
* Homework (65% of the grade)
* Project (25% of the grade)
* Participation (10% of the grade)

Unless adjustments are necessary, letter grades will be assigned using the standard grading scale: 

| Letter | Raw Average |
|--------|-----------|
|     A  |   93-100    |
|     A- |   90-92     |
|     B+ |   87-89     |
|     B  |   83-86     |
|     B- |   80-82     |
|     C+ |   77-79     |
|     C  |   73-76     |
|     C- |   70-72     |
|     D+ |   67-69     |
|     D  |   63-66     |
|     D- |   60-62     |
|     F  |   00-59     |

### Course Web Page 

[https://piazza.com/colorado/summer2017/appm6640](https://piazza.com/colorado/summer2017/appm6640)

This term we will be using Piazza for class
discussion. The system is highly catered to getting you help fast and efficiently from classmates, the grader, and
the instructor. **Rather than emailing me questions, I request that you to post your questions on Piazza**.  If your question 
is of a private nature, Piazza allows you to send me a private message. 
It is your responsibility to check the web page on a regular basis. Here you will find detailed information such as
news, homework assignments and solutions, and instructor office hours. 

### Collaboration Policy 

The collaboration policy is pretty simple:

* _Inspiration is free_: you may discuss homework assignments with anyone. You are especially encouraged to discuss solutions with your instructor and your classmates.

* _Plagiarism is forbidden_: the assignments that you turn in should be written entirely on your own. While writing the assignment you are not allowed to consult any source other than the textbook(s) for the class, your own class notes or the lecture slides for the class. Copying/consulting from the solution of another classmate constitutes a violation of the course's collaboration policy and the honor code.

* _Do not search for a solution on-line_: You may not actively search for a solution to the problem from the internet. This includes posting to newsgroup or asking experts at other universities.

* _When in doubt, ask_: If you have doubts about this policy or would like to discuss specific cases, please ask the instructor.

### Standard Course Policies 

<br>

**Honor Code**

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the [academic integrity policy](http://www.colorado.edu/policies/academic-integrity-policy) of the institution. Violations of the policy may include: plagiarism, cheating, fabrication, lying, bribery, threat, unauthorized access, clicker fraud, resubmission, and aiding academic dishonesty. All incidents of academic misconduct will be reported to the Honor Code Council (honor@colorado.edu; 303-735-2273). Students who are found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code Council as well as academic sanctions from the faculty member. Additional information regarding the academic integrity policy can be found at [honorcode.colorado.edu](http://honorcode.colorado.edu/).

**Disability Accommodations**

If you qualify for accommodations because of a disability, please submit to your professor a letter from Disability Services in a timely manner (for exam accommodations provide your letter at least one week prior to the exam) so that your needs can be addressed. Disability Services determines accommodations based on documented disabilities. Contact Disability Services at 303-492-8671 or by e-mail at [dsinfo@colorado.edu](mailto:dsinfo@colorado.edu). If you have a temporary medical condition or injury, see the [Temporary Injuries](http://www.colorado.edu/disabilityservices/students/temporary-medical-conditions) guidelines under the Quick Links at the [Disability Services](http://www.colorado.edu/disabilityservices/) website and discuss your needs with your professor.


**Religious Observances**

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments, or required attendance. If you have an exam or assignment conflict due to a religious observance please notify me in a timely manner. See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.


**Classroom Behavior**

Students and faculty each have responsibility for maintaining an appropriate learning environment. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with differences of race, color, culture, religion, creed, politics, veteran's status, sexual orientation, gender, gender identity and gender expression, age, disability, and nationalities. Class rosters are provided to the instructor with the student's legal name. I will gladly honor your request to address you by an alternate name or gender pronoun. Please advise me of this preference early in the semester so that I may make appropriate changes to my records. For more information, see the policies on [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior) and the [student code](http://www.colorado.edu/osc/sites/default/files/attached-files/studentconductcode_16-17-a.pdf).


**Sexual Misconduct, Discrimination, Harassment and/or Related Retaliation**

The University of Colorado Boulder (CU Boulder) is committed to maintaining a positive learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct, discrimination, harassment or related retaliation against or by any employee or student. CU's Sexual Misconduct Policy prohibits sexual assault, sexual exploitation, sexual harassment, intimate partner abuse (dating or domestic violence), stalking or related retaliation. CU Boulder's Discrimination and Harassment Policy prohibits discrimination, harassment or related retaliation based on race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy. Individuals who believe they have been subject to misconduct under either policy should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127. Information about the OIEC, the above referenced policies, and the campus resources available to assist individuals regarding sexual misconduct, discrimination, harassment or related retaliation can be found at the [OIEC website](http://www.colorado.edu/institutionalequity/).



