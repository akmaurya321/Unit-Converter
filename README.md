🧮 Multi Unit Conversion Application
📖 Overview

The Multi Unit Conversion Application is a simple, interactive Java Swing GUI project that allows users to convert between different units of length — Kilometers, Meters, and Centimeters.

It is built with NetBeans GUI Builder (Swing Designer) and includes smart validation, popup messages, and a confirmation dialog before quitting. This project demonstrates GUI handling, event-driven programming, and user interaction in Java.

✨ Features

✅ Convert units between:
Kilometers → Meters
Meters → Centimeters
Centimeters → Meters

✅ Interactive GUI built with Java Swing

✅ Error Handling:

Warns if input field is empty
Detects invalid (non-numeric) inputs
Alerts if no unit option is selected

✅ Clear Button:

Clears input, output, and radio button selection

✅ Quit Button:
Confirms before exiting
Asks for your name
Displays a “Thank You” message before closing the app

✅ Neatly formatted layout using NetBeans GUI Builder

🛠️ Technologies Used
Tool / Library	Purpose
Java (JDK 8 or higher)	Main programming language
Swing	GUI framework
NetBeans IDE	For designing and running the GUI
JOptionPane	Popup message dialogs for interaction
📂 Project Structure
MultiUnitConversionApp/
│
├── src/
│   └── com/mycompany/mavenproject1/
│       └── MultiUnitConversion.java
│
├── pom.xml (if using Maven)
│
└── README.md

🚀 How to Run
Option 1 — Run in NetBeans

Open NetBeans IDE.

Click File → Open Project → Select this folder.

Open the file:
src/com/mycompany/mavenproject1/MultiUnitConversion.java

Click the green Run ▶ button or press Shift + F6.

Option 2 — Run from Command Line

If you exported the .java file:

javac MultiUnitConversion.java
java com.mycompany.mavenproject1.MultiUnitConversion

🧠 How It Works (Logic Explanation)
Action	Description
Convert Button	Reads input → Checks radio selection → Performs conversion
Clear Button	Resets input, output, and selection fields
Quit Button	Asks confirmation → Requests user name → Displays “Thank you” → Closes app
Radio Buttons	Used to select the unit to convert from
Example Conversions:
Input	Selected Unit	Output
1	Kilometer	1000 meters
5	Meters	500 centimeters
250	Centimeters	2.5 meters
📸 (Optional) Screenshot

(Add a screenshot of your GUI window here)
For example:
![App Screenshot](images/screenshot.png)

💬 Pop-up Interactions

If no input entered:

⚠️ “Please enter a value!”

If wrong input (like text):

❌ “Invalid input! Please enter numeric values only.”

If no unit selected:

⚠️ “Please select a unit to convert!”

On Clear:

✅ “All fields cleared successfully.”

On Quit:
“Are you sure you want to quit?”
“Enter your name”
“Thank you, [Name], for using this application!”

🧩 Concepts Demonstrated
Event-driven programming (ActionListener)
GUI design using Swing
Exception handling (try–catch)
Conditional logic (if–else)
User interaction with JOptionPane
Object-oriented design (encapsulation via JFrame class)

🤝 Contribution

Feel free to fork the repository and improve the design or add new unit conversions (e.g., inches, feet, miles).
Pull requests are welcome!

📜 License

This project is open-source and available under the MIT License.

🧑‍💻 Author

Developed by: Ak Maurya
Project Type: Java Swing GUI (Educational Purpose)
IDE Used: NetBeans
Language: Java
