# 📰 TechNews Blog App

A simple blog web application built using **Node.js**, **Express.js**, and **EJS** templating.  
Users can create, view, and delete blog posts with images and metadata such as title, category, writer, and date.

---

## ✨ Features

- 🖊 Create new blog posts with image uploads
- 📃 View all blog posts
- 📄 View single post by slugified title (dynamic route)
- ❌ Delete individual posts
- 🌐 Responsive UI with a modern navbar (mobile-friendly)

---

## 📦 Tech Stack

- **Backend**: Node.js, Express.js
- **Templating**: EJS
- **File Upload**: Multer
- **Styling**: Custom CSS
- **Static Assets**: Served from `/public`

---

## 🚀 How to Run Locally

### 1. 📥 Clone the Repository

```bash
git clone https://github.com/yourusername/technews-blog.git
cd technews-blog
```

### 2. 📦 Install Dependencies
```bash
npm install
```

### 3. 🏃 Run the App
```bash
node app.js
```

## 📁 Project Structure
├── public/
│ ├── images/ # Static images (e.g., logo, default assets)
│ └── uploads/ # Uploaded blog images
├── views/
│ ├── partials/
│ │ ├── header.ejs # Shared header (navbar, logo, etc.)
│ │ └── footer.ejs # Shared footer (copyright)
│ ├── index.ejs # Home page with list of posts
│ ├── create.ejs # Blog creation form
│ └── post.ejs # Single post view
├── app.js # Main Express server file
