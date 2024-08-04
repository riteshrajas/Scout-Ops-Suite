# 🚀 ScoutOps Suite

ScoutOps Suite is a comprehensive repository that contains all the tools necessary for efficient FRC scouting, including the ScoutOps Android app, ScoutOps Windows client, and ScoutOps Server. This suite integrates these tools into one cohesive package, making it easier for teams to manage and utilize the full range of ScoutOps functionalities.

## 🔍 General Information

- **Name:** ScoutOps Suite
- **Primary Purpose:** To provide a unified repository for all ScoutOps tools.
- **Intended Users:** FRC scouting teams, admins, and developers.
- **Platforms Supported:** Android, Windows, Linux, and any platform supporting Python and SQL.

## ✨ Features and Functionality

- **Main Components:**
  - **ScoutOps Android App:** A mobile-friendly scouting application for recording FRC match data.
  - **ScoutOps Windows Client:** An administrative tool for managing scouting activities and viewing connected devices.
  - **ScoutOps Server:** The backbone for communication and data exchange between the Android app and Windows client, utilizing SQL for data storage and Python for requests.

## 🛠️ Technical Details

- **Technologies and Frameworks Used:**
  - Flutter for the Android app.
  - React for the Windows client.
  - Python and SQL for the server.

- **Data Collection and Storage:**
  - Uses Hive for the Android app.
  - SQL for the server.

- **Communication:**
  - Utilizes Bluetooth PAN for connecting devices.
  - Python's requests library for server communication.

## 🚀 Setup and Usage

### 📋 Prerequisites

- Ensure you have Flutter, React, Python, and SQL installed on your development environment.

### 📥 Installation and Configuration

1. **Clone the Repository:**
   ```sh
   git clone --recurse-submodules https://github.com/yourusername/ScoutOps-Suite.git
   cd ScoutOps-Suite
   ```

2. **ScoutOps Android App:**
   - Navigate to the Android app directory:
     ```sh
     cd ScoutOps-Android
     ```
   - Follow the setup instructions in the Android app's README file.

3. **ScoutOps Windows Client:**
   - Navigate to the Windows client directory:
     ```sh
     cd ScoutOps-Windows
     ```
   - Follow the setup instructions in the Windows client's README file.

4. **ScoutOps Server:**
   - Navigate to the server directory:
     ```sh
     cd ScoutOps-Server
     ```
   - Follow the setup instructions in the server's README file.

### 🚀 Starting the Suite

- **ScoutOps Android App:**
  - Run the app on your Android device using Flutter.
  
- **ScoutOps Windows Client:**
  - Launch the Windows client application.

- **ScoutOps Server:**
  - Start the server using Python:
    ```sh
    python server.py
    ```

## 🛠️ Maintenance and Support

### 🐛 Known Issues and Limitations

- Ensure proper configuration and security measures are in place for the server.

### 📬 Reporting Bugs and Requesting Features

- Report bugs and request new features by raising an issue on GitHub.

### 🔮 Future Plans

- Expand platform support.
- Enhance security features.
- Add new functionalities and endpoints.
