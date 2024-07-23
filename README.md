# Code Brawl Frontend

## Description
Code Brawl is a multiplayer typing game where players type random code snippets from various programming languages. The game increases in difficulty as players score higher. It includes a leaderboard to track top players.

## Tech Stack
- React
- Vite (for development and build)
- Socket.io (for real-time communication)
- Redux (for state management, optional)

## Project Setup

### Prerequisites
- Node.js (version 14 or higher)
- npm (version 6 or higher)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/code-typer-frontend.git
    cd code-typer-frontend
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

### Running the Application

1. Start the development server:
    ```sh
    npm run dev
    ```

2. Open your browser and navigate to `http://localhost:5173`.

### Project Structure

```plaintext
src/
├── components/          # Reusable components
├── pages/               # Page components
├── services/            # API and other service calls
├── utils/               # Utility functions
├── App.jsx              # Main application component
├── main.jsx             # Entry point
└── ...                  # Other files as needed
