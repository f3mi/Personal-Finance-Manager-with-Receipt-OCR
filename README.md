# Personal Finance Manager with Receipt OCR

A cross-platform finance management application with receipt scanning capabilities, expense categorization, and comprehensive budget visualization.

## Features

### Mobile App (Flutter)
- Receipt scanning with OCR
- Automatic expense categorization
- Offline-capable expense tracking
- User-friendly interface with dark/light mode

### Web Portal
- Interactive dashboard with spending visualizations
- Budget management and savings goals
- Detailed financial reports and exports
- Account settings and preferences

## Technology Stack

- **Mobile**: Flutter, Dart, ML Kit/Google Cloud Vision for OCR
- **Web Frontend**: React.js, Chart.js
- **Backend**: Node.js with Express (or Firebase)
- **Database**: MongoDB/PostgreSQL
- **Authentication**: Firebase Auth/JWT
- **Cloud Storage**: Firebase Storage/AWS S3
- **Deployment**: Firebase Hosting, Google Cloud/AWS

## Project Setup

### Prerequisites
- Flutter SDK (latest stable)
- Node.js (v14 or higher)
- npm or yarn
- Git

### Mobile App Setup
1. Clone the repository
   ```
   git clone https://github.com/yourusername/personal-finance-manager.git
   cd personal-finance-manager/mobile
   ```

2. Install dependencies
   ```
   flutter pub get
   ```

3. Run the app
   ```
   flutter run
   ```

### Web Portal Setup
1. Navigate to the web directory
   ```
   cd ../web
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Start development server
   ```
   npm start
   ```

### Backend Setup
1. Navigate to the backend directory
   ```
   cd ../backend
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Set up environment variables
   ```
   cp .env.example .env
   ```
   Then edit the `.env` file with your configuration

4. Start the server
   ```
   npm start
   ```

## Project Structure

```
personal-finance-manager/
├── mobile/                # Flutter mobile application
│   ├── lib/
│   │   ├── api/           # API services
│   │   ├── models/        # Data models
│   │   ├── screens/       # UI screens
│   │   ├── utils/         # Utilities and helpers
│   │   └── widgets/       # Reusable widgets
│   └── assets/            # Images, fonts, etc.
├── web/                   # React web application
│   ├── public/
│   └── src/
│       ├── components/    # React components
│       ├── pages/         # Page layouts
│       ├── services/      # API services
│       └── utils/         # Utility functions
├── backend/               # Node.js backend
│   ├── controllers/       # API controllers
│   ├── models/            # Database models
│   ├── routes/            # API routes
│   └── services/          # Business logic
└── docs/                  # Documentation
    └── api/               # API documentation
```

## Development Guidelines

### Code Style
- Follow Flutter/Dart style guide for mobile development
- Use ESLint/Prettier for JavaScript/TypeScript code
- Use meaningful variable and function names
- Comment complex logic

### Git Workflow
- Use feature branches (`feature/feature-name`)
- Create pull requests for code review
- Squash commits when merging to main branch

### Testing
- Write unit tests for all business logic
- Create widget tests for UI components
- Implement integration tests for critical user flows

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributors
- [Your Name](https://github.com/yourusername) 