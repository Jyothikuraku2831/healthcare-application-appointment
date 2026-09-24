# Meridian Health — Patient Portal

Healthcare appointment booking portal built with HTML5, CSS3 & Bootstrap 5.

## Features
- Patient registration form (HTML5 validation)
- Dynamic appointments table
- Health info lookup

## Tech
HTML5 · CSS3 · Bootstrap 5 · JavaScript

## Run
Open `index.html` in a browser.

---

## 🚀 Getting Started

### Prerequisites
Nothing to install — just a web browser.

### Run Locally
1. Clone this repository
```bash
   git clone https://github.com/<your-username>/meridian-health-portal.git
```
2. Navigate into the project folder
```bash
   cd meridian-health-portal
```
3. Open `index.html` directly in your browser
```bash
   start index.html   # Windows
   open index.html    # macOS
```

No build tools, servers, or dependencies required.

---

## 🎯 How It Works

- All appointment data is stored **in-memory** using a JavaScript array (`appointments[]`)
- Submitting the registration form pushes a new appointment object into this array and re-renders the table
- Selecting an Appointment ID in the Health Information section pulls matching data from the same array
- **Note:** Data resets on page refresh since there is no backend/database persistence

---

## 🔮 Future Enhancements

- Connect to a backend (Node.js/Express + MongoDB or Firebase) for persistent data storage
- Add doctor login/admin dashboard to manage appointments
- Email/SMS appointment confirmation
- Search and filter functionality on the appointments table

---

## 👩‍💻 Author

**Jyothi** — 3rd Year, AI & Machine Learning
Front-end Web Development Project

---

## 📄 License

This project is created for academic/educational purposes.
