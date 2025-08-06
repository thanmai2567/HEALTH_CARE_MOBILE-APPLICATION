# 24x7 Healthcare Mobile Application

## Description

The **24x7 Healthcare Mobile Application** Android application provides users with a multi-functional healthcare service platform. The app integrates features like **user authentication**, **lab test packages**, **medicine purchases**, **doctor appointments**, and **order details** management. The system is backed by an **SQLite database** for handling data, including user registration, login, cart management, and appointment scheduling.

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
