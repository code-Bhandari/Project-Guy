                                              INTRODUCTION

 1.1 Overview

 In many tertiary institutions in the country, students seek a project in a given field of specialty as part of the upper level of their degree program. Usually, a project can be filled by at most one student, though in some cases a project is suitable for more than one student to work on simultaneously. To give students something of a choice, there should be as wide a range of available projects as possible, and in any case the total number of project places should not be less than the total number of students. Typically a lecturer will also offer a range of projects, but does not necessarily expect that all will be taken up. Each student has preferences over the available projects that he/she finds acceptable, whilst a lecturer will normally have preferences over the students that he/she is willing to supervise. There may also be upper bounds on the number of students that can be assigned to a particular project, and the number of students that a given lecturer is willing to supervise. In this paper we consider the ways of allocating student project in our various institutions. 

STATEMENT OF THE PROBLEM : The traditional way of allocating project to students in our higher institution need to be reconsidered since project/research writing is sensitive aspect of student education in the higher institution. Before now, lecturers ask students to go out and get project topics for themselves for approval. This system made project writing look less like a class assignment which does not require an extra effort to complete rather an issue of copying. 

OBJECTIVE OF THE STUDY : With the advancement in file saving and file retrieval system, institution cannot afford to be ignorant of the basic tool, which is the driving force behind technological oriented administration. Much can be achieve if an institution have a well organized management system. Students project can easily be allocated to each or group of students without the problem of delayed project allocation from the supervisor or conflict of topic between two individual or group of student in the same department. Students update can be easily be accessed if the database system is enhanced. 

SIGNIFICANCE OF THE STUDY : Projects provide a flexible framework for engaging students in exploring curricular topics and developing important 21st century skills, such as communication, teamwork, and technology skills. In addition, students are motivated by the fun and creative format and the opportunity to make new friends around the world. For teachers, a school portal enables quick and easy management of student accounts and review of project work. 

SCOPE OF STUDY : The research will center on the design and implementation of Student Project Allocation and Management system for the department of computer science in the Galgotias University. 

LIMITATION OF STUDY : Usually, every work has some limitations and this study is not exempted. The two major limitations of this study are the time limits within which the study is expected to be completed as well as financial constraints. The time constraint prevents the researcher to have an in depth study and analysis on the subject matter. While the issue of financial constraint limits the frequency of investigation to/ from the institution toward gathering the necessary information relevant for the study 


1.2 Project Allocation Methods 

Undergraduate final year projects offer opportunities for students to undertake independent 
project work and to develop subject-specific and generic skills. It also provides an opportunity for staff to work closely with the student and strengthen individual students’ skills, which are not visible from a standard course assessment. However, the success of achieving some of these underlined objectives also depends on the project allocation scheme used at the beginning. Various types of project allocation techniques are used in engineering and science streams: project selection by students based on project titles provided by staff, project allocation based on the preferences of both (or negotiation between) students and lecturers, project based on student’s own proposal, etc. Each allocation technique has potential strengths and weaknesses, where a student’s choice of project is Educ. Sci. 20193 of 13 influenced by their desire to work with a particular academic staff member or desire for a particular project area 


Project allocation is a resource allocation problem where the key constraint for any programme is to ensure that the project workload among the staff are distributed evenly while matching projects to student’s demands. Doing this for a large number of students is a challenge, where the final year projects are allocated manually. 


The manual processing sequence is very time consuming and inconvenient to all parties 
involved. For instance, a student may have to manually search for a good number of project titles to find the relevant projects and then prioritise them in a form that is difficult to modify after submission. It is also troublesome for supervisors to keep track of the final year project proposals that are submitted and make changes later on. It is also very stressful and tedious for the committee members to manually assign final year projects to students one by one Therefore, most of the universities with a larger number of students these days apply some form of computer algorithms that perform the allocations based on certain inputs and constraints . In this section, we will discuss a few of the most common and popular student project allocation (SPA) methods.


1.2.1. Project Allocation Based on the Preferences of Both (or Negotiation between) Students and Lecturers 

