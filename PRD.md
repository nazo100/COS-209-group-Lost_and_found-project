# **CAMPUS LOST AND FOUND SYSTEM IN BABCOCK UNIVERSITY**

#### &#x20; PROJECT DESCRIPTION

&#x20;         The campus lost and found system is going to be a web based application designed to help students report, search for, and recover lost belongings within the campus. The system provides a platform where users can report items they have lost or found, provide descriptions and locations, and search through reports to identify missing belongings. The application aims to improve the process of recovering lost items by making information accessible to the campus by the use of a single digital platform.





#### &#x20; BACKGROUND AND RESEARCH

&#x20;      Losing personal belongings in a school environment can be frustrating, especially when there is no centralized platform for reporting or searching for such items. Students may lose belongings such as: Mobile phones, Student ID cards, Bags, Books, Keys, Electronic devices, Clothing and accessories and so on

&#x20;     When an item is lost, the owner may have to ask people around the campus, go to different locations, or depend on announcement from different WhatsApp groups. A person who finds an item may not know how to identify its owner or where to report it. The proposed system will investigate these challenges through surveys and interviews with students and other members of the campus community.





#### &#x20;  RESEARCH QUESTIONS

&#x20; Me and my team interviewed different random students on campus and the following questions were asked:



1. Have you ever found any items belonging to someone else
2. Have you ever lost any items on campus
3. Where have you lost or found these items
4. Have you tried to recover or return the items
5. Were you able to recover or return the items
6. Do you know of any official lost and found system on campus
7. Would you use a campus lost and found website to report or search for items

&#x20;

##### &#x20;   RESEARCH ANSWERS/FINDINGS

From the answer gotten from different students from the survey above shows that 90 percent of students have either lost something that belongs to them or found an item belonging to someone else, with most frequent places where these items were lost or found being in Amphitheatre, SAT building and in the cafeteria. The study also tells that out of the people that were surveyed only 20 percent of them were able to find their missing item leaving out 80 percent of them to never find their lost item. It also finds that 75 percent of people would like to use a Campus lost and found website to find their lost item.





#### &#x20;    CHALLANGES THIS SYSTEM WILL ADDRESS

&#x20;      The system is intended to address the following challenges:



* Lack of a centralized platform for reporting lost and found items.
* Difficulty searching for belongings that have been lost on campus.
* Difficulty identifying the owners of found items.
* Limited access to information about items that have been recovered.
* Dependence on physical announcements and informal communication.
* Difficulty keeping track of lost and found reports.





#### &#x20;     PROPOSED SOLUTION



The Campus Lost and Found System will provide a online platform for reporting and searching for lost and found items. Users will be able to create accounts, submit item reports, upload images, provide descriptions and locations, and search for items that have been reported. When a user identifies an item they believe belongs to them, they will be able to submit a claim. The system will provide a process for verifying ownership before the item is marked as successfully recovered.

&#x20;



#### &#x20;     STUDENT WHO LOST AN ITEM

#### 

* As a student who has lost an item, I want to report the item on the platform so that other members of the campus community can help me find it.
* As a student who has lost an item, I want to search for found items so that I can identify and recover my belongings.
* As a student who has lost an item, I want to provide a description and image of the item so that it can be easily identified.



#### &#x20;     STUDENT WHO FOUND AN ITEM

* As a student who has found an item, I want to report it on the platform so that its owner can locate it.
* As a student who has found an item, I want to provide the location where I found it so that the owner can have an idea of where to recover it.





#### &#x20;       ITEM STATUS MANAGEMENT



The system shall support the following item statuses:

* Lost: The item has been reported missing.
* Found: The item has been reported as found.
* Pending Claim: A claim has been submitted for the item.
* Recovered: The item has been successfully returned to its owner.
* Closed: The report is no longer active.







#### &#x20;      DATABASE REQUIREMENTS



The system will use a POSTGRESQL a relational database to store user information. The database will contain the following tables, user ID, Full name, email, password, report created at:, report closed at:





#### &#x20;      TECHNICAL REQUIREMENTS

|LANGUAGE|PURPOSE|
|-|-|
|HTML|STRUCTURE OF THE WEBPAGE|
|CSS|TO STYLE THE WEBPAGE|
|JAVASCRIPT|TO MAKE THE WEBPAGE INTERACTIVE|
|POSTGRESQL|DATABASE|
|NODE.JS|BACKEND LOGIC|







#### BUSINESS OBJECTIVES

The main aim of this project is to make reporting and recovering lost belongings easier for members of the Babcock University community. The system is expected to:

* Provide one online place where students and other approved members of the university community can report lost and found items.
* Make it easier for users to search for items without having to ask around different parts of the campus or depend only on WhatsApp announcements.
* Improve the chances of lost items getting back to their owners by making reports easier to find.
* Keep reports organised so users and authorised administrators can know whether an item is lost, found, awaiting a claim, or recovered.
* Provide a more organised way to review claims and confirm ownership before an item is handed over.



#### TARGET USERS

The main users of the system will be people who study, work, or carry out approved activities within Babcock University. These include:

