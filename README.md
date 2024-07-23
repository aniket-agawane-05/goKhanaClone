# goKhanaClone

# project structure

my-react-native-app/
│
│
├─ src/
│ ├── components/ # Reusable UI components
│ │ ├── atoms/ # Small, reusable components (e.g., buttons, inputs)
│ │ ├── molecules/ # Composite components made of atoms (e.g., form groups, cards)
│ │ ├── organisms/ # More complex components made of molecules (e.g., entire forms, navbars)
│ │ ├── templates/ # Page-level layout components
│ │ └── screens/ # Complete pages/screens
│ │
│ ├── assets/ # Static assets like images, fonts, etc.
│ │
│ ├── hooks/ # Custom hooks
│ │
│ ├── navigation/ # Navigation setup
│ │
│ ├── constants/ # Constants like urls, json data etc
│ │
│ ├── contexts/ # Context API providers
│ │
│ ├── services/ # API services, utilities, etc.
│ │
│ ├── store/ # State management (e.g., Redux)
│ │
│ ├── utils/ # Utility functions
│ │
│ ├── App.js # Entry point of the app
│ └── index.js # App registration
│
├── .gitignore # Git ignore file
├── package.json # NPM package file
├── README.md # Project documentation
└── ...
