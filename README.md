# TEAM NAME : 
 QUAD CORE (Members-4)

# PROJECT TITLE :
 PEER-TO-PEER RESOURCE HUB (sycet-013m)

 # WEBAPP NAME :
 CircleShare 

# DESCRIPTION : 
CircleShare is a web platform designed to eliminate the struggle of finding realiable study notes,previous year question paper (PYQ'S), and reference materials . Unlike a simple file sharing folder, this hub uses a social ranking system to ensure the most accurate and helpful content is easiest to find . it fosters a culture of collaborative learning where peers help each other by passing and sharing of curated resources.  

# SOLUTION :
 To build an effective solution ,we focused on:
    
    1) Organised Year-wise and Branch-wise content.
    2) Doubt session. 
    3) Easy to upload and download of a study materials.
    4) Preview of the resource.
    5) Contribution points for user engagement.
    6) Fast search functionality.
    7) Secure student login system.
    
## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#5032B6](https://dummyimage.com/10/#5032B6/white?text=+) #5032B6
| Example Color | ![#7F4AC3](https://dummyimage.com/10/#7F4AC3/white?text=+) #7F4AC3
| Example Color | ![#AB65D0](https://dummyimage.com/10/#AB65D0/white?text=+) #AB65D0
| Example Color | ![#FFFFFF](https://dummyimage.com/10/#FFFFFF/white?text=+) #FFFFFF


## 🌟 Features

### 🔐 Authentication System

* Email & Password Signup/Login
* Google Authentication
* Password Reset using Firebase Auth
* Persistent user sessions
* User profile creation

### 👤 User Profiles

* Editable profile
* Profile image support
* Branch & year information
* XP tracking
* Dynamic leaderboard ranking

### 📚 Resource Sharing

* Upload:

  * Notes
  * PYQs
  * Assignments
  * Practicals
  * Reference Books
  * Question Banks
* Cloudinary file hosting
* Preview & download resources
* Resource ratings system

### ❓ Doubt Section

* Ask doubts
* Answer other students’ questions
* Real-time doubt updates using Firestore

### 🏆 XP & Leaderboard

* Earn XP by:

  * Uploading resources (+20 XP)
  * Posting doubts (+5 XP)
  * Answering doubts (+10 XP)
* Dynamic ranking system
* Top contributors leaderboard

### 🎨 Modern UI

* Tailwind CSS styling
* Responsive design
* Dark mode support
* Animated gradients
* Glassmorphism effects

---

# 🛠️ Tech Stack

## Frontend

* HTML5
* Tailwind CSS
* Vanilla JavaScript

## Backend & Database

* Firebase Authentication
* Firebase Firestore

## Cloud Storage

* Cloudinary

---

# 📂 Project Structure

```bash
CircleShare/
│
├── signup.html
├── login.html
├── dashboard6.html
├── style.css
├── img/
│   ├── main_logo-removebg-preview.png
│   └── main_logo2-removebg-preview.png
│
└── README.md
```

---

# 🔥 Firebase Features Used

## Firebase Authentication

Used for:

* User signup
* User login
* Google login
* Password reset

---

## Firebase Firestore

Used for:

* Resources collection
* Doubts collection
* Ratings system

---

# ☁️ Cloudinary Integration

Resources are uploaded to Cloudinary using:

```javascript
https://api.cloudinary.com/v1_1/YOUR_CLOUD_NAME/auto/upload
```

Supported file formats:

* PDF
* DOCX
* PPT/PPTX
* PNG/JPG/JPEG

---

# ⚡ XP System

| Action          | XP     |
| --------------- | ------ |
| Upload Resource | +20 XP |
| Post Doubt      | +5 XP  |
| Answer Doubt    | +10 XP |

---

# 🏅 Leaderboard System

The leaderboard:

* Sorts users by XP
* Updates ranks dynamically
* Highlights current user
* Stores rankings in localStorage

---

# 🌙 Dark Mode

CircleShare includes:

* Light mode
* Dark mode toggle
* Persistent theme switching

---

# 🔎 Search & Filters

Users can:

* Search resources by name
* Search by subject
* Filter by:

  * Year
  * Branch

---

# 📱 Responsive Design

Optimized for:

* Desktop
* Tablet
* Mobile devices

---

# 🚀 How To Run The Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/circleshare.git
```

---

## 2️⃣ Open the Project

Open the project folder in:

* VS Code
* Sublime Text
* Any code editor

---

## 7️⃣ Run the Project

Simply open:

```bash
signup.html
```

or

```bash
login.html
```

in your browser.

---

# 📌 Future Improvements

* Real-time chat
* AI doubt assistant
* Notifications system
* Admin dashboard
* Resource approval system
* Bookmarking resources
* Better XP algorithms
* Full Firestore-based leaderboard
* Profile image upload
* Mobile app version

---

# 🧠 Learning Concepts Used

This project demonstrates:

* Firebase Authentication
* Firestore CRUD operations
* Cloudinary uploads
* Dynamic DOM manipulation
* Responsive UI design
* Local storage management
* Async/Await
* Tailwind CSS
* Dark mode implementation

---

# 👨‍💻 Developed By

* HTML
* Tailwind CSS
* JavaScript
* Firebase
* Cloudinary

---

# 📄 License

This project is open-source and free to use for educational purposes.

---

# ⭐ CircleShare

> Learn Together. Share Together. Grow Together.
