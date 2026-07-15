# Appwrite Blog

A modern full-stack blogging platform built with **React**, **Redux Toolkit**, **Appwrite**, **TinyMCE**, and **Tailwind CSS**. Users can securely sign up, log in, create, edit, delete, and manage blog posts with image uploads and a rich text editor.

---
## Live Demo

Visit the live website here:

**Website:** https://appwrite-blog-nu-nine.vercel.app/

---
## Features

- User Authentication (Signup/Login/Logout)
- Rich Text Editor using TinyMCE
- Image Uploads with Appwrite Storage
- Create, Read, Update & Delete (CRUD) Blog Posts
- Protected Routes
- Responsive User Interface
- State Management using Redux Toolkit
- Backend powered by Appwrite
- Styled using Tailwind CSS

---

## Tech Stack

### Frontend

- React.js
- React Router DOM
- Redux Toolkit
- React Hook Form
- TinyMCE Editor
- Tailwind CSS

### Backend

- Appwrite
  - Authentication
  - TablesDB
  - Storage

---

## Project Structure

```
src/
│
├── appwrite/
│   ├── auth.js
│   └── config.js
│
├── components/
│   ├── Header/
│   ├── Footer/
│   ├── PostForm/
│   ├── Container/
│   └── ...
│
├── pages/
│   ├── Home.jsx
│   ├── Login.jsx
│   ├── Signup.jsx
│   ├── AddPost.jsx
│   ├── EditPost.jsx
│   ├── Post.jsx
│   └── AllPosts.jsx
│
├── store/
│   ├── authSlice.js
│   └── store.js
│
├── conf/
│   └── conf.js
│
├── App.jsx
└── main.jsx
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Appwrite-Blog.git
```

Navigate to the project directory

```bash
cd Appwrite-Blog
```

Install dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file in the root directory and add the following:

```env
VITE_APPWRITE_URL=YOUR_APPWRITE_ENDPOINT
VITE_APPWRITE_PROJECT_ID=YOUR_PROJECT_ID
VITE_APPWRITE_DATABASE_ID=YOUR_DATABASE_ID
VITE_APPWRITE_COLLECTION_ID=YOUR_TABLE_ID
VITE_APPWRITE_BUCKET_ID=YOUR_BUCKET_ID
VITE_TINYMCE_API_KEY=YOUR_TINYMCE_API_ID
```

---


## Pages

- Home
- Login
- Signup
- Add Post
- All Posts
- Single Post
- Edit Post

---

## Dependencies

- React
- React Router DOM
- Redux Toolkit
- React Hook Form
- TinyMCE
- Appwrite SDK
- Tailwind CSS

---

## Future Improvements

- Like and Comment System
- Search Functionality
- Categories and Tags
- Dark Mode
- User Profiles
- Dashboard
- Pagination
- Notifications

---




