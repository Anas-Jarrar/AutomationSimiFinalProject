🚀 AutomationSimiFinalProject
This project is an automation testing suite developed using Selenium WebDriver, Java, and TestNG. It covers various types of web elements like radio buttons, dynamic and static dropdowns, checkboxes, tables, alerts, iFrames, window/tab switching, and more — all against the test website: https://codenboxautomationlab.com/practice/.

📁 Project Structure
AutomationSimiFinalProject/
└── src/
    └── AutomationSimiFinalProject/
        └── AppTest.java


✅ Features Covered
✅ Radio Buttons

✅ Dynamic & Static Dropdowns

✅ Auto-complete Fields

✅ Checkboxes (single & multiple)

✅ Windows & Tabs switching

✅ JavaScript Alerts

✅ Tables (reading headers, data, prices)

✅ Element visibility & enable/disable testing

✅ Mouse hovering actions

✅ Booking calendar interaction

✅ iFrame handling



🛠️ Setup Instructions
Prerequisites
Java JDK 8 or higher

Maven or other build tool (if used)

TestNG (can be installed via IntelliJ plugin or Maven)

Chrome browser

ChromeDriver (compatible with your browser version)

Installation
Clone the repository or copy the project files.

Make sure you have chromedriver installed and its path set in your system.

Open the project in your IDE (e.g., IntelliJ IDEA or Eclipse).

Add the required dependencies (Selenium, TestNG) via Maven or manually.

Run the tests using TestNG.

🧪 Running Tests
You can enable/disable test cases by toggling the enabled attribute in @Test annotation.

@Test(priority = 1, enabled = true)
public void RadioButton() {
    ...
}
To run all active tests:

Right-click AppTest.java and choose Run with TestNG

Or use the TestNG XML suite (if added)


👨‍💻 Author
Anas Jarrar
