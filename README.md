# CS-360-Mobile-Architect-Programming
# CS 360 Mobile App Portfolio Reflection

## App Overview

The application I developed is called HotSpot, a community-focused event discovery app designed to help users find local events, keep track of upcoming activities, and connect with others in their community. The primary goal of the app is to make it easier for users to discover events they may have otherwise missed while providing a simple interface for viewing, creating, and managing events. The app also includes user authentication, notifications, and profile features to create a more personalized experience.

## User Interface Design

Several screens were necessary to support the needs of users, including a login screen, home screen, calendar view, alerts page, notifications page, profile page, and an event creation dialog. The home screen allows users to browse available events, while the calendar provides another way to organize and view them. The alerts page displays notifications, and the profile page gives users access to their personal information and event history.

When designing the interface, I focused on keeping navigation simple and consistent across every screen. I used a bottom navigation bar to make switching between major sections easy, along with reusable layouts, consistent icons, and organized resource files. Separating strings, layouts, menus, and drawable resources also made the application easier to maintain while following Android development best practices.

## Development Process

I approached development by building one feature at a time instead of trying to complete the application all at once. I first created the layouts and user interface before implementing the functionality behind each screen. Once individual features were working, I connected them together through activities, adapters, and the SQLite database. Breaking the project into smaller pieces made debugging much easier and allowed me to focus on one problem at a time. This is a strategy I plan to continue using in future software projects because it reduces complexity and helps isolate issues more quickly.

## Testing

Testing was performed throughout development by running the application on the Android emulator after completing each feature. I verified that navigation between activities worked correctly, events could be created and deleted from the database, login functionality operated as expected, and SMS notification permissions behaved properly. This testing process was important because it helped identify bugs such as missing resources, navigation issues, and database errors before moving on to the next stage of development.

## Challenges and Innovation

One of the biggest challenges was organizing the application as it became more complex. As additional screens, adapters, layouts, and database functionality were added, maintaining a clean project structure became increasingly important. I also had to redesign portions of the application several times as new ideas emerged and additional functionality was added. One feature I improved during development was the SMS notification permission flow. Instead of requesting permission immediately when the app launched, I redesigned the process so users are first presented with a dedicated notifications screen where they can choose whether or not to enable SMS notifications. This provides a better user experience and gives users more control over their privacy.

## Demonstration of Skills

The component that best demonstrates my knowledge and skills is the overall integration of the application's features. I successfully combined multiple Android activities, RecyclerViews, adapters, SQLite database operations, dialogs, permissions, navigation components, and reusable resources into a single application. Throughout the project I also gained experience organizing Android resources, managing layouts, handling user input, and implementing a user-centered interface. Completing this project strengthened both my Android development skills and my confidence in designing larger software applications.
