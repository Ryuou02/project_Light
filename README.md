# project_Light
Abstract:
The “Light” is a data bank that stores your personal data in a secure way and allows for the secure sharing of data at the click of a button. The data receiver has their side of the software that allows to send a request to receive specific data from a specific user. The user then verifies their identity and shares the data as he/she sees fit to be shared.

The data banks are Registration centers where authentication of users is done and all the details they provide into the database are real.
The admin has control over all users but the main role of admin is to register registration centers.
Registration centers mainly invlolve 2 users:

I)Trusted Data Receiver
These users typically include hospitals, police stations, schools etc all of which have their identities verified by registration centers.
They have the ability to create their own database to store data that is specific                                 to their organization.
Highly trusted data receivers such as Hospital and police have ability to access normal users data.



II)Regular User
These are standard users who simply input their data and provide their databank ID to facilitate data sharing. Their information is categorized as basic and personal. The basic details are accessible to hospitals and the police for the purpose of swift identification during emergencies.
Personal data is not stored in the database as it is. The user has the option of storing their personal data either with themselves or on the server as an encrypted file protected by a password.

           
KeyFeatures:
1)Data Encryption options
Users can choose to store their personal data either with themselves or on the server as an encrypted file secured by a password.

2) Hash encryption :
The server retains the hash of the unencrypted file to prevent any tampering by the user when the data is in their possession.

3)Segregation of Important Data:
important information like aadhar card , pan details etc are stored separately from other personal information, streamlining the sharing process for critical documents. If the data receiver is identified to be a hospital or police station, it can be sent without any validation from the user since, this data may be required by them in case of emergency.

4)Password Protection for Sharing: 
When sharing personal data, users are required to enter a password and review all the information being shared, adding an extra layer of security and control. In the end, it is all the user’s decision whether he/she wants to share the data or not.

5) Protection against Web Vulnerabilities:
Protection from different kind of SQL Injection attack through implementation of rigorous input validation, parameterized statements, and secure database user configurations
6) Protection against Packet Sniffing Vulnerabilities:
The data will be encrypted using RSA encryption before sending to other devices. This makes sure that even if someone gets their hands on the data that is sent from one device to the other, while it is being sent, that person won’t be able to see the content in it since it is encrypted.



Software & Hardware Requirements:

Server Infrastructure: A dedicated server or cloud-based hosting environment with sufficient computational resources, including CPU, RAM, and storage, to accommodate the expected volume of user data.

Network Connectivity: High-speed internet connectivity to ensure seamless data transmission and user access to the system.

Client Devices: Users should have access to internet-enabled devices such as smartphones, tablets, or computers for interaction with the "Light" system.

Secure Storage Medium: Storage devices or cloud storage solutions for safeguarding user data, ensuring data redundancy, and maintaining backups.

Operating System: The server should be running a compatible and secure operating system, such as Linux (e.g., Ubuntu, CentOS) or Windows Server, with necessary updates and security patches applied.

Web Server: A web server software (e.g., Apache, Nginx) to host the web application and facilitate communication between users and the system.

Database Management System: A reliable DBMS (e.g., MySQL, PostgreSQL) for storing user data securely and efficiently. Proper configuration and optimization of the DBMS are essential.

Backend Framework: A backend framework (e.g., Django, Ruby on Rails, Node.js) to handle user authentication, data processing, and communication with the database.

Frontend Technologies: Web technologies (e.g., HTML, CSS, JavaScript) for creating and intuitive and user-friendly interface accessible from web browsers.

Security Measures: Implementation of security protocols, encryption libraries, and firewall configurations to protect user data from unauthorized access and cyber threats.

Data Encryption Tools: Tools or libraries for data encryption and decryption, ensuring that sensitive user information remains confidential.

Dependency Management: A package manager (e.g., npm, pip) for managing and updating project dependencies and libraries.

Development Environment: Integrated Development Environments (IDEs) and code editors for software development and debugging.
