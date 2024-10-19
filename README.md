# Weather Forecast App using MERN Stack

This project is a **simple weather application** built using **React.js** for the frontend and **Node.js** with **Express.js** for the backend. It allows users to check the **current weather** and **forecast** for a specific city. The backend retrieves weather data from the **OpenWeatherMap API** and stores it in a **MongoDB database**, while the frontend displays the information in a **user-friendly interface**.

---

## Features
- Search for **current weather** and **forecast** by city name.
- **Store weather data** in MongoDB for easy retrieval.
- **Responsive UI** built with React.js.
- Real-time data fetching from **OpenWeatherMap API**.

---

## Prerequisites
- **Node.js** installed (for backend setup)
- **React.js** installed (for frontend)
- **MongoDB** (local or cloud instance like MongoDB Atlas)
- **OpenWeatherMap API Key** (get one [here](https://openweathermap.org/api))

---
## Project Flow
1. **Frontend:** User enters a city name and clicks the **Get Weather** button. The frontend sends a request to the backend to fetch weather data.
2. **Backend:** Retrieves weather information from **OpenWeatherMap API** and stores it in the **MongoDB database**.
3. **Frontend:** Displays the weather data in a **user-friendly interface**.

## How to Run the Project Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/deepak2875/my_weather_application.git
   ```

2. Set up and run the **backend**:
   ```bash
   cd server
   npm install
   node index.js
   ```

3. Set up and run the **frontend**:
   ```bash
   cd client
   npm install
   npm start
   ```

---

## Conclusion
This **Weather Forecast App** demonstrates how to build a full-stack web application using the **MERN stack**, integrating a third-party API and MongoDB to create a responsive and dynamic user experience.

---
