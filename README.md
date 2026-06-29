# CS-360-Mobile-Architect-Programming
## CS 360 Mobile App Portfolio Reflection

## App Overview

The application I developed is called HotSpot, a community-focused event discovery app designed to help users find local events, keep track of upcoming activities, and connect with others in their community. The primary goal of the app is to make it easier for users to discover events they may have otherwise missed while providing a simple interface for viewing, creating, and managing events. The app also includes user authentication, notifications, and profile features to create a more personalized experience.

## User Interface Design

Several screens were necessary to support the needs of users, including a login screen, home screen, calendar view, alerts page, notifications page, profile page, and an event creation dialog. The home screen allows users to browse available events, while the calendar provides another way to organize and view them. The alerts page displays notifications, and the profile page gives users access to their personal information and event history.

When designing the interface, I focused on keeping navigation simple and consistent across every screen. I used a bottom navigation bar to make switching between major sections easy, along with reusable layouts, consistent icons, and organized resource files. Separating strings, layouts, menus, and drawable resources also made the application easier to maintain while following Android development best practices.

## Development Process

Here's a version that better matches what you've described throughout the course and sounds a bit more polished while keeping your style:

**Development Process**

I approached development by first designing the user interface and overall layout before implementing the functionality behind each screen. Rather than trying to complete the entire application at once, I focused on developing one feature at a time. After each feature was working, I integrated it with the rest of the application using activities, adapters, and an SQLite database. As the project evolved, I also organized shared resources such as string files, layouts, and menus to make the code more modular and easier to maintain. Breaking the project into smaller, manageable pieces made debugging much easier, reduced complexity, and allowed me to focus on solving one problem at a time. This is a development strategy I plan to continue using in future software projects because it improves organization, maintainability, and overall code quality.

## Testing

Testing was performed throughout development by running the application on the Android emulator after completing each feature. I verified that navigation between activities worked correctly, events could be created and deleted from the database, login functionality operated as expected, and SMS notification permissions behaved properly. This testing process was important because it helped identify bugs such as missing resources, navigation issues, and database errors before moving on to the next stage of development.

## Challenges and Innovation

One of the biggest challenges was organizing the application as it became more complex. As additional screens, adapters, layouts, and database functionality were added, maintaining a clean project structure became increasingly important. I also had to redesign portions of the application several times as new ideas emerged and additional functionality was added. One feature I improved during development was the SMS notification permission flow. Instead of requesting permission immediately when the app launched, I redesigned the process so users are first presented with a dedicated notifications screen where they can choose whether or not to enable SMS notifications. This provides a better user experience and gives users more control over their privacy.

## Demonstration of Skills

The component that best demonstrates my knowledge and skills is the overall integration of the application's features. I successfully combined multiple Android activities, RecyclerViews, adapters, SQLite database operations, dialogs, permissions, navigation components, and reusable resources into a single application. Throughout the project I also gained experience organizing Android resources, managing layouts, handling user input, and implementing a user-centered interface. Completing this project strengthened both my Android development skills and my confidence in designing larger software applications.
