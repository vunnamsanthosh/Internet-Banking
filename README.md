SOFTWARE REQUIRMENT SPECIFICATIONS FOR INTERNET BANKING

1.INTRODUCTION
  1.1   Purpose of the Document:
The purpose of the SRS document is to define and document the     requirements of a software system comprehensively, facilitating effective communication, project management, development, testing, and quality assurance throughout the software development lifecycle.
1.2	Scope of the project:
It serves as a critical document that outlines what the project will achieve, what it will produce, what constraints and assumptions it operates under, and what is specifically excluded from the project. It provides a clear and shared understanding of the project's boundaries, helping to prevent misunderstandings and scope changes that can impact project success.
1.3	Overview of the Internet Banking:
It is a digital service provided by banks and financial institutions that allows customers to conduct various banking transactions and access financial services through the internet. It has revolutionized the way people manage their finances, offering convenience, accessibility, and a wide range of banking functions from the comfort of their computers or mobile devices.

 2.FUNCTIONAL REQUIREMENTS 
    2.1   User requirements and authentication:
User has to give the basic details to create an account in the website for better features and accessibility.
     2.2    Content management: 
The users can able to check their account transactions and balances easily in their mobiles it self they no need to go bank for balance checking.
   2.3    Search and Navigation:
They empower customers to find information, perform transactions, and manage their accounts efficiently while maintaining a high level of security and accessibility.
3. Non- Functional Requirements
          Non-functional requirements are requirements that are not directly concerned with the specific functions delivered by the system. They may relate to emergent system properties such as reliability, response time and store occupancy. They may specify system performance, security,  availability, and other emergent properties.

   3.1 Safety Requirements:
           a. Backup, recovery & business continuity Banks should ensure adequate back up of data as may be required by their operations. Banks should also have, well documented and tested business continuity plans that address all aspects of the bank’s business.
         b. Both data and software should be backed up periodically. 
         c. An off-site back up is necessary for recovery from major failures / disasters to ensure business continuity.

  3.2 Security Requirements: 
a. Account ID and Password (PIN) Protection 
b. Auto Timeout Screen Blanking 
c. Sign-off Button 
d. Failed Log-on Attempts 
e. Encryption 
3.3 Software Quality Attributes: 
a. Reliability 
Measure if product is reliable enough to sustain in any condition. 
Should give consistently correct results. Product reliability is 
measured in terms of working of project under different working 
environment and different conditions. 
b. Maintainability 
Different versions of the product should be easy to maintain. For 
development, its should be easy to add code to existing system, 
should be easy to upgrade for new features and new technologies 
time to time. Maintenance should be cost effective and easy. System 
be easy to maintain and correcting defects or making a change in the 
software. 
c. Usability 
This can be measured in terms of ease of use. Application should be 
user friendly. Should be easy to learn. Navigation should be simple. 
d. Portability 
This can be measured in terms of Costing issues related to porting, 
Technical issues related to porting, Behavioral issues related to porting.
 e. Correctness 
Application should be correct in terms of its functionality, 
calculations used internally and the navigation should be correct. This 
means application should adhere to functional requirements. 
f. Efficiency 
To Major system quality attribute. Measured in terms of time 
required to complete any task given to the system. For example 
system should utilize processor capacity, disk space and memory 
efficiently. If system is using all the available resources then user 
will get degraded performance failing the system for efficiency. If 
system is not efficient then it can not be used in real time 
applications. 
g. Flexibility 
Should be flexible enough to modify. Adaptable to other products 
with which it needs interaction. Should be easy to interface with 
other standard 3rd party components.
3.3 Hardware Requirements: 

       Standard pc 
       Internet connection with good enough speed 
       ATM 
       Pentium IV 1.7 GHz class or better processor 
       128MB or more RAM (256 recommended) 
       At least 500 MB Hard disk space. 
       Smart mobile phone
3.4 Software Requirements:
This product is developed mainly using open source technologies like apache, php,  etc. So, we can use any operating system for developing this product. 
Frontend Technologies:
  JavaScript Framework:-
  Requirement 1: Use a modern JavaScript framework like React.js or Angular.js for building the front-end of the portfolio website.
  CSS Framework:-
  Requirement 2: Utilize a CSS framework such as Bootstrap or Tailwind CSS for efficient styling and responsive design.
  JavaScript Libraries:-
  Requirement 3: Use appropriate JavaScript libraries for features like animations, modals, or any specific UI/UX enhancements.
  Version Control:-
  Requirement 4: Implement a version control system (e.g., Git) for efficient team collaboration and code management.

Back-End Technologies: 
Server-Side Framework:-
Requirement 5: Choose a suitable server-side framework like Node.js with Express.js for handling server logic and API endpoints. 
Database:- 
Requirement 6: Use a database system such as MongoDB or PostgreSQL to store project, service, and user data.
Authentication:-
Requirement 7: Implement authentication using a secure mechanism (e.g., JWT) to manage user accounts and profiles.


CONCLUSION:
This Software Requirements Specification (SRS) specifies the requirements needed for the Banking System, which will be used in the Banks. This document will be used by the customer to ensure all specifications are correct and verified by the software Engineer to design the system. It deals with the internal banking functions like new account registration, withdrawal, deposit, account closure,& exclusively for the customers, who could access it from anywhere having an internet connection. The banking system uses a well interfaced GUI and well designed Web Forms for specific actions required by the users. It will need to be connected to a main database server for storing and retrieving the data of the customers. 
This SRS would be used by the following people: 
Bank Employees : They would be using the Core Banking Solution to 
perform the various banking functionalities. 
Bank Customers: They would be using the e-Banking Solution to view their account details. 
Research Students : Research students are advised to read all the section of this document to get an overall idea of the workflow and technicalities of the software. 
Testers: It can be used as a documentation to know the interfaces.
