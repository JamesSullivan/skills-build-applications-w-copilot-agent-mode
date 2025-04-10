# OctoFit Tracker

## Overview
OctoFit Tracker is a fitness tracking application built with React. It allows users to log their activities, manage teams, view leaderboards, and access personalized workout suggestions.

## Project Structure
The project is organized as follows:

```
octofit-tracker
└── frontend
    ├── node_modules        # Contains all the installed npm packages
    ├── public              # Static files for the application
    ├── src                 # Source code for the React application
    │   ├── components       # Contains all the React components
    │   │   ├── Activities.js
    │   │   ├── Leaderboard.js
    │   │   ├── Teams.js
    │   │   ├── Users.js
    │   │   └── Workouts.js
    │   ├── App.css         # CSS styles for the main application
    │   ├── App.js          # Main component with routing and layout
    │   ├── index.css       # Global CSS styles
    │   └── index.js        # Entry point of the application
    ├── package.json        # npm configuration file
    └── README.md           # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd octofit-tracker/frontend
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the application:**
   ```
   npm start
   ```

4. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`.

## Usage
- **Activities:** Manage and log your fitness activities.
- **Leaderboard:** View the competitive leaderboard among users.
- **Teams:** Create and manage teams for group activities.
- **Users:** Handle user profiles and authentication.
- **Workouts:** Access personalized workout suggestions.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License.