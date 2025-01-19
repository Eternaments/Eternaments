
Eternaments/
├── public/            # (static assets for the frontend)
├── src/               # Frontend source files
│   ├── components/    # Components to use
│   ├── pages/         # Page routes for the SPA
|   ├── config/        # Config files
|   ├── styles/        # SASS related files (maybe)
|   ├── hooks/         # React Hooks
│   ├── App.jsx        # Main React app entry point
│   └── main.jsx       # Vite's main entry point
├── server/            # Backend folder (Express and related files)
│   ├── models/        # MongoDB models (since we're using Mongoose)
│   ├── routes/        # API routes
│   ├── controllers/   # Controller logic
│   ├── index.js       # Entry point for Express server
│   └── .env           # Environment variables (optional)
├── package.json       # Root package.json for frontend dependencies
├── vite.config.js     # Vite configuration
└── README.md          # Project documentation
