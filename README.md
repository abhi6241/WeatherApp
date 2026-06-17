# 🌤️ Modern Weather App

A sleek, responsive, and interactive weather application built with vanilla web technologies. This app fetches and displays real-time weather data for any city across the globe using the OpenWeatherMap API, wrapped in a modern "glassmorphism" user interface.

## ✨ Features

* **Real-Time Data:** Fetches current temperature, humidity levels, and weather descriptions.
* **Dynamic Emojis:** Visually represents current weather conditions (e.g., clear skies, rain, snow) with responsive emojis.
* **Modern UI/UX:** Features a beautiful, frosted-glass (glassmorphism) design with smooth hover states and input focus effects.
* **Smooth Animations:** The weather card smoothly glides and fades into view upon loading data.
* **Fully Responsive:** Adapts seamlessly to all screen sizes, from large desktop monitors to mobile phones.
* **Error Handling:** Gracefully alerts the user if a city is not found or if the input is left blank.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure.
* **CSS3:** Flexbox, CSS Animations (`@keyframes`), Media Queries, and Glassmorphism techniques (`backdrop-filter`).
* **JavaScript (ES6+):** DOM manipulation, Event Listeners, and asynchronous API requests using `async/await` and the `Fetch` API.
* **OpenWeatherMap API:** RESTful API used to retrieve global weather data.

## 🚀 Getting Started

### Prerequisites

You do not need any build tools or frameworks to run this project. A modern web browser is all that is required.

### Installation & Setup

1. **Download or Clone the Repository:**
   Download the project files to your local machine.
2. **Obtain an API Key:**
   * Go to [OpenWeatherMap](https://openweathermap.org/) and create a free account.
   * Generate an API key.
   * Open `index.js` and replace the placeholder API key with your own:
     `const apiKey = "YOUR_WEATHER_API_KEY";`
3. **Run the App:**
   Simply open the `index.html` file in any web browser to start using the application. No local server is strictly required, though you can use tools like VS Code's "Live Server" extension for a better development experience.

## 📁 Project Structure

📦 weather-app
 ┣ 📜 index.html    # The main HTML document
 ┣ 📜 index.css     # Styling, layouts, animations, and media queries
 ┗ 📜 index.js      # App logic and API integration

## 🤝 Acknowledgments

* Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
