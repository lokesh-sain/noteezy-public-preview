# Noteezy 📝 (Full Stack Preview)

**Notes Made Simple.** A production‑grade, full‑stack note‑taking application inspired by Google Keep. Built to be simple, fast, and secure.

> **⚠️ DISCLAIMER: PUBLIC PREVIEW**  
> This is a public preview repository for the **Noteezy** project.  
> The **Source Code** for both Client (React) and Server (Node.js) is currently **private**.  
>  
> **Recruiters / Hiring Managers:**  
> Please contact me at **lokesh.sainlks@gmail.com** for a code walkthrough or temporary access request.

![Noteezy Banner](https://res.cloudinary.com/videotube-new/image/upload/v1764936085/Noteezy-HomePage_eqrryf.png)

---

## 🚀 Live Demo  
**🔗 https://noteezy.lokeshsain.com**

---

# 🧭 Project Structure (Frontend + Backend)

Noteezy consists of two private repositories:

## **1. Frontend (Private Repo)**

- React 19  
- Redux Toolkit + RTK Query  
- React Router v7  
- Tailwind CSS  
- React Hook Form  
- Axios (custom base query)  
- Masonry Grid Layout  
- Dark/Light Theme  
- Complete UI + Optimistic Updates  

---

## **2. Backend (Private Repo)**

- Node.js + Express  
- MongoDB + Mongoose  
- JWT with HttpOnly Cookies  
- Multer + Cloudinary (Media uploads)  
- Node-Cron (Automated cleanup)  
- Fully modular controller + route architecture  

---

# 🔌 Backend Capabilities Summary

The backend exposes a secure REST API with **23 controller functions**, covering:

### 🔐 Authentication
- Register  
- Login  
- Logout  
- Get Current User  
- Refresh Access Token  

### 📝 Notes Management
- Create notes (text + image)  
- Update notes  
- Archive / Unarchive  
- Pin / Unpin  
- Move to Trash  
- Restore notes  
- Permanently delete  
- Auto-clean trash after 7 days (cron job)  

### 🤝 Sharing & Collaboration
- Share note with another user  
- Remove user access  
- Leave shared note  
- Retrieve shared notes  
- Get signed media URLs  

The API follows **robust error handling**, **token validation**, and **secure permission checks**.

---

# 🧩 System Architecture

```
Frontend: React + RTK Query + Tailwind
          ↓ Axios (custom base query)
Backend:  Node.js + Express + MongoDB
          ↓ Cloudinary (Media Storage)
          ↓ Node-Cron (Automated Jobs)
Auth:     JWT in HttpOnly Cookies + Refresh Token Rotation
```

### **Authentication and data flow**
```
Login → Set HttpOnly Cookie → Access Token for API → Auto Refresh → Secure Actions
```

---

# ✨ Core Features

### 🎨 Beautiful, Smart UI
- Responsive masonry grid  
- Theme switching  

### ⚡ Instant Actions (Optimistic UI)
- Archive, delete, pin — instant with RTK Query  

### 🔒 Best‑Practice Security
- Tokens not stored in localStorage  
- HttpOnly cookies protect against XSS  
- Validated API access  
- Signed media URLs  

### 🌐 Media Handling
- Upload, preview, update, remove note images  

### 🧹 Automated Cleaning
- Notes in Trash older than **7 days** auto‑deleted via cron job  

---

## 📸 Screenshots

### 🌗 Theme Support  
| Light Mode | Dark Mode |
| :---: | :---: |
| ![Light](https://res.cloudinary.com/videotube-new/image/upload/v1764936085/Noteezy-HomePage_eqrryf.png) | ![Dark](https://res.cloudinary.com/videotube-new/image/upload/v1764936083/Noteezy-HomePage-Dark_scelnf.png) |

### 🔐 Authentication  
| Login | Signup |
| :---: | :---: |
| ![Login](https://res.cloudinary.com/videotube-new/image/upload/v1764936083/Noteezy-LoginPage_mr9to8.png) | ![Signup](https://res.cloudinary.com/videotube-new/image/upload/v1764936084/Noteezy-SignupPage_lwvbao.png) |

### 📝 Note Management  
| Create Note | Update Note |
| :---: | :---: |
| ![Create](https://res.cloudinary.com/videotube-new/image/upload/v1764936083/Noteezy-CreateNoteModal_hwnskm.png) | ![Update](https://res.cloudinary.com/videotube-new/image/upload/v1764936102/Noteezy-UpdateNoteModal_vvulvf.png) |

### 📂 Organization  
| Shared Notes | Trash | Archive |
| :---: | :---: | :---: |
| ![Shared](https://res.cloudinary.com/videotube-new/image/upload/v1764936086/Noteezy-SharedPage_or2zro.png) | ![Trash](https://res.cloudinary.com/videotube-new/image/upload/v1764936099/Noteezy-TrashPage_plyfdy.png) | ![Archive](https://res.cloudinary.com/videotube-new/image/upload/v1764936083/Noteezy-ArchivePage_hnoobu.png) |

---

## 👨‍💻 Developed By  
**Lokesh Sain — MERN Stack Developer**

📧 Email: **lokesh.sainlks@gmail.com**  
🌐 Portfolio: **https://lokeshsain.com**
GitHub: **https://github.com/lokesh-sain**

---

© 2025 Noteezy — All rights reserved.
