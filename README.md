Live URL:  https://aminbiography.github.io/weather-app/


Here’s a clean, professional **`README.md`** you can include for your project.
It explains what the app does, how to use it, and how developers can improve or extend it 

---

# Weather App by aminbiography

A **modern, responsive weather web app** built using **HTML, CSS, and Vanilla JavaScript**, powered by the [Open-Meteo API](https://open-meteo.com/).
Users can search for any city or use their current geolocation to view current weather and a 7-day forecast — all without requiring an API key.

---

## Features

* **Live weather search** by city name
* **Auto-suggestions** while typing (powered by Open-Meteo Geocoding API)
* **Use My Location** button — fetches weather based on user’s GPS
* **Dynamic 7-day forecast** including temperature highs, lows, and precipitation
* **Responsive design** that adapts from desktop to mobile
* **“Refresh” button** to quickly reset and perform new searches
* **Clean UI** with animated loading indicator

---

## Demo

You can open `index.html` directly in your browser — no build step or server required.
Alternatively, host it using GitHub Pages or Netlify for public access.

---

## Technologies Used

| Technology           | Purpose                                      |
| -------------------- | -------------------------------------------- |
| **HTML5**            | Markup structure                             |
| **CSS3**             | Styling and responsive layout                |
| **JavaScript (ES6)** | App logic, API calls, and DOM manipulation   |
| **Open-Meteo API**   | Fetch real-time weather and geolocation data |

---

## How It Works

1. User types a city name → suggestions appear from the Open-Meteo Geocoding API.
2. On selecting a city or clicking **Search**, the app fetches weather data for that location.
3. The app displays:

   * Current temperature and wind speed
   * A daily forecast with max/min temperatures and precipitation
4. The **“Use My Location”** button gets weather based on device coordinates.
5. The **“Refresh”** button clears everything for a new search.

---

## Responsive Design

* The `.forecast` section uses a flexible `flex-wrap` layout.
* On screens smaller than 480px, each forecast card (`.day`) expands to 100% width — showing **one forecast per row** for readability.

---

## How Developers Can Improve This Project

Here are several ideas to enhance or expand the project:

### **1. Add Weather Icons**

Integrate weather condition icons from [Open-Meteo’s icon set](https://open-meteo.com/en/docs#weathervariables) or use a free library like [Weather Icons](https://erikflowers.github.io/weather-icons/).

### **2. Add Dark/Light Mode Toggle**

Allow users to switch between dark and light themes with a simple toggle, saving their preference in `localStorage`.

### **3. Multi-Language Support**

Translate labels, buttons, and forecasts using the Open-Meteo API’s `language` parameter.

### **4. Add More Data**

Include humidity, sunrise/sunset times, UV index, or hourly forecasts.

### **5. Map Integration**

Display the searched city on a small embedded map using [Leaflet.js](https://leafletjs.com/).

### **6. Cache or Save Last Search**

Use `localStorage` to remember the last searched city and auto-load it when the app opens again.

### **7. Error Handling & Offline Mode**

Improve user experience by handling API failures gracefully and caching data with a service worker (PWA).

### **8. Code Optimization**

* Extract inline CSS into a separate stylesheet.
* Modularize JavaScript into multiple files.
* Add ES module imports for better scalability.

---

## Example API Calls

**Geocoding API:**

```js
https://geocoding-api.open-meteo.com/v1/search?name=London&count=5&language=en
```

**Weather API:**

```js
https://api.open-meteo.com/v1/forecast?latitude=51.5072&longitude=-0.1276&current_weather=true&daily=temperature_2m_max,temperature_2m_min,precipitation_sum&timezone=auto
```

---

## Setup & Usage

1. **Clone the repo**

   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. **Open the app**

   * Just double-click `index.html`, or
   * Run a local server (optional):

     ```bash
     npx serve
     ```

3. **Search a city** or click “Use My Location” to view results.

---

## Author

**Developed by [Mohammad Aminul Islam (Amein)](https://github.com/aminbiography)**
- *Web Developer*
- *Cyber Threat Intelligence Associate*

---

Would you like me to integrate this author block **into the full README.md** (so it’s ready to upload directly to your repository)?
I can polish the formatting, emojis, and add a footer credit section to make it look like a professional open-source project.


---

## License

This project is released under the **MIT License** — feel free to use and modify it for your own projects.

----

---

Would you like me to **add code examples and screenshots** (in Markdown format) so your README looks even more polished for GitHub or portfolio use?

