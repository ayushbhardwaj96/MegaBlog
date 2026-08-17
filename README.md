# 📝 MegaBlog

<div align="center">

# 🚀 MegaBlog

### A Modern Blogging Platform Built with React

**Write • Create • Publish • Explore**

![MegaBlog 3-D Visual](assets/megablog-3d-visual.png)

[![GitHub](https://img.shields.io/badge/GitHub-ayushbhardwaj96-181717?logo=github)](https://github.com/ayushbhardwaj96)

</div>

---

## 🌟 About MegaBlog

**MegaBlog** is a modern blogging platform that I built while learning and applying **React, Vite, React Router, Redux Toolkit, Appwrite, reusable components, authentication, and rich content editing**.

The goal of this project is to create a complete blogging experience where users can authenticate themselves, create rich blog posts, browse all posts, and manage their content.

The project is still under development, with several social and post-management features planned for future versions.

---

## ✨ Features

### 🔐 Authentication
- User Sign Up
- User Login / Sign In
- Logout
- Authentication state management
- Protected routes

### 📝 Blog Features
- ➕ Add Post
- 📚 All Posts
- 👁️ View individual posts
- ✏️ Edit / Update Post *(work in progress)*
- 🗑️ Post management

### 🖊️ Rich Content Editor

MegaBlog uses a rich editor for creating blog posts.

The editor supports:

- 📄 Files / Documents
- 🖼️ Images
- 🎬 Media
- ✍️ Rich formatted content
- ➕ Add Post workflow

This allows posts to contain much more than plain text.

### 🎨 UI & Architecture
- Responsive interface
- Reusable React components
- Header and Footer
- React Router navigation
- Redux Toolkit state management
- Component-based architecture

---

## 🖼️ Screenshots

### 🔐 Sign Up

![MegaBlog Sign Up](assets/signup.jpg)

### 🔑 Login

![MegaBlog Login](assets/login.jpg)

### 📄 Sign Up Page & Footer

![MegaBlog Sign Up Full](assets/signup-full.jpg)

---

## 🧊 3-D Project Visual

MegaBlog also includes a 3-D visual to make the project presentation more engaging.

![MegaBlog 3-D Visual](assets/megablog-3d-visual.png)

The image is stored with the exact filename:

```text
assets/megablog-3d-visual.png
```

---

## 🔄 Application Flow

```text
                         ┌─────────────────┐
                         │    main.jsx     │
                         └────────┬────────┘
                                  │
                    ┌─────────────┴─────────────┐
                    │                           │
              ┌─────▼─────┐               ┌─────▼─────┐
              │   Redux   │               │   Router  │
              │   Store   │               │           │
              └─────┬─────┘               └─────┬─────┘
                    │                           │
                    └─────────────┬─────────────┘
                                  │
                           ┌──────▼──────┐
                           │    Pages    │
                           └──────┬──────┘
                                  │
              ┌───────────────────┼───────────────────┐
              │                   │                   │
         ┌────▼────┐         ┌────▼────┐         ┌────▼────┐
         │  Home   │         │  Login  │         │  Signup  │
         └─────────┘         └─────────┘         └─────────┘
              │
              ▼
       ┌──────────────┐
       │  All Posts   │
       └──────┬───────┘
              │
       ┌──────┴──────┐
       ▼             ▼
 ┌───────────┐  ┌───────────┐
 │  Add Post │  │ Edit Post │
 └─────┬─────┘  └─────┬─────┘
       │               │
       └───────┬───────┘
               ▼
        ┌──────────────┐
        │   Appwrite   │
        │    Backend   │
        └──────────────┘
```

---

## 🧱 Project Structure

```text
MegaBlog/
│
├── public/
│
├── src/
│   ├── appwrite/
│   │   ├── auth.js
│   │   └── config.js
│   │
│   ├── assets/
│   │   └── megablog-3d-visual.png
│   │
│   ├── components/
│   │   ├── Container/
│   │   ├── Footer/
│   │   ├── Header/
│   │   └── post-form/
│   │
│   ├── pages/
│   │   ├── AddPost.jsx
│   │   ├── AllPosts.jsx
│   │   ├── EditPost.jsx
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Post.jsx
│   │   └── Signup.jsx
│   │
│   ├── store/
│   │   ├── authSlice.js
│   │   └── store.js
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| ⚛️ React | Frontend |
| ⚡ Vite | Development & build tool |
| 🧭 React Router | Routing |
| 🔄 Redux Toolkit | State management |
| ☁️ Appwrite | Authentication & backend |
| 🖊️ Rich Text Editor | Blog content creation |
| 🎨 CSS / Tailwind CSS | Styling |
| 💻 JavaScript | Application logic |
| 🐙 Git & GitHub | Version control |

---

## 🔐 Authentication Flow

```text
Sign Up
   ↓
Create Account
   ↓
Login
   ↓
Authentication State
   ↓
Protected Routes
   ↓
MegaBlog
```

---

## 🚧 Project Status

MegaBlog is **not completely finished yet**. The main foundation and blogging workflow are being developed, while several important features are still pending.

### ✅ Completed / Implemented

- [x] Sign Up
- [x] Login
- [x] Authentication flow
- [x] Add Post
- [x] All Posts
- [x] Individual post viewing
- [x] Rich content editor
- [x] File / document support
- [x] Image support
- [x] Media support
- [x] React Router
- [x] Redux state management
- [x] Reusable components
- [x] Header and Footer

### ⏳ Pending Work

- [ ] Edit Post
- [ ] Update Post
- [ ] Delete Post improvements
- [ ] Following system
- [ ] Followers system
- [ ] Like system
- [ ] Comments and replies
- [ ] Bookmark posts
- [ ] User profiles
- [ ] Search and filtering
- [ ] Categories and tags
- [ ] Notifications
- [ ] Author dashboard
- [ ] Blog analytics
- [ ] Dark / Light mode
- [ ] Improved mobile UI

---

## 💡 Future AI Features

Once the core features are completed, I plan to make MegaBlog more powerful by adding AI-based functionality such as:

- 🤖 AI blog title generation
- ✍️ AI writing assistance
- 📝 AI content summarization
- 🏷️ Automatic tag generation
- 🔍 Semantic blog search
- 📊 AI-powered content insights
- 🛡️ Spam/toxicity detection

---

## 📚 What I Learned

Through MegaBlog, I learned and practiced:

- React component architecture
- React Hooks
- React Router
- Redux Toolkit
- Authentication
- Backend integration
- CRUD operations
- Rich text editors
- File and media handling
- Protected routes
- Reusable components
- Environment variables
- Git & GitHub
- Structuring a real-world React project

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/ayushbhardwaj96/MegaBlog.git
```

### 2. Navigate to the project

```bash
cd MegaBlog
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file and add your required credentials.

```env
VITE_APPWRITE_URL=your_appwrite_url
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
VITE_APPWRITE_BUCKET_ID=your_bucket_id
VITE_TINYMCE_API_KEY=your_tinymce_api_key
```

> ⚠️ Never upload `.env` or private API credentials to GitHub.

### 5. Start the development server

```bash
npm run dev
```

Open:

```text
http://localhost:5173
```

---

## 🤝 Contributing

Contributions and suggestions are welcome.

```bash
git checkout -b feature/new-feature
git add .
git commit -m "Add new feature"
git push origin feature/new-feature
```

Then create a Pull Request.

---

## 📄 License

This project is currently created for **learning, experimentation, and portfolio purposes**.

---

## 👨‍💻 Author

<div align="center">

### Ayush Ranjan

GitHub: **[@ayushbhardwaj96](https://github.com/ayushbhardwaj96)**

Built with ❤️ while learning and building modern web applications.

⭐ If you like MegaBlog, consider starring the repository!

</div>
