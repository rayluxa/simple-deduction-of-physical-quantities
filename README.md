Simple Deduction of Physical Quantities

Author: Ilya Zuev
Version: v5.0.0
Created with: Mendix Studio Pro

🧩 Description

This Mendix application demonstrates the calculation and deduction of basic physical quantities such as velocity, acceleration, and force using simple user inputs and formulas.
The project was developed for educational and demonstrational purposes.

⚙️ Technologies

Mendix Studio Pro (version used for development)

Atlas UI framework

Microflows and nanoflows

Java actions (if any were used)

Mendix built-in database

🚀 How to run locally

Open the .mpr file in Mendix Studio Pro.

Click Run Locally (F5).

Wait until the build is finished.

Open your browser and go to http://localhost:8080
.

📁 Project Structure

/ (root)
├─ MyApp.mpr — Main project file
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

📜 License

MIT License © 2025 Ilya Zuev
You are free to use, copy, and modify this project for educational or personal purposes.

💡 Notes

Do not commit deployment/ or cache folders — they are automatically generated.

All libraries (.jar files) must be stored in userlib/.

You can export the project as .mpk for releases via App → Export App Package.
