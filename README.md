# FitLife

A web application built with React and Firebase for gym membership registration and trainer management.

## About

FitLife connects fitness enthusiasts with gyms and personal trainers. Users can register for gym memberships and book training sessions, while trainers manage their schedules and clients.

## Features

- User registration and authentication
- Gym membership registration
- Browse and book personal trainers
- Trainer dashboard for client and schedule management
- Real-time database synchronization

## Technologies

- **Frontend**: React
- **Database**: Firebase Firestore (NoSQL)
- **Authentication**: Firebase Auth

## Getting Started

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/fitlife.git
cd fitlife
```

2. Install dependencies
```bash
npm install
```

3. Create `.env` file and add Firebase credentials:
```
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

4. Run the application
```bash
npm start
```

## Purpose

Built as a learning project to practice React development and Firebase integration.

## License

MIT License