This is one of the most common SPA methods, where both students and supervisors have their own preferences. Typically, the available projects are advertised to the students, and having browsed through the descriptions, each student (either explicitly or implicitly) forms a preference list over the projects that they find acceptable. Supervisors may also have preferences over the students and/or the projects that they offer. Manlove and O’Malley studied the problems of allocating projects, where both students and lecturers have preferences over projects, and both projects and lecturers have capacities . They proposed different algorithms and tried to find a more stable allocation process but could not strongly propose one single method without having some approximation. Later, Iwama et al. built upon the algorithms presented by Manlove et al. and proposed an improved stability index 
for SPA . Moussa and El-Atta also studied the algorithms of Manlove and O’Malley and 
presented a new SPA model in which the lecturers have preference lists over pairs (student, project) and the students have preference lists over projects. Furthermore, Kazakov mentioned several complexities after analysing two different approaches applied in two consecutive academic sessions, where both the students and supervisors have preferences over projects. Kazakov identified several problems of those methods and proposed a new method having three phases, which saved time for both students and supervisors and reduced the number of randomly allocated projects .Other than making a preferred list of project titles, in some cases, students contact supervisors directly and express their interest in listed projects. A project is allocated to a student if both parties, that is, the student and the supervisor, agreed and confirmed on the same project number. The concept of first come, first served is applied and the process is usually conducted via email. Gallagher et al. suggested that with this system, there is still the problem of “popular” titles, where a large 
number of students are attracted to a small number of projects 

1.2.2. Project Selection by Students Based on Project Titles 

This is another popular SPA system, where students choose their projects by themselves based on the project titles provided by the supervisors. Many higher educational institutions worldwide have adopted this system to allocate final year projects to students . Cheung et al.described the method the Department of Civil Engineering of National University of Singapore follows to allocate the projects to final year students. They proposed an algorithm, which is intended to find an optimal allocation scheme that best matches a student’s preference to the student’s eligibility for the corresponding project, subject to the constraints in the student’s ranking, their prioritised project selections and available project spaces. This allocation scheme ensures that everyone gets a project that best matches the student’s personal preference with their ranking. Harland et al. carried out a case study to compare the factors that influence students’ choice of project in the two allocation systems, namely choice of specific title and choice of subject area Educ. Sci. 20194 of 13 followed by negotiation, and to determine whether different factors were relevant. This case study demonstrated that there is no significant difference in the factors affecting student project choices between allocation by project title and allocation by subject area followed by individual negotiation. However, the staff were generally much more enthusiastic about allocation by subject area than by title. Open comments indicated that they were able to match students’ interests, and to some extent abilities, more closely to the research projects they had available. However, SPA by project titles has benefits, such as it saves the supervisors’ time spent on negotiations with students regarding any project. It also ensures that the higher-ranked students get their desired projects to work with 

1.2.3. Project Selection by Students Based on Supervisors and/or Project Category 

Obtaining a satisfying allocation for both students and supervisors by negotiation and/or 
preference list is a challenging task, especially when the number of available supervisors is small and their popularities are highly diverse. Serrano et al. stated that no allocation system can guarantee that every student gets their first choice when the number of students is significantly greater than the number of available supervisors. They proposed a novel method based on a ranked list of supervisors, as well as categories provided to student, where a category corresponds to a general research area. A student’s satisfaction may therefore correspond to getting a project either with a highly ranked supervisor and/or in a highly ranked category. Although they claimed to have an improved level of satisfaction of students and academics, this method could be more time consuming as students have to negotiate the project title with their preferred supervisor or in their preferred area of research even after the allocation. A similar problem will occur in the method proposed by Salami and Mammam, where they proposed assigning supervisors to students rather than assigning project titles by using their algorithm. According to them, the advantages of this method is that the projects are not required to be available at the time of allocation, and students and supervisors can discuss their project ideas/topics with each other after the allocation. 

1.2.4. Project Allocation Based on Students’ Own Proposals 

