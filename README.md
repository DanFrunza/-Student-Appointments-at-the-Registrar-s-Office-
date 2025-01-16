Project Title: "Student Appointments at the Registrar's Office"

Description:

This Java web application provides a platform for students to schedule appointments at the Registrar's Office. Administrators can manage these appointments and view the appointments.
Technologies Used:


Java: Core programming language.   

Jakarta EE: Java EE platform for enterprise applications, including CDI (Contexts and Dependency Injection).   

JPA: Java Persistence API for database interactions.   

XHTML: Structure of web pages.

CSS: Styling of web pages.

JSF: JavaServer Faces for building user interfaces.   

PrimeFaces: UI component library for JSF.   

Database: PostgreSQL

Build tool: Maven   

Server: Payara



Features:

User registration and authentication: For both students and administrators.

Appointment scheduling: Students can schedule appointments for specific dates and times and see their appointments.

Appointment management: Administrators can view, edit, and cancel appointments.

Status tracking: Appointments have different statuses (active, expired, canceled). The status is automatically updated to 'expired' if the appointment date has passed.

Security: Leverages Argon2 for robust password hashing. Administrators require a unique code for account creation. Future integration of a database containing valid matriculation numbers will allow for student identity verification, enhancing system security.

User roles: Differentiated access for students and administrators.


Installation:


Clone the repository:

Bash: git clone https://github.com/DanFrunza/-Student-Appointments-at-the-Registrar-s-Office-/tree/master


Set up database:

Create a database with the specified name and schema.

Configure database connection details in the persistence.xml file.


Build the application:

Use your preferred build tool (Maven, Gradle) to compile and package the application.


Deploy the application:

Deploy the WAR file to your application server (e.g., Payara, Glassfish).



Usage:

Access the application: Open a web browser and navigate to the deployed application URL.

Login: Use the provided credentials to log in as a student or administrator.

Schedule an appointment: Students can select a date and time and submit a scheduling request.

Manage appointments: Administrators can view all appointments, filter by date, and perform actions like canceling or changing the status.



