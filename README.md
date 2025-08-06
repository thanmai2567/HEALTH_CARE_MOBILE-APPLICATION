# 24x7 Healthcare Mobile Application
A project that has been especially rewarding is the 24x7 Healthcare Mobile Application, an all-in-one platform designed to simplify healthcare services for users. This application combines user authentication, lab test packages, medicine purchases, doctor appointments, and order details management to provide a seamless healthcare experience.I developed the app using Kotlin for the Android platform, implementing features like user registration, login authentication, and appointment scheduling. The system also includes a SQLite database to manage user data, cart items, orders, and appointments efficiently. A key feature is the appointment booking module, which allows users to choose doctors, view available slots, and book appointments with ease. Additionally, the app provides access to health articles, offering valuable information to users looking to stay informed about various health topics.What excites me most about this project is how it improves user access to healthcare services while reducing manual administrative work. By automating tasks like appointment scheduling, order management, and healthcare information access, the app ensures a smooth user experience and encourages better healthcare practices. It was incredibly satisfying to see how this app could make a tangible difference in people's lives, from simplifying appointment bookings to empowering users with the information they need to manage their health. This project reinforced my commitment to creating impactful, scalable solutions using technology.
## Features

- **User Authentication**: Registration, login, and session management using **SharedPreferences**.
- **Healthcare Services**: Lab test packages, medicine purchases, and doctor appointments.
- **Appointment Scheduling**: Date and time picker integration for booking doctor appointments.
- **Order Management**: Cart management for lab tests and medicines, order tracking.
- **Health Articles**: Access to a collection of health-related articles.
- **UI/UX Design**: Modern UI using **CardViews**, **GridLayouts**, and **ListViews** for dynamic content display.
- **Database**: SQLite database integration for managing user data, orders, and appointments.

## Tech Stack

- **Frontend**: Kotlin (Android SDK)
- **Database**: SQLite (with `SQLiteOpenHelper`)
- **UI**: ConstraintLayout, CardView, GridLayout, ListView
- **Session Management**: SharedPreferences
- **App Navigation**: Intents for inter-activity communication
- **Date & Time Handling**: DatePickerDialog and TimePickerDialog for appointment booking

 **Run the app**:
    - Set up an **Android Virtual Device (AVD)** using the **AVD Manager** in Android Studio.
    - Run the app on an emulator or a physical device.

 **Database Setup**:
    - The app uses an **SQLite database** to manage user data and appointments, which is handled automatically by the **DatabaseHelper** class.
  
## Features Walkthrough

- **User Authentication**: Includes user registration and login with validation (password strength, email format). Sessions are stored using **SharedPreferences** to maintain the user state.
- **Healthcare Services**: Users can view lab test packages, medicines, and book doctor appointments through interactive UI elements such as **CardViews** and **GridLayouts**.
- **Appointment Booking**: The app integrates a **DatePickerDialog** and **TimePickerDialog** for users to choose appointment times, with validation for past dates and invalid inputs.
- **Order Management**: Users can add lab tests and medicines to their cart, view their cart, and place orders.

## UI Design

- **ConstraintLayout**: Used for flexible and responsive UI layouts.
- **CardViews**: Display doctor's specialties and healthcare services.
- **GridLayouts**: For organizing UI components like doctor's specialties in a grid format.
- **ListViews**: Display dynamic content such as health articles with custom adapters.

## Security and Validation

- **Input Validation**: The app performs input validation on user registration forms (e.g., empty fields, matching passwords, email format).
- **Session Management**: User session is managed using **SharedPreferences**, which securely stores login details.