Another common and popular way of SPA is a “student-led” allocation system. In this system, students design their own project and approach a member of staff to be their supervisor. Students contact supervisors directly via e-mail or in person, and it is up to that member of staff to agree to supervise the student or refer them to someone else. The topic and content of the project is established entirely between the supervisor and student. Thus, a minimum of admin staff support is needed until after the topic and supervisor have been identified. There are some positive aspects of running a student-led model as Harland et al. stated that projects suggested/proposed by students promote active student participation. Chang argues that in this method, independent students need inspiration and occasional guidance rather than full supervision such that students approaching the end of their degrees become autonomous and independent learners. Despite having these advantages, the student-led model also raises a number of issues for the undergraduate cohort as a 
whole. First, most undergraduates find choosing a research topic difficult as undergraduate students rarely have deep knowledge of any particular area in order to identify a research rationale. Students often identify a very general topic area for research, and usually produce research questions that are too broad to be tenable. In Hidi and Renninger’s terms, their interest in research needs some substantial external support, and therefore, supervisors need to spend time working on the feasibility of the project, even though students work fairly autonomously on their dissertations. This can end up with the supervisor suggesting a very different topic afterward negotiations, where students can feel disenfranchised as their ideas are set aside and they are channelled into a project for which they have less interest, enthusiasm and ownership. Volkema  also suggested that asking students 
to create their own projects from scratch presents a few difficulties and takes considerable time. Analysis from the literature and informal feedback from those involved suggests that the student-led system is unsatisfactory for the majority of staff and students. 


















1.3 EXISTING MODEL

This is a system used by Educational Institutions or other organizations, which are willing to give student projects. We have three roles in this system, an administrator, a supervisor/lecturer and a student. An administrator logs into this system, and can register a professor who belongs to that institution. Students register in this system and get user-id (similar to a website like Yahoo). A student should register, provide his information (technologies familiar with, prior project experience etc., ) and also provide information about his team members. This is saved in a database. The department shortlist student for supervisors. The lecturer/supervisor extract project topic from the list of topic in his profile page to students/group under him/her Facility for password changing - There is facility for changing the password for the student as well as the lecturer. Mail sent to students - An auto-generated email is sent to students intimating them that a supervisor/lecturer has allocated them a project. This email should be responded by the students in a week’s time as then only can a lecturer/supervisor communicate with their group The data entered by the student like name, percentage, marks, age etc should be validated appropriately. This feature will improve the robustness of the application; also this feature is a must as it prevents the incorrect data being entered in the database. 



1.3.1 PROBLEMS OF EXISTING SYSTEM

Although, the manual process of project allocation meet the requirement, in order to make the job more effective some development has to be involve. The problem, of this system however is in the speed of the process and the dissemination of information to users of the system. In the existing system, it will take a student to must wait for lecturer to collect his/her project topic. Sometime, it takes days or even weeks to get a topic. Another problem with the existing system is the fact that some of this topic given to the students are brought forward by the student thereby creating a chance of “copy and paste” which do not at the end of the day make the project work a “research study”. This problem is solved in the new system. 









                                             






1.4 METHODOLGY 
This project contains many frontend and backend files .
Backend Django files-
1.Settings.py- this is a file containing whole details of the project which binds the app with the main project. It contains all the necessary details regarding the views ,model, template, database, middleware etc .
 

2.Url.py-When a user makes a request for a page on your web app, Django controller takes over to look for the corresponding view via the url.py file, and then return the HTML response. It contains path of all the webpages. 
3.Views.py - All views for a Django application are placed in views.py file. In this a view is a python function that takes in a request and returns a response. The response can be an HTML-oriented web page or it could be even an error message or even an image. The view itself hold anything subjective in logic is essential to go back as a response. Every view is callable and holds the capability to take a request and response. It is more than a function.
 


4.Model.py - It contains database schema of the project .
 


Frontend files-
The project contains 3 html files that are the part of template.
1.home.html - This is the starting file of the project  that includes a navigation bar which connects this page further to the register page and login form which allows used to login and when the user logins with the student id and password it connects it to the next html page which is project selection .
2. projectselection.html - This project includes a form through which the user can select the project by selecting the preferred project from the list of projects .

 
Above is the snapshot of the UI of the project selection page of the project .










3. studentloginform.html - This file includes a login form which appears on the home page

 













      1.5 KEYWORDS 

•	 HTML CODE- HTML stands for Hyper Text Mark-up Language. It is a type of computer language that is primarily used for files that are posted on the internet and viewed by web browsers. HTML files can also be sent via email. 

•	WEB BROWSER - A Web browser is a software program that interprets the coding language of the World Wide Web in graphic form, displaying the translation rather than the coding. This allows anyone to “browse the Web” by simple point and click navigation, bypassing the need to know commands used in software languages.
 
•	TCP/IP - This often used but little understood set of operations stands for Transmission Control Protocol/Internet Protocol. TCP/IP is the combination of the two and describes the set of protocols that allows hosts to connect to the Internet. 

•	WWW – acronym for World Wide Web 