* **Students:** Students who have lost personal belongings or found items that may belong to someone else.
* **University staff:** Staff members who may lose or find items while within the university campus.
* **System administrators:** Authorised people responsible for reviewing reports, managing claims, and keeping the platform organised.

The first version of the system will mainly focus on students, since the research for this project was carried out among students. Access for other members of the university community can be confirmed with the relevant university authority.





#### FUNCTIONAL REQUIREMENTS

The system should provide the following features:

1. **User registration and login:** Users should be able to create an account and log in securely before submitting reports or claims.
2. **Report a lost item:** A user should be able to report an item they have lost by entering its name, description, category, the date it was last seen, and the location where it may have been lost.
3. **Report a found item:** A user should be able to report an item they have found by entering its name, description, category, the date it was found, and the location where it was found.
4. **Upload an image:** Users should be able to add an image to a report when they have one. The system should still allow a report to be submitted without an image.
5. **Search and filter reports:** Users should be able to search for reported items and narrow the results using details such as item name, category, location, date, and status.
6. **View item details:** Users should be able to open a report and view the information provided about the item.
7. **Submit a claim:** A user who believes a found item belongs to them should be able to submit a claim and provide information that can help confirm ownership.
8. **Review claims:** An authorised administrator should be able to review claims and decide whether the information provided is enough to confirm ownership.
9. **Manage item status:** The system should allow authorised users to update an item's status as it moves from being reported to being claimed, recovered, or closed.
10. **Manage personal reports:** Users should be able to view the reports they have submitted and check their current status.



#### NON-FUNCTIONAL REQUIREMENTS

These requirements describe how well the system should work:

* **Usability:** The website should be simple to understand and use, even for students who are not very familiar with websites of this type.
* **Mobile responsiveness:** The website should work properly on phones, tablets, and computers because many students may access it with their phones.
* **Security:** User accounts and reports should be protected. Passwords should be stored securely, and only authorised users should be allowed to perform administrative actions.
* **Privacy:** Personal information and private ownership details should not be exposed publicly. The system should only display information needed to help users identify an item.
* **Performance:** Pages and search results should load within a reasonable time under normal usage by the Babcock University community.
* **Reliability:** Reports should be stored properly and remain available when users return to the website. The system should also have a way to prevent accidental loss of stored records.
* **Data validation:** The system should check submitted information and prevent incomplete or invalid reports from being saved where required.



#### SCOPE AND PRIORITIES

The first version of the project will focus on the features needed to report, find, and recover items within Babcock University.

**Features planned for the first version (MVP):**

* User registration and login.
* Reporting lost and found items.
* Adding descriptions, locations, dates, categories, and optional images to reports.
* Searching and filtering reported items.
* Submitting and reviewing claims.
* Updating item statuses, including marking items as recovered.
* Allowing users to view their own reports and their status.

**Features that can be considered for a later version:**

* Email or in-app notifications when a possible match or a change to a claim is recorded.
* More advanced matching between lost-item and found-item reports.
* A dashboard showing useful statistics about reports and recovered items.

**Outside the first version:**

The first version will not include live tracking of personal belongings, payments, or integration with other Babcock University systems. These features can be considered later if there is a clear need and the university approves them.



#### ACCEPTANCE CRITERIA

The first version will be considered ready for use when the following can be demonstrated:

* A new user can create an account and log in with valid details.
* A logged-in user can submit a lost-item report with the required details.
* A logged-in user can submit a found-item report with the required details.
* A user can search for and filter reports using available item information.
* A user can open a report and view its details.
* A user can submit a claim for a found item and provide information to support the claim.
* An authorised administrator can review a claim and update the item's status after the ownership check.
* An item can be marked as recovered after it has been returned to its owner.
* Users can view the reports they submitted and see their current statuses.
* The website can be used on both a mobile phone and a computer without the main features breaking.
* Users who are not authorised cannot access administrative features or change another user's reports.



#### ASSUMPTIONS AND OPEN QUESTIONS

The development of this system is currently based on the following assumptions:

* Students and other approved users will have access to a phone or computer and an internet connection.
* The platform will initially be used for items lost or found within Babcock University.
* Users will provide honest and accurate descriptions of the items they report.
* The university will need to approve the platform and identify the person or office responsible for overseeing reports and recovered items.

Some details still need to be confirmed before development is completed:

* Will the system be available to students only, or will Babcock University staff also be allowed to create accounts?
* Which university office or authorised staff member will review claims and oversee the handover of recovered items?
* What kind of information or proof should a person provide before a found item can be handed over to them?
* Should users be contacted through email, in-app notifications, or another approved method?
* How long should lost and found reports remain on the platform before they are closed or archived?
* Should campus locations be selected from a prepared list, or should users be allowed to enter locations themselves?
* What rules should apply to uploaded images and the personal information shown on public reports?

These questions will be discussed with the relevant people at Babcock University as the project develops.



#### &#x20;        CONCLUSION



The Campus Lost and Found System is intended to provide an easy and organized way for members of the university community to report, search for, and recover lost belongings. By providing a  platform solely meant for lost and found items, the system will reduce dependence on other inefficient means and make it easier for people to find their lost items. The project will demonstrate the application of  database design, user authentication, data validation, API development, and system security.

