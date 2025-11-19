# Weather App 
𝔟𝔶: 𝔊𝔦𝔬𝔳𝔞𝔫𝔦 𝔖𝔞𝔩𝔳𝔞𝔡𝔬𝔯

**Weather App** is a clean and simple web application built with **React.js**, **Styled Components** and **Axios**, which consumes the public API provided by [OpenWeatherMap](https://openweathermap.org) to display current weather information and a short forecast for any searched location.

➡️ [Live Demo](https://weather-app-ashy-eta.vercel.app) *(Deployed via Vercel)*

---

## On This Project

- Demonstrates a solid grasp of frontend fundamentals in React including **state management**, **API integration**, and **component-based architecture**.  
- Showcases styling with Styled Components for modular, reusable CSS-in-JS.  
- Highlights experience working with asynchronous calls (via Axios), error handling, and dynamic user input.  
- Serves as a portfolio piece for a front-end developer position — clean, focused, and user-centric.

---

## Technologies & Tools

- **React.js** – Front-end UI library  
- **Styled Components** – CSS-in-JS for styled React components  
- **Axios** – Promise-based HTTP client  
- **OpenWeatherMap API** – Weather data provider  
- **Vercel** – Hosting and continuous deployment  
- **Git & GitHub** – Version control and collaboration  
- **ESLint / Prettier**  – Code quality & formatting  

---

## Features

- Search input for cities (by name) to fetch current weather + forecast  
- Display of weather conditions: temperature, humidity, wind, iconography  
- Responsive layout: optimized for desktop and mobile  
- Error handling: e.g., invalid city name or API failure  
- Modular component structure for future scalability  
- Environment variables for API keys (kept out of source control)  

---

## Getting Started (Local Setup)

1. Clone the repository:  
   ```bash
   git clone https://github.com/GioSalvador/weather-app.git
   cd weather-app
   
2. Install dependencies: 
   ```bash
   npm install
   
3. Create a .env.local file (at the project root) and add your OpenWeatherMap API key: 
   ```bash
   REACT_APP_WEATHER_API_KEY=YOUR_API_KEY_HERE   
   
4. Start the development server: 
   ```bash
   npm start  
   
5. Open http://localhost:3000 in your browser to view the app.

## What I Learned

- How to structure React projects for maintainability and separation of concerns 
- Integrating and handling asynchronous API calls using Axios and React hooks  
- Managing API keys securely with environment variables  
- Creating responsive UI components with Styled Components  
- Debugging UI issues, handling edge-cases like no results or API errors
- Deploying a React application with continuous deployment via Vercel  

## Future Enhancements

- Dynamic Thematic UI: transform the entire interface based on the current weather, a sunny city will feature bright skies and warm tones, cloudy conditions will bring softer gradients, and rainy weather will include subtle rain animations for a more immersive experience. 
- Geolocation Detection: automatically identify the user’s location and show local weather instantly. 
- Unit Switching: allow users to toggle between Celsius and Fahrenheit.  
- Automated Testing: integrate Jest and React Testing Library for unit and integration tests.  

Feel free to check out my GitHub profile @GioSalvador for more projects.
I’m open to connect on [LinkedIn](https://www.linkedin.com/in/giovani-salvador/) or via E-mail: gsalvador9817@gmail.com to discuss collaborations or job opportunities.

Thank you for visiting my portfolio project!
   
