# 🌦️ Weather React App

A simple and interactive weather application built using React.js that allows users to fetch real-time weather data for any city using an external weather API.

---

## 🚀 Project Overview

This project is a frontend-based weather application where users can:

* Search for any city
* View real-time weather data
* See temperature, humidity, and weather conditions

The application fetches live data from a weather API and dynamically updates the UI.

Weather apps like this typically use APIs such as OpenWeatherMap to fetch real-time data. ([GeeksforGeeks][1])

---

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript (ES6)
* HTML5
* CSS3

### Libraries / Tools

* Axios or Fetch API (for API calls)
* React Scripts
* Node.js & npm

### API Used

* OpenWeatherMap API (or similar weather API)

---

## 📁 Project Structure

```
weather-react/
│── public/
│── src/
│   ├── components/
│   │   └── Weather.js
│   ├── App.js
│   ├── index.js
│   ├── App.css
│── package.json
│── README.md
```

---

## ⚙️ Features

* 🌍 Search weather by city name
* 🌡️ Display temperature in Celsius
* 💧 Shows humidity and weather conditions
* ⚡ Real-time API data fetching
* ❌ Error handling for invalid city or API issues

---

## 🔑 Environment Setup

To run this project, you need an API key.

1. Create an account on OpenWeatherMap
2. Generate an API key
3. Add it in your project:

```
const API_KEY = "your_api_key_here";
```

⚠️ Important: Do NOT push your API key to GitHub. Use `.env` file instead.

---

## 🧑‍💻 Installation & Setup

### 1. Clone the Repository

```
git clone https://github.com/PriyeshPandey07/weather-react.git
cd weather-react
```

### 2. Install Dependencies

```
npm install
```

### 3. Start the Application

```
npm start
```

App will run on:

```
http://localhost:3000
```

---

## 🚀 Deployment

You can deploy this project using:

### 🔹 Netlify

* Push code to GitHub
* Connect repo to Netlify
* Deploy automatically

### 🔹 Vercel

* Import GitHub repo
* Click deploy

### 🔹 AWS EC2 (Advanced - DevOps Way)

1. Launch EC2 instance
2. Install Node.js
3. Clone repo
4. Run:

```
npm install
npm run build
serve -s build
```

---

## 🧪 Common Issues & Fixes

### ❌ Error: Invalid API Key

* Make sure API key is correct
* Check API activation status

### ❌ react-scripts not found

```
npm install react-scripts
```

### ❌ Git asking for username/password

Use Personal Access Token instead of password.

---

## 📸 Future Improvements

* 🌤️ Add 5-day forecast
* 📍 Detect user location
* 🎨 Improve UI/UX
* 📱 Make fully responsive

---

## 🤝 Contributing

Feel free to fork this repo and contribute!

---

## 📜 License

This project is open-source and free to use.

---

## 👨‍💻 Author

**TylerPottsDev**

[1]: https://www.geeksforgeeks.org/reactjs/weather-application-using-reactjs/?utm_source=chatgpt.com "Weather Application using ReactJS - GeeksforGeeks"
