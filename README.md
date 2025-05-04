# FINAL PROJECT
# nourishED minds - Meal Tracking App
---

### Project Overview
**nourishED minds** is a web-based meal tracking application designed to help rural schools track daily meals given to students. The app is built to be easy to use for teachers and administrators, even in areas with limited internet connectivity. It provides a simple interface to log and track meals for children who depend on school feeding programs to fight hunger and improve their focus on education.

This tool allows:
- Easy logging of meals given to each student.
- Offline access for use in rural schools with limited internet.
- Simple and fast interface for teachers and administrators.
- Secure data storage and potential backend integration for advanced features.

---

### Features
- **Student List & Meal Tracking**: Log meals given to each student on a daily basis.
- **Offline Mode**: Works even without an internet connection (Progressive Web App ready).
- **User-Friendly Interface**: Simple and easy-to-navigate UI for teachers and school administrators.
- **Secure Data**: Data stored locally or can be configured for cloud storage in future iterations.

---

### Tech Stack
The app is built using the following technologies:

- **Frontend**: 
  - HTML
  - CSS
  - JavaScript
  - PWA (Progressive Web App) support
  
- **Backend**:
  - **Flask** (Python) – For backend API services and logic (to be implemented in future versions)
  
- **Storage**:
  - **LocalStorage/JSON** (for offline capabilities)
  - **SQLite** (for future use with backend integration)

---

### Installation Instructions
1. Clone the repository:
   git clone https://github.com/yourusername/nourishED-minds.git
2. Navigate to the project folder:
3. Open the project:You can open the index.html file in any modern browser to view the app.
4. Run the app:
5. Backend Setup:
When Flask is implemented for the backend, install the necessary Python dependencies using bash:
pip install -r requirements.txt
6. Then run the Flask server:
python app.py

### Usage
Add Student:

Click the “Add Student” button to add a student to the meal tracker.
Fill out the form with the student’s name and click “Add.”

Track Meal:

For each student, a “Meal Given” button will appear. Click this button each time a student is given a meal.

Offline Usage:

The app works offline, and all data is saved in your browser's local storage.
You can continue logging meals even without an internet connection.

### Contributors
Joy Wucha – Founder & Lead Developer







