Simple Deduction of Physical Quantities

Author: Illia Zuiev
Version: v5.0.0
Created with: Mendix Studio Pro

🧩 Description

This Mendix application demonstrates the calculation and deduction of basic physical quantities such as power (výkon) and speed (rýchlosť) using simple formulas and user inputs.
The interface of the application is fully in Slovak language, designed for easy understanding and use by Slovak-speaking students.
The project was developed for educational purposes as part of studies at the Technical University of Košice (TUKE FVT).

⚙️ Features

Výpočet výkonu (Power Calculation):
User inputs voltage (napätie, V) and current (prúd, A); the app automatically calculates power (výkon, W).

Výpočet rýchlosti (Speed Calculation):
User enters distance (dráha, m) and time (čas, s); the app calculates speed (rýchlosť, m/s).

Clean, modern UI built with Mendix Atlas UI framework

Full Slovak-language interface

Educational and demonstration purpose

⚙️ Technologies

Mendix Studio Pro (version 11.2.0)

Atlas UI framework

Microflows and nanoflows

Mendix built-in database

Java actions (optional)

🚀 How to run locally

Open the .mpr file in Mendix Studio Pro.

Click Run Locally (F5).

Wait until the build is finished.

Open your browser and go to http://localhost:8080
.

📁 Project Structure

/ (root)
├─ Zuiev_Illia.mpr — Main project file
├─ javasource/ — Java actions (if used)
├─ themesource/ — UI layouts and styles
├─ resources/ — Config files and assets
├─ userlib/ — External .jar libraries
└─ widgets/ — Custom widgets

🧱 Versioning

This project follows Semantic Versioning — https://semver.org

Format:
vMAJOR.MINOR.PATCH

Examples:

v1.0.0 → first stable release

v1.1.0 → new features added

v1.1.1 → small fixes and improvements

v5.0.0 → major release (current version)

You can create a new version by running:
git tag v5.0.0
git push origin v5.0.0

🧾 Changelog

v5.0.0 – Initial public release.

Added Slovak UI

Added pages for power and speed calculation

📜 License

MIT License © 2025 Illia Zuiev
You are free to use, copy, and modify this project for educational or personal purposes.

💡 Notes

Do not commit deployment/ or cache folders — they are automatically generated.

All libraries (.jar files) must be stored in userlib/.

You can export the project as .mpk for releases via App → Export App Package.
