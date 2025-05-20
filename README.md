
# ConcordiaStudyRoomBookings

A full-stack application to improve the study room booking system at Concordia University. Our goal is to create a more efficient and user-friendly interface while ensuring that reserved rooms are actually used.

## 🚀 Project Goals

- Prevent room hoarding by requiring check-in within 15 minutes of the booking start time.
- Automatically release rooms that go unused and make them available for others to book.
- Provide a clean, responsive, and mobile-friendly user interface.
- Create the potential for integration into the official Concordia mobile app or function as a standalone web app.

## 🛠️ Technologies Used

### Frontend
- **React** with **TypeScript** – for a fast, modular, and type-safe UI

### Backend
- **Spring Boot** – to develop a secure and scalable REST API

### Database
- **PostgreSQL** – to handle relational data such as users, rooms, and bookings

### Stretch Technologies (optional but desirable)
- **WebSockets** – for real-time updates
- **QR Code Scanning** – for on-site room check-in
- **Push Notifications** – to remind users of upcoming bookings or no-show releases
- **OAuth2 / SSO** – integration with student login systems

## 📌 Key Features

- Real-time room availability and booking
- Automatic room release after 15 minutes if no check-in occurs
- User authentication and secure session management
- Modern and intuitive booking interface
- Potential mobile app integration or PWA (Progressive Web App) support

## 🧩 Project Structure

ConcordiaStudyRoomBookings/
├── frontend/ # React + TypeScript code
├── backend/ # Spring Boot services and REST API
├── database/ # SQL schema and migration scripts
└── README.md


## 🗺️ Roadmap

### Phase 1: Planning & Setup
- [ ] Define user roles and user stories (e.g. student, admin)
- [ ] Sketch UI/UX mockups (e.g. Figma or Whimsical)
- [ ] Set up GitHub repo and basic folder structure
- [ ] Initialize frontend (React) and backend (Spring Boot)
- [ ] Design and implement PostgreSQL schema

### Phase 2: Backend Implementation
- [ ] Create endpoints for:
  - User registration/login
  - Viewing available rooms
  - Booking a room
  - Checking into a room
  - Auto-release of no-show bookings
- [ ] Enforce check-in within 15 minutes logic
- [ ] Write unit/integration tests

### Phase 3: Frontend Implementation
- [ ] Create responsive components for:
  - Room list and calendar view
  - Booking form
  - Check-in confirmation
  - User login and dashboard
- [ ] Connect frontend to backend via REST API
- [ ] Handle form validation, loading states, and error messages

### Phase 4: Integration & Testing
- [ ] End-to-end testing of booking and check-in workflows
- [ ] Add real-time updates for released rooms (polling or WebSocket)
- [ ] Improve UX through feedback and iteration

### Phase 5: Deployment & Final Touches
- [ ] Deploy backend (e.g. on Railway, Render, or Heroku)
- [ ] Deploy frontend (e.g. on Vercel or Netlify)
- [ ] Add environment variables and database hosting
- [ ] Final polish on UI/UX and mobile optimization

## 🔐 Authentication & Security (Optional)
- [ ] OAuth2 for Concordia login integration
- [ ] Session/token-based authentication
- [ ] Role-based access control for admin features

## 📱 Mobile App / Integration (Stretch Goal)
- [ ] PWA support for mobile usability
- [ ] Integration into Concordia’s existing app using APIs or iframe embedding

## 🤝 Contributing

If you're a Concordia student and want to contribute, feel free to open a pull request or contact us!
