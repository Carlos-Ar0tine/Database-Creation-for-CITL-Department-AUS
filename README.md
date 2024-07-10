<h1>Designing and Creating a Database for the CITL Department within American University of Sharjah using Oracle SQL Developer</h1>

This project aims to create a new database from scratch for the department Center of Innovation for Teaching and Learning within AUS. 

* Project Description / Requirements
* Methodologies
* Results


<h2> Project Description:</h2>
This project involves creating and populating a database for managing events, budgets, speakers, venues, attendees, and related entities. The database design includes several tables with primary and foreign key constraints to maintain data integrity and relationships between different entities. Furthermore, the project required that several updateable views and PL/SQL scripts should be written. 


Tables and Their Purposes:

* BUDGET: Stores budget-related information for events.
* EVENTS: Captures details of various events, including type, catering services, and associated budget.
* SPEAKER: Maintains information about speakers for events.
* VENUE: Details about the venues where events are held.
* CITL_EMP: Stores data on CITL employees and their roles.
* SURVEY: Contains survey results from event attendees.
* ATTENDEES: Holds information about people attending the events.
* REGISTRATION: Manages the registration status of attendees.
* SCHEDULE: Records the schedule of events.
* DEPARTMENT: Details of departments within the university involved with CITL.
* FEEDBACK: Collects feedback on events.
* EMPLOYEE: Stores data on employees involved in events (different than CITL_EMP).
* SPECIAL_EVENT: Records special event requests and details.
* INT_SPEAKER: Subtype of SPEAKER for internal speakers.
* EXT_SPEAKER: Subtype of SPEAKER for external speakers.

<h2> Methodologies:</h2>
The methods taken to create the database were comprehensive. First, business rules were established to understand the scope and requirements of the project and the sequence of interactions between the database users and the desired database solution. Then, several EERDs (Enhaned Entity Relationship Diagrams) were created to map out the architecture of the database and its classes. Once the stakeholders were satisfied, the creation of the database took place using Oracle SQL Developer. 

<h2> Results:</h2>
Once the database has been established alongside the updateable views and PL/SQL scripts, we were able to streamline and automate complex data management processes, ensuring efficiency and accuracy. This approach not only fulfilled the project requirements but also demonstrated a high level of proficiency in PL/SQL programming.

> As a result of our efforts, our project was awarded the second highest grade in the class, reflecting the effectiveness and quality of our solution.
