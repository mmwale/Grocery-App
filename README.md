# Grocery-App
An application for smart shopping 🛒. Features budget tracking, store locator, real-time deals, and healthy options. Built with React Native + Node.js + PostgreSQL.

## Features  
- **Smart Shopping Lists**: Create, edit, and categorize items with cost estimation.  
- **Budget Tracker**: Set spending limits and get real-time alerts.  
- **Store Locator**: Find nearby grocery stores using Google Maps.  
- **Deals & Discounts**: Get notified about sales at your favorite stores.  
- **Healthy Options**: Dedicated section for nutritious choices.  
- **Offline Mode**: Access your lists without internet.

## Tech Stack  
| **Area**       | **Technology**                          |  
|----------------|----------------------------------------|  
| Frontend       | React Native (TypeScript)              |  
| Backend        | Node.js + Express.js                   |  
| Database       | PostgreSQL                             |  
| Authentication | Firebase Auth                          |  
| Maps           | Google Maps API                        |  
| State Management | Redux Toolkit                        |  
| Testing        | Jest + Detox                          |  

## Getting Started  
### Prerequisites  
- Node.js (v18+)  
- PostgreSQL (v15+)  
- Expo CLI (for mobile testing)

### Installation  
1. Clone the repo
2. Set up the backend:
   cd server  
npm install  
cp .env.example .env  # Add your credentials  
npm run dev 
3. Set up the frontend:
cd ../client  
npm install  
expo start  

Project Structure

grocery-app/
├── client/                  # Frontend (React Native)
│   ├── assets/              # Images, fonts, etc.
│   ├── components/          # Reusable UI components
│   ├── screens/             # App screens (Home, Shopping List, Budget, etc.)
│   ├── navigation/          # Routing (React Navigation)
│   ├── context/             # State management (Redux/Context API)
│   ├── services/            # API calls (Axios/Fetch)
│   └── App.js               # Main entry point
│
├── server/                  # Backend (Node.js + Express)
│   ├── controllers/         # Business logic
│   ├── models/              # Database models (PostgreSQL/MongoDB)
│   ├── routes/              # API endpoints
│   ├── middleware/          # Auth, error handling
│   └── server.js            # Server entry point
│
├── database/                # Database scripts/SQL files (if using PostgreSQL)
│
├── docs/                    # Project documentation
│   ├── API.md               # API endpoints
│   └── DESIGN.md            # UI mockups (Figma links)
│
├── .gitignore              # Ignore node_modules, .env, etc.
├── README.md               # Project overview + setup instructions
└── package.json            # Shared scripts (e.g., `npm run dev`)

How to Contribute
1.Fork the repository.
2.Create a feature branch (git checkout -b feature/your-feature).
3.Commit changes (git commit -m 'Add amazing feature').
4.Push to the branch (git push origin feature/your-feature).
5.Open a Pull Request.


License
MIT © 2024
