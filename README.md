<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> HiveMind is a mobile app for modern beekeeping, utilizing IoT devices to monitor hive health, detect pests through hive images, and provide up-to-date weather insights for your apiary locations.
> It also fosters collaboration between hive owners and ground beekeepers, all within a single platform.

### User Stories

#### Owner

- As an owner, I want to check my apiaries and hives and their location, so I can keep track of their conditions.
- As an owner, I want to receive recommendations on hive activities, so I can ensure maximum harvest.
- As an owner, I want to assign tasks to beekeepers, so I can make sure the work gets done on time.

#### Beekeeper

- As a beekeeper, I want to receive hive conditions from sensors and manually add some, so I can track the hives health.
- As a beekeeper, I want to upload hive pictures and audios, so I can monitor pests or abnormal activity.
- As a beekeeper, I want to receive tasks from the owner and mark them as done, so I can keep the owner updated on my progress.

#### Admin

- As an admin, I want to track all users and their activity, so I can ensure app is used appropriately.
- As an admin, I want to manage user accounts, so I can add, update, or deactivate users as needed.
- As an admin, I want to view and edit details of all apiaries and hives, so I can maintain accurate records of the hives and their conditions.

<br><br>

<!-- Tech stack -->
<img src="./readme/title3.svg"/>

### HiveMind is built using the following technologies:

