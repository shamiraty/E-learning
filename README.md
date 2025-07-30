# 📚 Educational Content Management System (Web + Android)

## 🔽 Download the Full System and Customize It as Your Own

This system includes two platforms working together:

- **Web Version** – For Admins to upload and manage educational content
- **Android Version** – For Students to view, search, and download videos or documents

---

## 🌐 WEB VERSION (ADMIN PANEL)

Admins can manage both **video tutorials** and **documents** for different education levels.

### 📥 1. Upload Video Tutorials
Admins can:
- Upload a **video file**
- Assign it to a **category** (e.g., "Science", "Social Science", "Lecture Tutorials")
- Add it to a **playlist**
- Upload a **thumbnail image**
- Set the **target audience** (e.g., Certificate, Diploma, Others)
- Add a **reference URL**
- Upload an extra **PDF document** (e.g., textbook)
- Write a **short description**
- Enter the **video title**

### 🛠️ 2. Manage Videos
Admins can:
- **Edit** or **delete** videos
- Create or update **video categories**
- Create or manage **video playlists**

### 📄 3. Manage Documents
Same features as video management, but for **documents**:
- Upload **PDF, DOCX, or EPUB** files (books, lecture notes)
- Categorize and group into playlists
- Upload thumbnails and extra resources
- Assign education level
- Provide links and descriptions

---

## 📱 ANDROID VERSION (FOR STUDENTS)

Students can:
- View educational **videos** or **documents**
- **Search** by category or target audience
- **Download** files for offline access

---

## 🛠️ HOSTING REQUIREMENTS

Choose your preferred hosting environment:

### ✅ Private Server
You can host the Laravel Admin Panel on your own server infrastructure.

### ✅ Shared Hosting
If you don't have a server, use any shared hosting that supports:
- PHP ≥ 8.1
- MySQL Database
- Apache or NGINX with `.htaccess` support

---

## 💻 TECHNOLOGIES USED

### 📱 Android Client (Student App)
- Kotlin (Jetpack Compose)
- Retrofit (API Integration)
- Built using Android Studio

### 🌐 Web Admin Panel
- Laravel (PHP Framework)
- MySQL (Database)
- Bootstrapwatch (Frontend theme)
- HTML, JavaScript, PHP

---

## 🧪 WEB DEMO PREVIEWS

You can add or remove API users and manage all content easily via the web admin panel.

### 🔐 API User Management
![API Users](https://github.com/user-attachments/assets/b936da5c-ec97-4e64-958d-69aefab076e9)

### 🔍 Specific API User Details
![API User Details](https://github.com/user-attachments/assets/bd439226-80bf-4a87-9fc7-5c68f09ef201)

### 📁 Video & Document Management Screenshots
![Management Panel](https://github.com/user-attachments/assets/705a2748-984d-4ce4-8c01-b299774e7434)
![Video Form](https://github.com/user-attachments/assets/eba43b9d-6f3b-43b4-a118-a840d9122d52)
![Playlist Settings](https://github.com/user-attachments/assets/0562a06f-4906-45b0-a2d5-94f4efa7448f)
![Video Category Settings](https://github.com/user-attachments/assets/7bf41162-0443-41c5-b2c1-76147c929fc2)
![Document View](https://github.com/user-attachments/assets/4871fd52-06f7-41fb-96ee-69b46b5804d3)

---

## 📲 ANDROID DEMO SCREENSHOTS

| Main Menu | Video Listing | Document Download |
|-----------|----------------|-------------------|
| ![Screenshot 1](https://github.com/user-attachments/assets/b593177a-0a8e-4dfc-9aab-098a4d731a23) | ![Screenshot 2](https://github.com/user-attachments/assets/e45798b1-53a1-4e27-8352-ee1e17afb4fd) | ![Screenshot 3](https://github.com/user-attachments/assets/d149c543-7799-44ac-8357-482dc3cdfe13) |

---

## ⚙️ INSTALLATION GUIDE

> If you are not familiar with system setup, contact an IT expert or the original seller for help.

### ✅ Prerequisites

Install the following software:

- [Android Studio](https://developer.android.com/studio)
- [XAMPP](https://www.apachefriends.org/index.html)
- [Composer](https://getcomposer.org/)
- [Laravel](https://laravel.com/docs)
- [Visual Studio Code](https://code.visualstudio.com/)

### ✅ Web Setup (Laravel Admin Panel)

1. Create a new MySQL database via **phpMyAdmin**
2. Import the provided `.sql` file
3. Copy `.env.example` to `.env`
4. Update the database credentials inside `.env`
5. Run:
   ```bash
   composer install
   php artisan key:generate
   php artisan migrate
   php artisan serve
