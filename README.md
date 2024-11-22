# tinybudget
A simple budget app made for me to track monthly expenses and learning about React

### Tech
React+Vite using other plugins such as tailwind, and PostCSS

### Folder Structure
```
src/
├── assets/
│   ├── images/        # Static images (e.g., logos, icons)
│   ├── fonts/         # Custom fonts
│   └── styles/        # Global styles (CSS, SASS, Tailwind configs, etc.)
│       ├── index.css  # Global CSS or base styles
│       ├── variables.css # CSS variables or design tokens
│       └── reset.css  # CSS resets
│
├── components/
│   ├── common/        # Reusable components (buttons, modals, etc.)
│   │   ├── Button.jsx
│   │   ├── Modal.jsx
│   │   └── Input.jsx
│   ├── layout/        # Layout-specific components (headers, footers)
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   └── Sidebar.jsx
│   └── specific/      # Feature-specific components
│       ├── DashboardCard.jsx
│       └── Chart.jsx
│
├── context/           # Context API files for global state
│   ├── ThemeContext.js
│   └── UserContext.js
│
├── hooks/             # Custom hooks
│   ├── useFetch.js
│   └── useAuth.js
│
├── pages/             # Page-level components (corresponds to routes)
│   ├── Home.jsx
│   ├── About.jsx
│   ├── Dashboard.jsx
│   └── NotFound.jsx
│
├── services/          # API calls or service logic
│   ├── api.js         # Centralized API functions
│   ├── authService.js # Authentication-related functions
│   └── dataService.js # Data-related functions
│
├── utils/             # Helper functions and utilities
│   ├── constants.js   # Application constants
│   ├── helpers.js     # Generic helper functions
│   ├── validators.js  # Form validators or custom logic
│   └── logger.js      # Custom logging functions
│
├── App.jsx            # Main application component
├── main.jsx           # Entry point (for Vite, analogous to index.js)
├── routes/            # Application routing logic
│   ├── index.js       # Centralized routes definition
│   └── ProtectedRoute.jsx # Wrapper for protected routes
│
└── index.html         # Main HTML template (used by Vite)
```