- This project uses the [Flutter app development framework](https://flutter.dev/). Flutter is a cross-platform hybrid app development platform which allows us to use a single codebase for apps on mobile, desktop, and the web.
- This project uses the [NestJS server-side framework](https://nestjs.com/), a progressive Node.js framework built with TypeScript and JavaScript, designed for building efficient, reliable, and scalable server-side applications.
- For database operations, the app utilizes [MongoDB](https://www.mongodb.com/), a NoSQL database that supports flexible and scalable data storage, along with [MongoDB Compass](https://www.mongodb.com/products/tools/compass) for an intuitive graphical interface to manage and visualize the database.
- For IoT integration, the app utilizes the ESP12E-8266 module, a low-cost Wi-Fi module developed by [Espressif System](https://www.espressif.com/en/products/modules/esp8266) and ideal for IoT applications, offering built-in Wi-Fi and GPIO capabilities. The module was programmed using [PlatformIO](https://platformio.org/), a VS Code extension for firmware development.
- The admin panel was developed using [ReactJS](https://react.dev/), a popular JavaScript library for building dynamic, responsive, and efficient single-page applications.
- The machine learning model is served using [Flask](https://flask.palletsprojects.com/en/stable/), a lightweight Python web framework ideal for creating APIs and serving models efficiently.
- To send local push notifications, the app uses the [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications) package which supports Android, iOS, and macOS.

<br><br>

<!-- UI UX -->
<img src="./readme/title4.svg"/>

> HiveMind was designed on Figma, starting with wireframes and progressing to mockups, with iterations focused on achieving smooth navigation and a seamless user experience.

- Project Figma design [figma](https://www.figma.com/design/AIptVTX0dJFBQaGKdf3dAY/UI-UX-Assignments?node-id=0-1&node-type=canvas&t=0t6X8FZMun35SXlq-0)

### Mockups

| Apiaries Screen - Owner                                                 | Hives Screen - Beekeeper                                                  | Tasks Screen - Beekeeper                                                |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| ![ApiariesFrame](./assets/images/FigFrames/Apiary%20Screen%20Owner.png) | ![HivesFrame](./assets/images/FigFrames/Details%20Screen%20Beekeeper.png) | ![TasksFrame](./assets/images/FigFrames/Tasks%20Screen%20Beekeeper.png) |
| Add Apiary - Owner                                                      | Add Hive - Owner                                                          | Add Task - Owner                                                        |
| ![AddApiary](./assets/images/FigFrames/Add%20Apiary.png)                | ![AddHive](./assets/images/FigFrames/Add%20Hive.png)                      | ![AddTask](./assets/images/FigFrames/Add%20Task.png)                    |

<br><br>

<!-- Database Design -->
<img src="./readme/title5.svg"/>

### Architecting Data Excellence: Innovative Database Design Strategies:

![DatabaseSchema](./assets/images/MongoDbSchema.png)

<br><br>

<!-- Implementation -->
<img src="./readme/title6.svg"/>

| Onboarding Screen 1                                         | Onboarding Screen 2                                         | Login screen                              |
| ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------- |
| ![OnboardingScreen1](./assets/images/OnboardingScreen1.jpg) | ![OnboardingScreen2](./assets/images/OnboardingScreen2.jpg) | ![LoginScreen](./assets/images/Login.jpg) |

### Owner Screens (Mobile)

| Apiaries Screen                                                 | Hives of Apiary Screen                                          | Tasks of Apiary Screen                                           |
| --------------------------------------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- |
| ![ApiariesScreen](./assets/images/Owner/ApiariesOwner.png)      | ![HivesScreen](./assets/images/Owner/HivesOfApiaryOwner.jpg)    | ![TasksScreen](./assets/images/Owner/TasksOfApiaryOwner.jpg)     |
| Add Apiary                                                      | Add Hive                                                        | Add Task                                                         |
| ![AddApiary](./assets/gifs/addApiaryDemo_gif.gif)               | ![AddHive](./assets/gifs/AddHiveDemoCompressed.gif)             | ![AddTask](./assets/gifs/AddTaskDemoCompressed.gif)              |
| Delete Apiary                                                   | Map Screen                                                      | Complete Task                                                    |
| ![DeleteApiary](./assets/gifs/DeleteApiaryDemoCompressed.gif)   | ![MapScreen](./assets/gifs/MapDemoCompressed.gif)               | ![CompleteTask](./assets/gifs/CompleteTaskDemoCompressed.gif)    |
| General Hive Details Screen - Dark                              | Hive History Screen - Dark                                      | Empty Alerts Screen - Dark                                       |
| ![DarkDetailsScreen](./assets/images/Owner/HiveDetailsDark.jpg) | ![DarkHistoryScreen](./assets/images/Owner/HiveHistoryDark.jpg) | ![DarkAlertsScreen](./assets/images/Owner/EmptyStateDark%20.jpg) |

### Beekeeper Screens (Mobile)

| Apiary Screen                                                        | Tasks Screen                                                     | Alerts Screen                                               |
| -------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------- |
| ![ApiaryScreen](./assets/images/Beekeeper/HivesPageBeekeeper.png)    | ![TasksScreen](./assets/images/Beekeeper/TasksPageBeekeeper.png) | ![AlertsScreen](./assets/images/Beekeeper/AlertsPage.jpg)   |
| General Hive Details Screen                                          | Hive History Screen                                              | Image Analysis                                              |
| ![DetailsScreen](./assets/images/Beekeeper/HiveDetailsBeekeeper.jpg) | ![HistoryScreen](./assets/gifs/HiveDetailsDemoCompressed.gif)    | ![AIAnalysis](./assets/gifs/AiAnalysisDemoCompressed.gif)   |
| Settings Screen                                                      | Receiving Alerts                                                 | RComment on Task - Dark                                     |
| ![SettingsScreen](./assets/images/Beekeeper/SettingsPage.jpg)        | ![ReceiveAlerts](./assets/gifs/AlertsDemoCompressed.gif)         | ![CommentTask](./assets/gifs/TaskCommentDemoCompressed.gif) |

### Admin Screens (Web)

| Login Screen                                          | Users Screen                                                    |
| ----------------------------------------------------- | --------------------------------------------------------------- |
| ![LoginScreen](./assets/images/Admin/Login.png)       | ![UsersScreen](./assets/images/Admin/Users.png)                 |
| Apiaries Screen                                       | Apiary Details Screen                                           |
| ![ApiariesScreen](./assets/images/Admin/Apiaries.png) | ![ApiaryDetailsScreen](./assets/images/Admin/ApiaryDetails.png) |

<br><br>

<!-- IoT Simualtion -->
<img src="./readme/title7.svg"/>

### Smart IoT Simulation: Transforming Connectivity into Actionable Insights

- This project incorporates IoT devices to establish a connection between the mobile application and real-life beehives.
- The sensors employed include the DHT22, which measures temperature and humidity, and a load cell, which detects weight changes critical for determining the optimal timing for honey harvesting. These sensors interface with the ESP8266 module and periodically update the hive conditions in the application.

| Setup                                     | Sensors                                     | Setup Without Hive                         |
| ----------------------------------------- | ------------------------------------------- | ------------------------------------------ |
| ![Setup](./assets/images/IoT/HiveIoT.png) | ![Sensors](./assets/images/IoT/Sensors.png) | ![Setup](./assets/images/IoT/IoTSetup.png) |

<br><br>

<!-- How to run -->
<img src="./readme/title10.svg"/>

> To set up HiveMind locally, follow these steps:

### Prerequisites

- npm

  ```sh
  npm install npm@latest -g
  ```

- Flutter SDK from official documentation
- Python 3.10 from official documentation
- Arduino IDE or PlatformIO Extension in Visual Studio
- ESP8266 module
- Google Cloud Platform project with Places API and Maps SDK enabled
- Firebase CLI
- Firebase Project for notifications

### Installation

#### Cloning the Repository

1. Run the following command to clone the repository and all its submodules

   ```sh
   git clone --recurse-submodules [github](https://github.com/Sana-Kassamani/hivemind.git)
   ```

#### Server Configuration

1. Navigate to hivemind-server directory

   ```sh
   cd hivemind-server
   ```

2. Install NPM packages
   ```sh
   npm install
   ```
3. Run the following command and fill the necessary values in the created .env file
   ```sh
   cp .env.example .env
   ```
4. Navigate to your Firebase project in Firebase Console and maintain a Firebase Admin SDK for Nodejs, downloaded as a JSON file.
   Populate the .env file created with the current values from the downloaded JSON file.
5. Run Nestjs

   ```sh
   npm run start:dev
   ```

#### Application Configuration

1. Install Flutter SDK

2. Navigate to hivemind-app directory

   ```sh
   cd hivemind-app
   ```

3. Install pub packages from pubspec.yaml

   ```sh
   flutter pub get
   ```

4. Create a .env file and define URL with the url of your server and the API Key of your Google Cloud Platform

   ```js
   URL = "http://<IP-address>:<Port>";
   GOOGLE_API_KEY = "YOUR-KEY";
   ```

5. Make sure Firebase CLI is installed on your machine and run the following commands (Flutterfire will help you connect to your firebase project in the terminal.)
   ```sh
   dart pub global activate flutterfire_cli
      flutterfire configure
   ```
6. Run Flutter
   ```sh
   flutter run
   ```

#### Admin Panel Configuration

1. Navigate to hivemind-admin_panel directory

   ```sh
   cd hivemind-admin_panel
   ```

2. Install NPM packages
   ```sh
   npm install
   ```
3. Run the following command and fill the necessary values ( server url ) in the created .env file
   ```sh
   cp .env.example .env
   ```
4. Your database shall be populated with an admin document in users.

5. Run project

   ```sh
   npm run start
   ```

#### Flask Configuration

1. Navigate to hivemind-flask directory

   ```sh
   cd hivemind-flask
   ```

2. Create and activate a virtual environment to install dependencies ( The Following commands are for Windows users)
   ```sh
   python -m venv venv
   .\venv\Scripts\activate
   ```
3. Install dependencies from requirements.txt file
   ```sh
   pip install -r requirements.txt
   ```
4. Run the server
   ```sh
   flask run
   ```

#### Arduino Configuration

1. Navigate to hivemind-arduino directory

   ```sh
   cd hivemind-arduino
   ```

2. Install the dependencies listed in platformio.ini file under lib_deps

3. Set the variables in wifi.cpp file according to your network and sever

   ```cpp
   const char* ssid = "<Network-ssid>";
   const char* password = "<Network-password>";
   const char* serverName = "<Server_url";
   ```

4. Plug the module to your laptop and build the project. Enable serial monitor to read the prints.
5. Replace sensor reading with dummy values to simulate functionality.

   Now, you should be able to run HiveMind locally and explore its features.