•	 Hyper Link - A hyperlink is a graphic or a piece of text in an Internet document that can connect readers to another webpage, or another portion of a document. Web users will usually find at least one hyperlink on every webpage. The simplest form of these is called embedded text or an embedded link. 

•	WEB DESIGN- Web design is the “skill of creating presentations of content (usually hypertext or hypermedia) that is delivered to an end-user through the World Wide Web, by way of a Web browser or other Web-enabled software like Internet television clients, micro blogging clients and RSS readers”. M. Thorn, 2003 The intent of web design is to create a web site—a collection of electronic documents and applications that reside on a web server/servers and present content and interactive features/interfaces to the end user in form of Web pages once requested. Such elements as text, bit-mapped images (GIFs, JPEGs) and forms can be placed on the page using HTML/XHTML/XML tags. Displaying more complex media (vector graphics, animations, videos, sounds) requires plugins such as Adobe Flash, QuickTime, Java run-time environment, etc. Plug-ins are also embedded into web page by using HTML/XHTML tags. 
   
•	UI - the point of human-computer interaction and communication on a device, webpage, or app. This can include display screens, keyboards, a mouse, and the appearance of a desktop 

•	ALLOCATION - Allocation is the process of requesting access to a data set. If you allocate a data set that exists, the system allows you to open the data set. If you allocate a data set that does not exist, the system creates space for it on an available device and allows you to open that space.

•	   SUPERVISOR - a person who directs and oversees the work of a postgraduate research    student.









                                                               2. Literature Reviews 

Resource allocation is an integral aspect of any organization. It is the responsibility of management to ensure the efficient allocation of organization’s resources. Decision-making function may not be effective if the required information with which the decision will be made is not available at the right time. Resource allocation is geared towards achieving the organization’s purpose. Resources are acquired, allocated, motivated and manipulated by the manager’s control. This include: plant and equipment, people, materials, money, and information. In a Polytechnic environment, conducting research in areas chosen by the students or academic is a prerequisite for meriting a degree or diploma. The Institution oversees that courses are taught and award of degree or diploma given to students who satisfactorily and successfully completed a predetermined course of study that is offered by the institution, and also found worthy in character. Central to all diplomas is a project that students have to undertake and submit in support of their candidature for their National Diploma (ND) or Higher National Diploma (HND). Part of this process is the selection and allocation of final year projects involving both academic staff and students. “Whilst the Students Project Allocation (SPA) problem from a resource allocation perspective is not an especially complex one, aspects of the aforementioned methodology are still relevant and can be utilized in a basic form to aid in this project’s success. At a conceptual level, the SPA problem relating to the Department of Computer Science involves three core objects/entities: students, projects and supervisors” Morgan (2012). The students need a project topic and an academic for supervisor, who has adequate ability to supervise the project and a willingness to do so; to complete a student’s project. From the student’s point of view, once the pairing is satisfied, “then one can say that the appropriate resources have been successfully allocated to allow both the University and students to meet their primary purposes: that students have a suitable project to undertake, and that the University enables the student to go on and complete their chosen program of enrolment whist making sure that its academic staff have a balanced workload” Morgan (2012). In some institutions abroad, the institution has a list of projects they want to embark on for a particular session. The call for projects takes the form of an email to supervisors requesting that they write their project proposals and upload them to an online learning environment used by the institution. A project proposal basically has a project title, a detailed description and the maximum number of students that will work on the project. At completion, it is uploaded to the institutions website. It is the duty of support staff to browse through the list of projects to check whether any supervisor has not uploaded sufficient number of projects. If this is the case, an email is sent to them reminding them to upload more project proposals. Bouakaz (2015) Next is the release of the project proposals to students. A few weeks prior to the project allocation week, students are given access to the site where they can view all of the supervisors’ projects for the session. An email is sent out to the students to notify them that the list of proposals has become available to view. Discussion board is available for questions and answers about the various topics. During the project allocation week, a student formally requests a project from the supervisor through the online platform. Usually, a student request for a project; the supervisor chooses the student to make the offer to; An offer notification is sent by the supervisor to the student by email; students accept an offer and the project is considered to be allocated Bouakaz (2015). The Student Project Allocation problem (SPA) is a many-to-one matching problem and is an extension of the extensively studied one-to-one Stable Marriage Problem (SMP). Although a complete and comprehensive solution to the many-to-one matching problem has yet to be found, there are many comparable examples that offer a solution based on allowing a level of compromise within the results they obtain. The Department of Computer Science, University of York is one of the Universities in UK that has a working Student Projects allocation system: A. J. Fisher computerised the project allocation process in 1998 with the aim to reduce the amount of administration time needed by students, academics, and administrative staff in allocating projects to students. He also had the intention to make the process fairer. The system manipulates input data to make it fit the GS algorithm by preventing the scenario from occurring in which students could end up without a project. Although it is not perfect, it has proven to be fairly successful. In 2000, Jonathan Dyer, a then student of the department, worked on the same project to improve the algorithm used by A. J. Fisher designed by taking a constraint logic programming approach. The system he constructed was not entirely successful because it took too long to find useful results However; Jonathan’s work was able to provide new possible areas of research which could help produce a useful system (Morgan, 2012). 

