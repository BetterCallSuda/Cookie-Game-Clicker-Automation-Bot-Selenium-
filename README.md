🍪 Cookie Clicker Automation Bot (Selenium)
📌 Project Overview

This project is a Python automation bot built using Selenium WebDriver that plays the Cookie Clicker game automatically.
The bot continuously clicks the cookie, intelligently purchases the best affordable upgrades, and runs for a fixed duration.

It demonstrates real-world browser automation, dynamic element handling, and decision-making logic using Python.

🛠️ Technologies Used

Python

Selenium WebDriver

Google Chrome

HTML DOM interaction

Time-based automation

⚙️ Features

Automatically opens the Cookie Clicker website

Selects the English language option

Continuously clicks the main cookie

Reads live cookie count from the webpage

Buys the most expensive upgrade available every 5 seconds

Handles missing elements using exception handling

Runs the automation for 5 minutes

Prints the final cookie count at the end

🧠 Concepts Covered

Web automation with Selenium

DOM element selection (By.ID, CSS Selectors)

Handling dynamic web content

Exception handling (NoSuchElementException)

Time-based logic using time() and sleep()

Browser configuration using ChromeOptions

🚀 How It Works

Launches Chrome browser using Selenium

Loads the Cookie Clicker game

Handles language selection popup

Clicks the cookie continuously

Every 5 seconds:

Reads available cookies

Finds affordable store items

Purchases the best upgrade

Stops execution after 5 minutes

Displays final cookie count

📦 Installation & Setup
1️⃣ Install Required Packages
pip install selenium

2️⃣ Download ChromeDriver

Make sure Google Chrome is installed

Download matching ChromeDriver

Add it to your system PATH

3️⃣ Run the Script
python main.py

⚠️ Notes

Website structure changes may break selectors

sleep() is used instead of WebDriverWait for simplicity

For advanced projects, explicit waits are recommended

📈 Future Improvements

Use WebDriverWait instead of sleep

Add logging instead of print statements

Make runtime configurable

Add headless mode

Optimize buying strategy further

🎯 Learning Outcome

This project helped me understand:

How real websites behave dynamically

How automation bots work in practice

How to safely interact with live web elements

How to structure automation logic cleanly
