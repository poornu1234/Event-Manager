# Event Manager

## A Node.js application for managing events, scheduling, and attendee coordination.

## 🚀 Features
- Create and manage events with detailed information
- Track attendee registrations and RSVPs
- Handle event scheduling and calendar integration
- Real-time updates for event changes
- User authentication and authorization
- Event categories and tagging system
- Search and filter events
- Email notifications for event updates

- ## 📝 Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/) (v4.4 or higher)
- Modern web browser

- ## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/poornu1234/Event-Manager.git
   cd Event_Manager

2. Install dependencies:
   ```bash
   npm install

3. Create a `.env` file in the root directory and add your environment variables:

   ```env
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/event_manager
   JWT_SECRET=your_jwt_secret
   SMTP_HOST=your_smtp_host
   SMTP_PORT=587
   SMTP_USER=your_email
   SMTP_PASS=your_password
## 🚦 Running the Application

### Development Mode
   ```bash
   npm run dev


### Production Mode
   ```bash
npm run build
npm start

## 📚 API Documentation

### Authentication Endpoints
   ```plaintext
   POST /api/auth/register - Register new user
   POST /api/auth/login    - User login
   POST /api/auth/logout   - User logout

### Event Endpoints
   ```plaintext
   GET    /api/events       - Get all events
   GET    /api/events/:id   - Get specific event
   POST   /api/events       - Create new event
   PUT    /api/events/:id   - Update event
   DELETE /api/events/:id   - Delete event
### User Endpoints
GET /api/users/profile - Get user profile
PUT /api/users/profile - Update user profile
GET /api/users/events - Get user's events

## 🗂 Project Structure
Event_Manager/ ├── src/ │ ├── config/ │ ├── controllers/ │ ├── middleware/ │ ├── models/ │ ├── routes/ │ ├── services/ │ └── utils/ ├── tests/ ├── .env ├── .gitignore ├── package.json └── README.md

## 🧪 Testing

### Run the test suite:
   ```bash
   npm test
### Run tests with coverage:

  npm run test:coverage


