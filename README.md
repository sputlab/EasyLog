# EasyLog
EasyLog is a simple and intuitive tool designed to streamline activity tracking, allowing users to effortlessly log and manage their tasks in real-time with minimal effort.
Below, we will explore the main features and technical specifications of the app.

## 1. Intuitive User Interface
The web app features a clear and easy-to-use interface. The layout of the elements allows for quick access to various functions, with dedicated sections for logging activities, viewing timers, and managing past activities.

## 2. Activity Logging
Logging activities is straightforward and direct. There are three main elements:
- **Activity Description**: A text field to enter the description of the activity.
- **Timer**: A stopwatch that starts counting time as soon as the "Start" button is pressed, with updates every second, displaying the elapsed time in HH:MM:SS format.
- **Start/Stop Button**: Allows users to start or stop the timer, recording the elapsed time once the activity is completed.

## 3. Activity Management
Logged activities are displayed in a list below the timer. Each activity shows:
- The description (modifiable in the list even after the activity has been logged).
- The time taken.
- The start and end dates and times.

## 4. Activity Deletion
Each activity has a delete button that allows for easy removal of entries that are no longer needed. Deletion must be confirmed.

## 5. PDF Export
A useful feature is the option to export all activities into a PDF document. This is done by pressing the "Export to PDF" button. The generated file includes all activity details, and the filename includes the date and time of export in Italian format (attivita_GG-MM-AAAA_HH-MM-SS.pdf).

## 6. Browser Storage
The web app does not require external databases; it uses the browser's Local Storage to maintain logged activities. This way, even if the page is reloaded or the browser is closed, the information remains available upon the next access.

## 7. Responsive Design
The app is designed to adapt to different screen sizes, making it usable from desktops, laptops, or mobile devices without compromising usability.

## 8. Simplicity and Maintenance
The code is developed in HTML, CSS, and JavaScript. It utilizes libraries like jsPDF for PDF generation. It has been designed to be simple and modular, facilitating future updates or additions.

## Conclusion
The EasyLog web app is a useful tool for anyone looking to keep track of their daily activities practically. It is a free app, accessible to everyone, with no need for any investment. If you have questions or suggestions, feel free to contact us!
