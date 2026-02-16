# BioHelix Desktop

## System Architecture

BioHelix Desktop utilizes a client-server architecture to manage data flow efficiently between the client UI and the backend services. The client application is built using Electron, allowing for a cross-platform experience. The backend API is developed using Node.js and Express, which communicates with a MongoDB database to store user data and application state. The architecture is designed for scalability and ease of maintenance.

### Components:
1. **Client (Electron):** Provides a user-friendly interface that runs on all major operating systems.
2. **Server (Node.js/Express):** Handles requests, processes data, and interacts with the database.
3. **Database (MongoDB):** Stores user information and application-related data.
4. **Communication Protocol:** RESTful APIs manage the data exchange between the client and server.

## Features
- **Cross-Platform Compatibility:** Works on Windows, macOS, and Linux.
- **User Authentication:** Secure login system for user management.
- **Data Visualization:** Interactive charts and graphs to represent data analysis results.
- **Modular Architecture:** Easily extensible with plugins and additional features.
- **Real-Time Updates:** Automatic notifications for new data or events.

## Installation Instructions
### Prerequisites
- Node.js (v12 or later)
- npm (Node package manager)
- MongoDB (for local development)

### Steps:
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/kyleodinsen-beep/biohelix-desktop.git
   ```
2. **Change directory:**  
   ```bash
   cd biohelix-desktop
   ```
3. **Install dependencies:**  
   ```bash
   npm install
   ```
4. **Set up the database:**  
   Start MongoDB and create a database for the application.
5. **Run the application:**  
   ```bash
   npm start
   ```

## Usage Guide
1. **Launching the App:** After installation, run the command `npm start` to launch the application.
2. **User Registration:** Create an account by filling out the registration form.
3. **Logging In:** Use your credentials to log in to the application.
4. **Navigating the Interface:** Explore various features through the intuitive interface, including data analysis tools and settings.
5. **Data Management:** Import or export data through the provided options within the app.

For more detailed information and updates, visit the [project documentation](link-to-documentation).