# Weather-Search-iOS-app--Tomorrow.io

## Created an iOS App for retrieving and displaying weather details using the Tomorrow.io API.

## Tech Stack

**Frontend:** Swift, SwiftUI, UIKit

**Backend:** Node.js, Express, MongoDB (Atlas), Google App Engine

**Libraries & Frameworks:**
- SwiftyJSON: Handling JSON data
- Alamofire: Making HTTP requests
- Toast-Swift: Displaying toast messages
- SwiftSpinner: Loading spinner
- HighCharts: Implementing charts for data visualization

## APIs Used

1. **Tomorrow.io API** - Fetches real-time and forecast weather data.
2. **Google Places Autocomplete API** - Provides search suggestions for cities.
3. **Google Geocoding API** - Converts location names into latitude/longitude.
4. **MongoDB Atlas** - Stores user-favorited locations in a cloud database.
5. **Twitter (X) Share API** - Allows users to share weather updates on X (Twitter).

## Features

### 1. **User Location-Based Weather Search**
   - Automatically fetches weather data based on the user’s current location.
   - Uses Apple’s Core Location framework to determine the location.

### 2. **Search for Weather Details by City**
   - Implements a **UISearchBar** with autocomplete functionality.
   - Fetches weather data via Tomorrow.io API based on user input.
   - Displays search results in a table view.

### 3. **Weather Details View**
   - **Today Tab:** Displays current weather data including:
     - Temperature
     - Humidity
     - Wind Speed
     - Visibility
     - Pressure
   - **Weekly Tab:** Shows 7-day forecast with:
     - Date, sunrise/sunset times
     - Temperature trends using HighCharts area charts
   - **Weather Data Tab:** Includes:
     - Precipitation probability, humidity, cloud cover
     - Activity gauge charts using HighCharts

### 4. **Favorites List (MongoDB Integration)**
   - Allows users to save cities to a favorites list.
   - Implements persistent storage using **MongoDB Atlas (cloud database)**.
   - Supports removing cities from favorites and syncing data with the backend.

### 5. **Social Media Sharing**
   - Integrates **Twitter (X) sharing**.
   - Generates a tweet containing the weather details.

### 6. **Interactive UI**
   - Uses **SwiftUI** and **UIKit** for a smooth experience.
   - Includes dynamic loading spinners for API calls.
   - Displays error messages gracefully.

### 7. **Backend & Database Integration**
   - Uses a **Node.js backend** deployed on **Google App Engine (GAE)**.
   - Stores user-favorite locations in **MongoDB Atlas** for cross-device sync.
   - Communicates with the backend via **asynchronous HTTP requests**.
     
### 8. **View Demo**
- https://github.com/user-attachments/assets/28f4bd00-2a7c-4069-b43d-db6fbd9a5540
  
