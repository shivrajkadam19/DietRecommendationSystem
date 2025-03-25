# FitLife - Personalized Diet & Workout Companion

FitLife is a personalized diet and workout recommendation app that helps users achieve their health and fitness goals. It uses AI to generate tailored recommendations based on users' dietary preferences, fitness goals, lifestyle factors, dietary restrictions, and health conditions.

## Visit the Application

You can visit the live application here: [FitLife - Personalized Diet & Workout Companion](https://fitlifeapp.netlify.app/)

## Features
- Personalized diet and workout plans using AI
- Interactive form for user input
- Display customized recommendations
- Download recommendations as a PDF
- Seamless navigation with React Router
- AI-powered recommendations using Gemini API

## Tech Stack
- **Frontend:** React + TypeScript + Vite + TailwindCSS
- **Backend:** Node.js + Express + Google Gemini AI API
- **State Management:** React Hooks
- **PDF Generation:** jsPDF

---

## Getting Started

### Prerequisites
Make sure you have the following installed:
- Node.js (v18 or higher)
- npm or yarn

### Clone the Repository
```bash
git clone https://github.com/yourusername/fitlife.git
cd fitlife
```

### Install Dependencies
```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

### Set Environment Variables
Create a `.env` file in the server directory with the following:
```env
PORT=5001
GEMINI_API_KEY=your_google_gemini_api_key
MODEL=gemini-2.0-flash
```

### Start the Application
#### Backend:
```bash
cd server
node server.js
```
#### Frontend:
```bash
cd client
npm run dev
```
The frontend will be available at `http://localhost:5173` and the backend at `http://localhost:5001`.

---

## Project Structure
```bash
FitLife/
├── client/               # Frontend Code (React + Vite)
│   ├── public/           # Static assets
│   ├── src/              # Source code
│   │   ├── App.tsx       # Main App component
│   │   ├── FormPage.tsx  # Form Component
│   │   ├── Recommendations.tsx # Display Recommendations
│   ├── vite.config.ts    # Vite Configuration
└── server/               # Backend Code (Node.js + Express)
    ├── server.js         # Express API Server
    ├── .env              # Environment Variables
    └── package.json      # Backend Dependencies
```

---

## API Endpoints
### POST /api/recommendations
- **Description:** Generate personalized recommendations using AI
- **Request Body:**
```json
{
  "dietary_preferences": "string",
  "fitness_goals": "string",
  "lifestyle_factors": "string",
  "dietary_restrictions": "string",
  "health_conditions": "string",
  "user_query": "string"
}
```
- **Response:**
```json
{
  "recommendations": {
    "diet_types": [],
    "workouts": [],
    "breakfasts": [],
    "lunches": [],
    "dinners": [],
    "additional_tips": []
  }
}
```

---

## Screenshots
### Home Page
![Home Page](screenshots/home.png)

### Form Page
![Form Page](screenshots/form.png)

### Recommendations Page
![Recommendations](screenshots/recommendations.png)

---

## Contributing
Feel free to submit a pull request or open an issue if you'd like to contribute!

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact
For any queries, reach out to [Shivraj Kadam](mailto:shivraj.kadam@example.com).

---

Happy coding! 🚀

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/shivrajkadam19/fitlife.git
   ```

2. Navigate to the project directory:
    ```sh
    cd fitlife
    ```

3. Install frontend and backend dependencies:
    ```sh
    cd client
    npm install

    cd ../server
    npm install
    ```

4. Set Environment Variables:
Create a `.env` file in the server directory with the following variables:
    ```env
    PORT=5001
    GEMINI_API_KEY=your_google_gemini_api_key
    MODEL=gemini-2.0-flash
    ```

5. Start the servers:
    ```sh
    # Start the backend
    cd server
    node server.js

    # Start the frontend
    cd ../client
    npm run dev
    ```

6. Open your browser and visit http://localhost:5173 to see the application.

## Usage

- Visit the homepage and learn about FitLife.
- Click on **Get Started** to access the form.
- Enter your dietary preferences, fitness goals, and other details.
- Submit the form to get personalized diet and workout recommendations.
- Download the recommendations as a PDF for easy reference.

## API Credits

This project uses the **Google Gemini AI API** to generate personalized recommendations. Ensure you have a valid API key from Google to run the backend services.

## Contact

If you have any questions or feedback, feel free to contact [Shivraj Kadam](mailto:shivraj.kadam@example.com).

**Thank you for using FitLife! If you find this project helpful, please consider giving it a star on GitHub.**




# FitLife - Personalized Diet & Workout Companion



## Features

- Personalized diet and workout plans using AI
- Interactive form for user input
- Display customized recommendations
- Download recommendations as a PDF
- Seamless navigation with React Router
- AI-powered recommendations using Gemini API

## Technologies Used

- **React.js**: Frontend development
- **Node.js**: Backend API
- **Express**: Server-side framework
- **Google Gemini AI API**: AI-powered recommendations
- **Vite**: Fast build tool
- **TailwindCSS**: For responsive styling
- **jsPDF**: PDF generation

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/shivrajkadam19/fitlife.git
   ```

2. Navigate to the project directory:
    ```sh
    cd fitlife
    ```

3. Install frontend and backend dependencies:
    ```sh
    cd client
    npm install

    cd ../server
    npm install
    ```

4. Set Environment Variables:
Create a `.env` file in the server directory with the following variables:
    ```env
    PORT=5001
    GEMINI_API_KEY=your_google_gemini_api_key
    MODEL=gemini-2.0-flash
    ```

5. Start the servers:
    ```sh
    # Start the backend
    cd server
    node server.js

    # Start the frontend
    cd ../client
    npm run dev
    ```

6. Open your browser and visit http://localhost:5173 to see the application.

## Usage

- Visit the homepage and learn about FitLife.
- Click on **Get Started** to access the form.
- Enter your dietary preferences, fitness goals, and other details.
- Submit the form to get personalized diet and workout recommendations.
- Download the recommendations as a PDF for easy reference.

## API Credits

This project uses the **Google Gemini AI API** to generate personalized recommendations. Ensure you have a valid API key from Google to run the backend services.

## Contact

If you have any questions or feedback, feel free to contact [Shivraj Kadam](mailto:shivraj.kadam@example.com).

**Thank you for using FitLife! If you find this project helpful, please consider giving it a star on GitHub.**