Project allocation Process
 In some institutions abroad, the institution has a list of projects they want to embark on for a particular session. The call for projects takes the form of an email to supervisors requesting that they write their project proposals and upload them to an online learning environment used by the institution. A project proposal basically has a project title, a detailed description and the maximum number of students that will work on the project. At completion, it is uploaded to the institutions website. It is the duty of a support staff to browse through the list of projects to check whether any supervisor has not uploaded sufficient number of projects. If this is the case, an email is sent to them reminding them to upload more project proposals. Bouakaz (2015) Next is the release of the project proposals to students. A few weeks prior to the project allocation week, students are given access to the site where they can view all of the supervisors’ projects for the session. An email is sent out to the students to notify them that the list of proposals has become available to view. Discussion board is available for questions and answers about the various topics. During the project allocation week, a student formally requests a project from the supervisor through the online platform. More than one student may request for a project but the supervisor may choose a student that will work on the project. An offer is then sent by the supervisor to the student by email, at which point the student will have 24 hours to accept the offer. Given that students can (and are expected to) request more than one project, they may receive several offers during the week but may only accept one offer. If an offer is accepted, the student is committing to take that project and is invariably declining any other offers they have received. Once an offer has been accepted by a student, that project is considered to be allocated Bouakaz (2015). 

2.1 Responsibilities of the supervisor 

According to (Augustsson, Jaldemark, (2012) The supervisor(s) shall monitor, support and direct the student’s work and progress soon after the allocation of project/dissertation titles. The responsibilities of the supervisor include:
I.	Proposing/supervising projects/dissertations in their own subject area; 
II.	Briefing the students and apprising them of the regulations pertaining to the final year projects/dissertations; 
III.	 Setting a framework for regular scheduled progress meeting between supervisor(s) and student; 
IV.	 Giving frequent feedback/comments on progress achieved by the student; 
V.	 Giving guidance about relevant literature on the topic under study and appropriate literature sources;
VI.	 Providing advice on issues of plagiarism, in line with the University Regulations;
VII.	Assisting in the identification of a research methodology, planning and execution of the research project (if applicable); 
VIII.	 Giving guidance on the approach for appropriate analysis of data obtained, interpretation and presentation of results (if applicable); 
IX.	 Giving guidance about the formulation of an appropriate hypothesis-driven research project and focusing on the objectives of the research (if applicable);

2.2 Responsibilities of the student

Throughout the whole project/dissertation work, the student shall seek advice, comments and guidance from his/her supervisor(s) on the nature of the project/dissertation work and standard expected. Students are advised to keep a notebook for the purpose of the meeting with supervisor(s) while the supervisor(s) may wish to keep a brief record of each meeting held. 
Bouki (2007) and Augustsson (2012) Highlighted the responsibilities of the student to include: 4 International Conference of Sciences, Engineering and Environmental Technology, vol. 1, no. 22, 18-22 August 2016 

I.	 Arranging with his/her supervisor(s) mutually agreed convenient times to discuss progress achieved (in the event that meetings are not possible, e-mails or other forms of communication may be used); 
II.	Bringing to the urgent attention of the supervisor(s) any problems (academic and personal) associated with progress; 
III.	Responding to the supervisor’s suggestions and/or criticisms on his/her work and progress; 
IV.	Following all laboratory safety guidelines (if applicable); 
V.	 Discussing the layout of the final dissertation with the supervisor(s) prior to the writing-up stage; 



2.3 What is a Project Management System? 

Project Management (PM) is defined as the application of knowledge, skills, tools, and techniques to project activities in order to meet stakeholder needs and expectations from a project. Project Management Institute (PMI) in their PMBOK GUIDE defines project management system as software that has the ability to help strategize, organize, and manage resource streams and develop resource approximations. Depending on the complexity of the software, resource breakdown structures, resource availability, resource rates and various resource calendars can be defined to assist in optimizing resource utilization. There are different types of project management systems are used to handle projects .They are unique in operation, depending on the kind of project one is managing. Mohamed, A (2016) explained five types of project management systems .Those are as follows: 

1)A desktop management is implemented as a programmed that runs on the desktop of a particular user. Users and organizations can purchase it as a desktop package. The advantage of this type is the highly responsive and graphically-intense user interface.

