Event Management System - Backend in progress

Overview
I am building the backend of the Event Management System, a web-based application designed to streamline 
the organization and management of events. The system allows users to create, manage, and attend events. 
It includes features such as event creation, user registration, authentication, event search, and more.

The backend is built using Node.js, Express.js, and MongoDB, with a REST API architecture.


Planned Features
1. User Registration and Authentication
        . Users can sign up and log in using email and password.
        . Passwords are securely hashed.
        . JWT (JSON Web Tokens) are used for authentication and session management.

 2. Role-Based Access Control

    Two main roles:
       .Admin: Can manage all users and events.
       .User: Can create, update, and attend events.
       .Access to different API routes is restricted based on user roles.

3. Event Management

Create: Users can create new events by providing details such as the title, description, date, time, and location.
Update: Event organizers can update event details.
Delete: Event organizers or admins can delete events.

4. Event Search and Filtering

Users can search for events based on keywords, categories, dates, or locations.
Pagination support for large event listings.

5. Email Notifications

Email notifications for event-related actions, such as when a user RSVPs or when an event is updated/canceled.
Email reminders can be sent before the event start time.

6. Admin Dashboard

Admins can view all users and events.
Admins can manage user accounts (suspend, delete).
Admins can manage all events, including editing or removing events created by other users.


7. Third-Party Integrations (Optional)

Payment gateway integration for paid events.
Integration with external calendar apps (e.g., Google Calendar) for event scheduling.

8. API Documentation (Swagger)

Full API documentation available, detailing all the endpoints, request/response structures,
and authentication requirements.



Technologies Used

Node.js: JavaScript runtime for backend development.
Express.js: Web framework for building RESTful APIs.
MongoDB: NoSQL database for storing event and user information.
Mongoose: ODM library for MongoDB.
JWT (JSON Web Tokens): Used for secure user authentication.
Nodemailer: For sending emails related to event updates and notifications.
Swagger: API documentation.
dotenv: For managing environment variables.
