📖 About
==========
CameraRental-App is a console-based Java application designed to simulate a simple camera rental service. It enables users to:

==>View available cameras
==>Add or remove cameras
==>Rent cameras by deducting rental charges from a digital wallet
==>Deposit money into their wallet for transactions

This is a great hands-on project for practicing OOP concepts, collections, and console I/O in Java.

🚀 Features
=============
📜 User authentication prompt (username and password — currently not verified)

📸 Add, Remove, and View available cameras

🎥 Rent cameras (only if sufficient wallet balance is available)

💰 Digital Wallet management (check balance and deposit funds)

📃 Clear, menu-driven console interface

🛠 Technologies Used
=====================
Java SE 8+
JDK
Eclipse / IntelliJ IDEA (recommended IDEs)
Git for version control

▶️ How to Run
===============
1.Clone the repository:
git clone https://github.com/surajsamanta2000/CameraRental-App.git
2.Open the project in your Java IDE (like Eclipse or IntelliJ)
3.Run the CameraMain class — this contains the main() method that starts the console application.

📂 Project Structure
=====================
CameraRental-App/
└── src/
    └── jsp.camera.rental/
        ├── Camera.java
        ├── Wallet.java
        ├── CameraRentalApp.java
        └── CameraMain.java

 Note
=========
* This is a console-based demo project — no persistent storage is implemented yet. All data is lost upon application exit. Future improvements could include:
* Persistent storage using files or databases
* User authentication system
* Web-based or GUI interface
