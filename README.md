# GitOpsCentral LMS

A Learning Management System (LMS) built with PHP and WordPress.  
This platform provides course management, user enrollment, quizzes, certificates, and a blogging system — all in one place.
---

## Features
- 📚 Course creation & management
- 👥 User registration & enrollment
- 📝 Quizzes, assignments & grading
- 🎓 Certificates on completion
- 💬 Discussion forums
- 📊 Progress tracking
- 🔐 Role-based access (Admins, Instructors, Students)
- 🌐 SEO-friendly blogging module
---

## Project Structure

gitopscentral-in/
├─ wordpress/ # WordPress installation
│ ├─ wp-content/
│ │ ├─ themes/ # Custom theme (LMS frontend)
│ │ ├─ plugins/ # Custom LMS plugin
│ │ └─ uploads/ # Media uploads (ignored in git)
├─ .gitignore
└─ README.md

## build

This is for the go build

```bash
go build -mod=vendor -o build
```



