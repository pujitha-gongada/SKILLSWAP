 SkillSwap – Full Stack Skill Exchange Platform

SkillSwap is a full-stack web application that helps students connect with each other to exchange skills. 
Users can create profiles, list the skills they can teach and want to learn, find suitable peers, 
send skill exchange requests, schedule learning sessions, communicate through real-time chat, 
and provide ratings and reviews.

 Objectives

- Enable students to create profiles and manage their skills.
- Help users discover and connect with peers based on skills they want to learn or teach.
- Allow users to send, accept, and manage skill exchange requests.
- Provide session scheduling and management for learning activities.
- Enable real-time communication and notifications between users.
- Provide administration and feedback management through an admin dashboard.

 Key Features

1. User Authentication
- User registration and login
- JWT-based authentication
- Secure password hashing
- Role-based access for students and administrators

 2. User Profiles
- Create and update user profiles
- Add skills to teach
- Add skills to learn
- Manage availability information

 3. Skill Discovery
- Search for other users
- Filter users based on skills
- Find potential skill exchange partners

 4. Skill Exchange Requests
- Send skill exchange requests
- Accept or reject requests
- Track request status

 5. Session Management
- Schedule learning sessions
- View upcoming sessions
- Manage session status

 6. Real-Time Chat
- One-to-one messaging
- Real-time message delivery
- Chat history
- Typing indicator

7. Notifications
- Request notifications
- Session notifications
- Real-time chat notifications
- Activity updates

 8. Ratings & Reviews
- Rate completed learning interactions
- Add reviews
- View user feedback

 9. Admin Dashboard
- View platform statistics
- Manage users
- Role-based admin access
- Monitor platform activity

Technology Stack

 Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- React Router
- Axios
- Socket.IO Client
- Vite

Backend
- Node.js
- Express.js
- REST APIs
- Socket.IO
- JWT Authentication
- bcryptjs

 Database / Storage
- Local JSON-based storage

Development Tools
- VS Code
- npm
- Git
- GitHub

 System Architecture

```text
User
  ↓
React.js Frontend
  ↓
REST APIs / Socket.IO
  ↓
Node.js + Express.js Backend
  ↓
Authentication & Business Logic
  ↓
JSON Data Storage