2)A web-based project management system is implemented as a web application to be accessed via a web browser, or an extranet. It is multi-user and can be accessed from any computer without installing the software. They are usually less responsive than desktop applications, and users can not access project information if they are offline.

3)A personal project management system is designed for handling simple or home projects. It usually has a simple interface, and mostly overlaps with single user systems. 

4)A single-user project management system is programmed with the conjecture that only one used will ever need to work on the project plan at once. This may be used in small firms, or where only a few people are associated in top-down project planning. Desktop applications are commonly classified in this category.
 
5)A collaborative or client server is specially designed to support multiple users. It easily allows the multiple users who are working on different parts of a project at the same time. It incorporates multiple collaboration tools so that users can share knowledge and expertise. The other method of project management system includes:
•	• Registers 
•	• Telephonic communications ( manager to employee, manager to contractor, manager to supervisor, etc
•	• Face-to-face communications 





















                                    3. PROPOSED WORK     
This project is aimed at developing a web-based system, which manages the activity of “Student Project Management”. This system will manage the database and maintain a list of all student groups that have registered in the department. Allocation of project will be done by lecturers registered in this system through a list of topics in the department database organized by the department board. To join other standard educational institutions in the word, it became necessary to develop a computerize students project allocation system. From implementation standpoint, modules are implemented in this project as application logic in the web pages of the web application. A module may contain several web pages each of which is used to perform a specific function. The development of any web solution begins by first sketching a rough diagram of your design based on the basic pages that need to be created. The diagram shown below illustrates the structure of the web application. The entire pages do not all inter link because the creation of a new, personalized presentation is available only if no session exist for the current user. 

3.1 EVALUATION OF FORMS -
The system design is based on three –tier architecture. The three –tier (layer) in which the user interface, registration process and data storage and data access are developed and maintained as independent modules or most often on separate platforms. The three logical tiers are 

FRONTEND - The part of a website that the user interacts with directly is termed the front end. It is also referred to as the ‘client side’ of the application. It includes everything that users experience directly: text colors and styles, images, graphs and tables, buttons, colors, and navigation menu. HTML, CSS, and JavaScript are the languages used for Front End development. The structure, design, behavior, and content of everything seen on browser screens when websites, web applications, or mobile apps are opened up, is implemented by front End developers. Responsiveness and performance are two main objectives of the Front End. The developer must ensure that the site is responsive i.e. it appears correctly on devices of all sizes no part of the website should behave abnormally irrespective of the size of the screen.  

Using HTML - CSS - BOOTSTRAP as Frontend
 

BACKEND - Backend is the server-side of the website. It stores and arranges data, and also makes sure everything on the client-side of the website works fine. It is the part of the website that you cannot see and interact with. It is the portion of software that does not come in direct contact with the users. The parts and characteristics developed by backend designers are indirectly accessed by users through a front-end application. Activities, like writing APIs, creating libraries, and working with system components without user interfaces or even systems of scientific programming, are also included in the backend.  

Using Python as Backend for this project


DATABASE - A database is information that is set up for easy access, management and updating. Computer databases typically store aggregations of data records or files that contain information, such as sales transactions, customer data, financials and product information. 

3.2 IMPLEMENTATION 

When preparing system implementation plans, certain things must be considered. For this project, the new system differs a little from that of the existing one because of its nature. It is computerized and requires the services of competent and well trained staff for it to be effectively operational. Implementation of the new system involves: 
(1) Training of staff 
(2) System testing 
(3) System change over 
(4) System review and maintenance 

1 TRAINING OF-STAFF It is important to prepare training schedule for the staff before the new system is to be installed. The user of the new system should be given specific time for training courses. This will enable them fit into the new system. Also, user manual will be produced in regards to the operation of the new system. 

2 SYSTEM TESTING For the implementation of the new system, data must be prepared for live testing. The result from the new system is compared to that of the existing system to check if the expected result was achieved. It is also necessary to formulate the operation of the new system to check the overall time and ability of the staff to handle the operation of the new system.

3 SYSTEM CHANGE OVER The parallel method is adopted in the changeover process. This method was adopted because it creates an avenue where by the old and new systems are being run concurrently. With this method, the users of the system will gain a practical knowledge of how the new system is being operated. When this is achieved, the old system is discontinued and the new system takes its place. This method also helps to introduce the new system to users having little or no notice of the change over process. 

4 SYSTEM REVIEW MAINTENANCE The system should be reviewed and maintained periodically in order to deal with unforeseen operational problems that may arise and to make sure that the new system meets its planned objectives or standard. 
 
DOCUMENTATION The administrator controls the logging in process in such a way that unauthorized user do not log in, add new lecturer/supervisor to the list, update lecturer/supervisor’s profile, determine if a student should be given project supervisor after students assessment, add and delete student or supervisor below requirement 

     







3.3 FLOWCHART

For admin Side
 

For Student Side
 


Modules in the Project  

Student Project Allocation Module
The system is made of several modules in which some important modules are:
Admin
In the admin module the overall control will have the institute administrator and by using this module an institute can give access to any person by providing an ID and password to those while it can also check the information that who had access to the system with date and time.
User
In the user module, a person can only view the details by login to the system with their Unique ID provided by the system.

MODULES: 

1. ADMIN MODULE  
2. STUDENT MODULE 

1. ADMIN MODULE: 

1. REGISTER 
2. LOGIN 
3. STUDENT -MODIFING DETAILS 
4. DEPARTMENTS-ENTERING/MODIFYING DETAILS 

1. REGISTER: To be authenticated first have to be registered. 

2. LOGIN: The Registered User Can be allowed to view inner details for which he Permitted 

3. STUDENT -MODIFING DETAILS: Admin can be modified to change status of each User.

4. DEPARTMENTS-ENTERING/MODIFYING DETAILS: New departments adding and old department deletions are spend by this user. 

2. STUDENT MODULE: 

1. REGISTER 
2. LOGIN 
3. COOSE PROJECT 
4. SUBMIT  

1. REGISTER: To be authenticated first have to be registered 

2. LOGIN: The Registered User Can be allowed to view inner details for which he Permitted
 
3. CHOOSE PROJECT: Choose project from variety of topics

4. SUBMIT: After selecting your project submit


























3.4 DESIGN
Student Login Interface - This is student's login form and login will work only when a student is registered. so first Person need to register itself in register form to proceed for project selection

 



Admin Login Panel - This is your admin panel in which only admin can login with his user id and password

 



Admin Dashboard - This is a dashboard of the admin, in which you will get the  list of student login, you will get all the information of which student is registered and which project you have selected, which Course The Student belongs you will get everything in it.

 

Student Register Panel - This is the registration form of the student in which you have to give the name first, after that you have to define the ID and password of the student you want  to register, you will see a lot of Text fields like the mobile number ,Course , Dob and More, you have to fill all of them to register particular student.

 

 




















TOOLS / TECHNOLOGY USED 

HTML : HTML stands for Hyper Text Markup Language which is used for documents designed to be displayed in a web browser.
Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML describes the structure of a web page semantically and originally included cues for the appearance of the document.

CSS : CSS stands for  Cascading Style Sheets ,it is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is used for designing the webpages.

DJANGO : Django is a Python-based free and open-source web framework that follows the model–template–views (MTV) architectural pattern. Django's primary goal is to ease the creation of complex, database-driven websites. The framework emphasizes reusability and "pluggability" of components, less code, low coupling, rapid development, and the principle of don't repeat yourself. Python is used throughout, even for settings, files, and data models. 
Some well-known sites that use Django include Instagram, Mozilla, Disqus, Bitbucket, Nextdoor and Clubhouse.
In this project we have used the django to join the backend  and frontend together. django is a high-level python framework that enables rapid development of secure and maintain websites. There are so many framework from which we can connect both the end together for example Nodejs, React, Angular, Spring boot and many other . I have used django because it uses python which  is easy to understand as compared to other languages. django uses MVC architecture, and using its own Object Relational Mapper (ORM) for making CRUD operation calls to the database, Django helps to develop complex features quickly. In frontend we have to make sure the visual aspects of a website are functional. we are focused on what the user sees when they visit a website or app. We have used css, javascript, php and html.

PYTHON : Python is a high-level, interpreted, general-purpose programming language. Its design philosophy emphasizes code readability with the use of significant indentation. Python is dynamically-typed and garbage-collected. It supports multiple programming paradigms, including structured (particularly procedural), object-oriented and functional programming. It is often described as a "batteries included" language due to its comprehensive standard library.




Bootstrap - Bootstrap is a free and open-source front-end framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. Unlike many web frameworks, it concerns itself with front-end development only. 

Java Script -  JavaScript often abbreviated as JS, is a high-level, interpreted programming language. It is a language which is also characterized as dynamic, weakly typed, prototype-based andmulti-paradigm. Alongside HTML and CSS, JavaScript is one of the three core technologies of the WorldWide Web. JavaScript enables interactive web pages and thus is an essential part of web applications. The vast majority of websites use it, and all major web browsers have a dedicated JavaScript engine to execute it. 

VS CODE - Visual Studio Code is one of the best IDE for development purposes but when you install it, initially it does not have support for Python. It allows JavaScript and TypeScript – however for other programming languages we need to install some plugins for VS Code to support the particular language. 
 

MVT ACHITECTURE : MVT architecture is the software design pattern used by the Django web framework.MVT stands for Model – View – Template.  The view is used to execute the business logic and interact with a model to carry data and renders a template. There is no separate  controller and complete application is based on Model View and Template.
 





3.5 REQUIREMENTS

Minimum Software Requirements 

·	Operating System: Windows 
·	Web-Technology: Django 
·	Front-End: HTML, CSS, and Bootstrap 
·	Back-End: Python

Minimum Hardware Requirements
The minimum system requirement for the proposed project.  “ProjectGuy” is mentioned following.
System Requirement;-
•	Processor-1.2Ghz.
•	Ram-512MB.

Advantage of the Project
•	Easy to use - Easy to implement because it gives user friendly interface to the student and it can be Done in easy steps

•	Django Make Thing faster
1.	Reduce the amount of queries. ...
2.	Go asynchronous wherever you may with Celery. ...
3.	Do not repeat yourself. ...
4.	Cache the predictable data. ...
5.	Keep your code clean. ...
6.	Keep calm and enjoy Django!

•	No Need Of High Maintenance 

Limitations of the Project
•	Data May Be Overloaded
•	Less Security Against Cyber attacks
•	Site May be work Slow Due To Network Issue





 3.6 SYSTEM SCOPE
This student allocation system is inclined towards easily allocating students to supervisors and also allowing supervisors provide recommended project topics to their respective students within a reasonable time frame. The system was designed to be thorough without being too complex and cumbersome, robust enough to work well with minimum input. Having a well-designed allocation system endowed with extensive database use is in the best interest of both supervisors since other difficulties that come with final year projects can be reduced drastically if not totally avoided.




















                                                 CONCLUSION 

The Internet has truly changed the way we do a lot of things today; we now have the ability to do virtually everything from our computers. The online student project allocation is an emerging technology and a computer system has revolutionized the world thereby making tasks that seems difficult easy by the use of Internet. Students no longer need to overcrowd supervisor office because of project topic or research suggestion as this as been solved by this web application. Students can now at their comfort proceed with their project work online. What a welcoming development. This project work has emphasized the capabilities and reliabilities of a computer system i.e. It accuracy, speed and timeliness of information that it encompasses. The most important lesson from this project work is that information is essential and its availability cannot be washed away and the ability to move such information through 


The student project allocation system assists in automating the existing manual system. It reduces the manpower required. It provides accurate information always. Difficulties can be reduced and all years together gathered information can be saved and can be accessed at any time. The data which is stored in the repository helps in taking intelligent decisions by the management.
Though a lot of work has been done on this system to get this far, there are several other functionalities that could be added to make it complete. However, time constraint did not make it possible for this to materialize therefore I recommend that future work on this project should strive to include the features such as;

1. Better arrangement of tabs
2. Group Student Project Allocation
