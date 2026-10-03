# SkillSwap - Combined Phase 1 + Phase 2 + Phase 3

This ZIP contains the complete SkillSwap project in one folder.

## Phase 1
- Registration and login
- JWT authentication
- Student profiles
- Teaching and learning skills
- Student search
- Skill exchange requests
- Accept/reject requests
- REST APIs
- Local JSON storage

## Phase 2
- Dashboard
- Search filters
- Availability
- Session scheduling
- Session status
- Ratings and reviews API
- Notifications
- Admin dashboard
- Admin statistics
- Admin users
- Role-based admin authorization

## Phase 3
- Real-time chat with Socket.IO
- Direct student-to-student messaging
- Chat history
- Typing indicator
- Real-time notifications through Socket.IO

## Requirements
- Node.js 18 or newer
- VS Code

MongoDB is NOT required.

## Run the backend

Open VS Code Terminal 1:

```bash
cd server
npm install
npm run dev
```

You should see:

```text
SkillSwap Phase 3 API running at http://localhost:5000
```

## Run the frontend

Open VS Code Terminal 2:

```bash
cd client
npm install
npm run dev
```

The browser should open automatically at:

```text
http://localhost:5173
```

If it does not, open that address manually in Chrome or Edge.

## Admin testing

1. Register a normal account.
2. Stop the backend with Ctrl+C.
3. Open:

```text
server/data/users.json
```

4. Find your user.
5. Change:

```json
"role": "student"
```

to:

```json
"role": "admin"
```

6. Restart the backend.
7. Log in again.
8. The Admin link will appear.

## Important

The project intentionally uses local JSON files so you can develop without MongoDB or Atlas.

For a production deployment, replace the JSON data layer with PostgreSQL or MongoDB and use environment variables for secrets.

## Portfolio / interview talking points

You can explain that the project demonstrates:
- React frontend
- Node.js and Express REST APIs
- JWT authentication
- Password hashing
- Role-based authorization
- CRUD operations
- Search and filtering
- Scheduling workflow
- Notifications
- Socket.IO real-time communication
- Local persistence
- Responsive UI


## If you see "Registration failed"

Make sure the backend terminal is running:

```bash
cd server
npm install
npm run dev
```

The project includes a local `server/.env` with a JWT secret, so registration works without MongoDB or Atlas.

If you changed the `.env`, restart the backend after saving it.

If you already registered the same email, the app will show `Email already registered`; use Login instead.
