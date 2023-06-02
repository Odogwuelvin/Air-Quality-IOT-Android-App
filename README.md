# A-QM

The Air Quality Monitoring app, developed using Java on Android Studio, focuses on collecting real-time data from an Arduino prototype and transmitting it through Firebase Realtime Database. The primary objective of the app is to monitor air quality. Additionally, a room management feature has been implemented for practice purposes, although technically there is only a single room associated with the prototype.

Upon launching the app, users are prompted to authenticate or sign up to create a new account. Once logged in, they are presented with a dashboard displaying four options:

- Room List: Users can view the list of added rooms and have the ability to add or modify them by performing a long press.
- Air Quality Indicators: This section provides a visual representation of general air quality indicators, including temperature (in Celsius), humidity (in percentage), CO2 levels (in ppm), and light intensity (in lux). An Air Quality Index (AQI) is calculated based on a threshold of 1000, with the maximum value obtained being 1200. The app assigns a corresponding comment on the air quality, such as good, bad, or moderate.
- Fan Control: Users can control the real fan by toggling it on or off directly from the app.
- Occupancy Prediction: The app consumes a custom API developed to predict room occupancy based on the previously mentioned air quality indicators.

Although there are plans to add more functionalities, due to time constraints, the existing features provide a comprehensive air quality monitoring solution. Thank you for taking the time to read this description.
![App Icon](screenshots/appico.png)
**Figure 1: App Icon**

---

### Home Screen: 
The initial screen that greets users when they launch the application is a crucial point of entry into the app's world. It sets the tone and prepares users for the experience that awaits them. Typically, this first screen serves as an introduction or a splash screen, captivating users with a visually pleasing and branded display.
As the application springs to life, the initial screen takes center stage, capturing attention and creating a sense of anticipation. 

It may feature captivating imagery, a captivating logo, or a brief tagline that reflects the app's purpose and personality. This screen is designed to leave a positive first impression on users, igniting their curiosity and motivating them to explore further.

![Home Screen](screenshots/homescreen+.png)
**Figure 2: Home Screen**

---

### Login Screen: 
The LOGIN screen is a crucial element of the application, ensuring that only authorized users can access its features. It provides a secure entry point where users can input their login credentials, such as username and password, to authenticate their identity. By requiring this step, the app establishes a protective barrier, safeguarding sensitive information and maintaining user privacy. 

The LOGIN screen interface typically includes intuitive input fields and clear instructions, guiding users through the authentication process. Additional security measures like two-factor authentication may be incorporated to enhance user data protection. Overall, the login screen acts as a secure gateway, allowing users to access their personalized accounts and ensuring a safe and tailored experience within the application.

![Login Screen](screenshots/logi.png)
**Figure 3: Login Screen**

---

### Sign Up Screen: 
The SIGN UP screen serves as a platform for new users to register an account within the application. It offers a streamlined process for users to provide necessary information such as username, address (optional), email address, and password. By filling out these details, users can create a personalized account and unlock the application's full range of functionalities. 

The SIGN UP screen ensures a smooth and intuitive experience, guiding users through the registration process with clear instructions and input fields. It acts as a crucial step in expanding the user base and allowing individuals to fully engage with the application's features and services. Overall, the sign-up screen facilitates the onboarding process, enabling new users to establish their presence and begin their journey within the application.

![Sign Up Screen](screenshots/signup.png)
**Figure 4: Sign Up Screen**

---

### Dashboard Screen
The Dashboard screen presents all of the services that our app can do. We can also see the name of the current user and some other of his information.

Our application can detect the occupancy of a room as a machine learning module [see Chapter 6], also we see the list of the rooms located in a building.

Once the user finishes his session, he can sign out using the Sign out option in the menu at the top-end corner of the screen, which will allow him to return to the login activity. The user must sign in the next time he intends to use the app.

![Dashboard Screen](screenshots/dashboard+.png)
**Figure 5: Dashboard Screen**

---

### Room Lists Screen: 
The room lists screen provides users with a comprehensive overview of available rooms or locations that can be monitored for air quality. It gives information such as name, capacity, and size for each room, allowing users to identify the room they want to inspect or modify. Users can select a specific room from the list to access more detailed data or perform actions such as editing or removing the room by a long click on the designed room. 

This screen aims to provide an organized and convenient way for users to manage their rooms, enabling them to monitor air quality efficiently and make necessary adjustments to maintain a healthy environment.

![Room Lists Screen](screenshots/roomlists+.png)
**Figure 6: Room Lists Screen**

---

### Machine Learning Module:
Our application utilizes machine learning algorithms to predict the occupancy of a room based on air quality parameters. This module analyzes various factors like carbon dioxide levels, temperature, humidity, and particulate matter to estimate whether a room is occupied or not. 

The machine learning module plays a vital role in optimizing energy consumption and ensuring a healthy and comfortable environment for users. By accurately predicting occupancy, the application can automatically adjust ventilation, heating, and cooling systems to maintain optimal conditions while conserving energy.

![Machine Learning Module](screenshots/machinelearning+.png)
**Figure 7: Machine Learning Module**

---

### Notifications:
The notifications feature within the app keeps users informed about important updates, alerts, and reminders related to their monitored rooms and air quality. Notifications can include warnings about poor air quality, reminders to change filters or perform maintenance tasks, and updates on room occupancy status.

By providing timely and relevant notifications, the app enhances user experience and helps them stay proactive in maintaining a healthy environment. Users can customize their notification preferences, choosing which types of alerts they want to receive and how they want to be notified (e.g., push notifications, email notifications, or in-app notifications).

![Notifications](screenshots/notifications.png)
**Figure 8: Notifications**
