# User Notification Preferences API

This project is a serverless API built using **Nest.js** and **MongoDB** to manage user notification preferences and simulate sending notifications. The API supports CRUD operations for user preferences, logging notification activities, and providing basic statistics.

---

## Features
- **User Preferences Management**: Create, read, update, and delete user notification preferences.
- **Notification Simulation**: Simulate sending notifications to users through different channels (Email, SMS, Push).
- **Logging & Statistics**: Logs all notifications and provides insights into their statuses.
- **Validation**: Enforces data integrity with `class-validator`.
- **Rate Limiting**: Limits the number of requests to prevent abuse.
- **Swagger Documentation**: API documentation is available for easy exploration.
- **Serverless Ready**: Deployable on platforms like AWS Lambda or Vercel.

---

## Prerequisites
- **Node.js** (v16 or above)
- **npm** or **yarn**
- **MongoDB** (local or cloud, e.g., MongoDB Atlas)

---

## Installation

1. **Clone the repository**:
   git clone <repository-url>
   cd user-notification-preferences-api
   
2. Install dependencies:
  npm install

3. Set up environment variables:
  PORT=3000
  MONGO_URI=mongodb://localhost:27017/notification-preferences

4. Run the project:
  npm run start:dev

  
