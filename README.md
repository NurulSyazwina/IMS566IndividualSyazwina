Individual Assignment IMS566
Project Title 
PocketFlow : A student finance trackers and study management system

a. Project Description
PocketFlow is a web-based application developed using HTML, CSS, JavaScript, Bootstrap, and Chart.js to help students managing both of their academic and financial activities in one platform. In this system allows users to track their expenses, create savings goals, manage their tasks or assignments, organize class schedules, and improve productivity using a Pomodoro timer for studying.Furthermore, the website also includes a responsive and modern interface with light and dark mode support, animated backgrounds, and data visualization features such as pie charts and bar charts to improve users understand their spending trend and progress. This PocketFlow website have been developed with a modern and responsive interface using Bootstrap features to ensure accesibility via all different devices and screen sizes.

This project contains four main pages which are:
1. Register and Login Pages
2. Dashboard Page
3. FinanceHub Page 
4. StudyHub Page

b. Features Included:

1. Register and Login System page
The system has a simple user authentication interface that enables users to safely access the platform with predetermined login credentials. Other features included: 
- Error message for invalid login
- Password visibility toggle
- Modern Bootstrap card design
- Animated Vanta.js background

2. Dashboard Overview
The dashboard acts as the main overview page. It compiles all of the essential information that the user submitted from the StudyHub and FinanceHub websites. However, users must first enter their data in:
+ FinanceHub page
+ StudyHub page

After entering the data, the dashboard will automatically display:
- Expense pie charts
- Monthly spending graph
- Savings goals progress
- Your To-Do list
- Current class reminder

4. FinanceHub
FinanceHub is the financial management part in this website, where students can record, and manage their everyday expenses and set savings goals. The features such as:
- Add expense records that can be edited or delete
- Store expense history using Session Storage
- Create savings goals
- Savings progress bar
- Expense history table

5. StudyHub
StudyHub is the academic productivity part in this website, where students can arrange their tasks, calendars, and study sessions. The features included:
- Add tasks or any assessment
- Edit and delete tasks
- Weekly timetable system
- Add classes by day and time
- Pomodoro timer with study music
- Current class reminder system

6. Dark Mode
- Light/Dark mode toggle
- Theme saved using Local Storage

7. Charts & Analytics
- Pie chart for expense categories
- Bar chart for monthly spending
- Dynamic data visualization using Chart.js

c. Instructions to Test Login

Use the following login credentials:
- Email = nurulsyazwina@gmail.com
- Password = wina123

The System Flow

1. Open index.php
2. Login using the provided email and password
   Use the following login credentials:
    - Email = nurulsyazwina@gmail.com
    - Password = wina123
3. User will be redirected to the Dashboard page
4. Before the dashboard can display meaningful data:
   - User must first add expenses and savings goals in FinanceHub
   - User must add your to-do list and timetable data in StudyHub
5. After entering the data, the Dashboard page will automatically display:
   - Expense statistics
   - Savings progress
   - Your To-Do List overview
   * Current class information


c. Frameworks / Libraries Used

1. Frontend Framework
  - Bootstrap 5.3.8
    Bootstrap is used to construct responsive layouts, navigation bars, forms, buttons, cards, and other user interface components.

2. Icons
  - Bootstrap Icons
    Bootstrap icons are used across the system to enhance a visual illustration and user experience.

3. Charts
  - Chart.js
    Chart.js generates dynamic and interactive pie and bar charts for this website.

4. Animation Background
  - Vanta.js
  - Three.js
    These libraries are used to generate animated backdrop effects for the login and registration pages in order to improve their visual look.

5. Fonts
  - Google fonts

6. Storage
- Session Storage is used to temporarily store:
  ~ Expenses
  ~ Savings goals
  ~ Your To-Do List
  ~ Timetable data
- Local Storage is used to save:
  ~ Light and Dark Theme Mode

All files that have been included:

index.html          -> Login page
register.html       -> Register page
dashboard.html      -> Dashboard overview page
finance.html        -> Finance management page
study.html          -> Study management page
style.css          -> Main styling file

Develop by Nurul Syazwina binti Shoib (2025231844)