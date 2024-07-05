# Weather Application

This Weather Application is built using React with Vite, providing a fast and efficient development experience. It has features such as **user registration, login, and the ability to view and log live weather data based on city** . The application ensures a seamless user experience with persistent sessions and protected routes.

## Features

- **User Management(Register and Login)**: Securely register and LogIn users. User data is stored using a JSON server.
- **Live weather data**: Fetch and display weather data for various locations using third party API openweather.
  - It will Log these 5 details: **City, Temperature, Pressure, Humidity, Wind Speed and Wind Degree**
  - And auto-retrieve data after every 2 seconds
- **Persistent User Sessions**: User sessions are maintained even after the page is refreshed, ensuring a seamless experience.
- **Protected Routes**: Some routes are accessible only to authenticated users, enhancing the application's security.

## Components

- `Login`: Handles user login, including input validation and error handling.
- `Register`: Manages user registration.
- `Weather`: Displays weather data for the user's searched location.
- `ProtectedRoute`: Guards certain routes to ensure they are accessible only to authenticated users.

## Prerequisites

- Node.js
- npm

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Rohitpal0123/weatherApp
   ```
2. Navigate to the project directory:
   ```bash
   cd weatherApp
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Running the Project

This project uses the `concurrently` library to run both the React application and the JSON server simultaneously. To start the application, execute:

```bash
npm run dev
```

This command starts the JSON server on port 3000 and the React application. If the JSON server starts on a different port, please update the fetch URLs in the application accordingly.

## Usage

- **Registration**: Navigate to the registration page to create a new user account.
- **Login**: Log in using your registered credentials to access the weather data.
- **View Weather**: Once logged in, you can view the weather data for your current location or search for other locations.

## Screenshots

- **Login Page**
<img width="1470" alt="Screenshot 2024-07-06 at 1 06 11 AM" src="https://github.com/Rohitpal0123/weatherApp/assets/73094806/c61f0cf8-0961-44e7-8652-51b8e795ce48">

  
- **Registration Page**
<img width="1470" alt="Screenshot 2024-07-06 at 1 07 09 AM" src="https://github.com/Rohitpal0123/weatherApp/assets/73094806/ec735ee0-b1c5-41c7-a0df-acb5cc9ad330">


- **Weather App Home Page**
<img width="1470" alt="Screenshot 2024-07-06 at 1 09 19 AM" src="https://github.com/Rohitpal0123/weatherApp/assets/73094806/e5a5dc60-c1e4-496b-af8b-354383d6ee21">
