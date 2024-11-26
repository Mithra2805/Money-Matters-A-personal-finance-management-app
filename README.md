Wanderlast - The Travel Companion
Wanderlast is a mobile application designed to help travelers keep track of their expenses during their trips. This app allows users to input their travel expenses, categorize them (e.g., accommodation, transportation, food), and visualize their spending trends. It helps travelers manage their budgets efficiently and avoid overspending.

Features
Expense Tracking: Record all your travel expenses with ease.
Categories: Organize expenses into predefined categories like Food, Accommodation, Transport, Activities, etc.
Expense Summary: View a summary of your spending, including total expenses and the amount spent in each category.
Currency Converter: Convert expenses into your preferred currency.
Expense Analytics: Visualize your expenses with pie charts and graphs.
Multiple Trips: Track expenses for different trips individually.
User-friendly Interface: Simple, clean, and intuitive design optimized for ease of use.
Table of Contents
Installation
App Features
Tech Stack
Usage
Contributing
License
Installation
Prerequisites
Android Studio (Latest version)
Android SDK (Required SDK for building and running the app)
Setup Steps
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/Wanderlast.git
Open in Android Studio:

Open Android Studio and select "Open an existing project."
Navigate to the folder where you cloned the project and select it.
Install Dependencies:

The app requires several dependencies listed in the build.gradle files. Ensure that you have an internet connection to download them automatically.
Build the Project:

Click on Build in the Android Studio toolbar and select Make Project.
If everything is set up correctly, your app should compile without errors.
Run the App:

Connect your Android device or use the Android Emulator.
Click on the Run button (green triangle) in Android Studio to launch the app on your device.
Permissions
The app requires the following permissions:

Internet: For fetching real-time currency exchange rates (optional feature).
Storage: To save user data (expenses, trip details).
App Features
1. Expense Tracking
Track your travel expenses by adding amounts and selecting categories (e.g., Accommodation, Transport, Food, etc.). You can also enter the currency in which the expense is incurred.

2. Categories
Expenses can be categorized to get a better overview of your spending. Categories include:

Food
Accommodation
Transport
Activities
Shopping
3. Currency Converter
With an integrated currency converter, you can easily convert your expenses into your home currency or any other currency. The currency conversion rates are fetched using real-time APIs.

4. Expense Summary
Get an overview of your spending with a summary screen that displays total expenses and the amount spent in each category. This allows you to stay within your budget.

5. Expense Analytics
Visualize your expenses with interactive charts (Pie Chart, Bar Graph) to analyze your spending habits. This feature helps you see where your money is going at a glance.

6. Multiple Trips
The app allows users to manage and track expenses for multiple trips. Each trip is stored separately, and you can easily switch between them.

Tech Stack
Programming Language: Java / Kotlin
Android Studio: IDE for app development
Database: SQLite (For local storage of expenses and trip data)
Libraries/Dependencies:
Room Database: For managing app data.
MPAndroidChart: For expense visualization via charts.
Retrofit: For currency conversion API integration.
Glide: For image loading (if the app includes images like trip photos).
Material Design Components: For beautiful UI components.
Usage
Add Expense
Open the app and navigate to the "Add Expense" screen.
Enter the amount and select the category.
Choose the currency and add a note or description if needed.
Save the expense, and it will appear in the summary view.
View Expenses
From the main screen, tap on the "View Expenses" tab to see a summary of all recorded expenses.
You can filter expenses by category, date, or trip.
Expense Analytics
Tap on the "Analytics" tab to see a visual representation of your expenses.
Choose the desired time period (weekly, monthly, or trip-based) to view the charts.
Currency Conversion
Tap on the "Currency Converter" feature to convert expenses into your desired currency.
The app will fetch the latest exchange rates and display the converted value.
Contributing
We welcome contributions to improve Wanderlast - The Travel Companion! If you want to add new features, fix bugs, or improve documentation, feel free to submit a pull request.

Steps to contribute:
Fork the repository.
Create a new branch (git checkout -b feature-name).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature-name).
Open a pull request to merge your changes.
License
This project is licensed under the MIT License - see the LICENSE file for details.
