<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&duration=3500&pause=900&color=16A34A&center=true&vCenter=true&width=720&height=80&lines=YelpCamp;Discover+%26+share+campgrounds;A+full-stack+Node.js+app" alt="YelpCamp" />

### 🏕️ Find, review, and share campgrounds around the world

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=black)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white)

</div>

---

## 🧭 Overview

**YelpCamp** is a full-stack web application where users can discover campgrounds, add their own, and leave reviews. Every campground has a location pinned on an interactive map, photo galleries, and a star-rated review section. It's a complete CRUD app with authentication, authorization, image hosting, and production-grade security middleware.

## ✨ Features

- 🏕️ **Campground CRUD** — create, view, edit, and delete campgrounds
- ⭐ **Reviews & ratings** — leave star-rated reviews on any campground
- 🔐 **Authentication** — register and log in with Passport.js
- 🛡️ **Authorization** — only owners can edit/delete their content
- 🖼️ **Image uploads** — multiple photos per campground via Cloudinary
- 🗺️ **Interactive maps** — clustered map of all campgrounds (Mapbox)
- ✅ **Server-side validation** — request validation with Joi
- 🚨 **Flash messages** — friendly success/error feedback
- 🔒 **Security hardening** — Helmet, mongo-sanitize, and sanitized inputs

## 🛠️ Tech Stack

| Layer | Technologies |
| --- | --- |
| Runtime | Node.js |
| Server | Express |
| Database | MongoDB, Mongoose |
| Views | EJS, ejs-mate |
| Auth | Passport.js (local strategy) |
| Media | Cloudinary, Multer |
| Maps | Mapbox |
| Validation & Security | Joi, Helmet, express-mongo-sanitize |

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm
- A MongoDB database (local or Atlas)
- Cloudinary and Mapbox accounts

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Keshavkumar04/Camp.git
cd Camp

# 2. Install dependencies
npm install

# 3. Configure environment variables (see below)

# 4. (Optional) seed the database with sample campgrounds
node seeds/index.js

# 5. Start the app
npm start
```

### Environment Variables

Create a `.env` file in the project root:

```env
DB_URL="mongodb+srv://..."
CLOUDINARY_CLOUD_NAME=""
CLOUDINARY_KEY=""
CLOUDINARY_SECRET=""
MAPBOX_TOKEN=""
SECRET="your-session-secret"
```

## 📁 Project Structure

```
Camp/
├── app.js            # Express app entry point
├── models/           # Mongoose models: campground, review, user
├── controllers/      # Route logic: campgrounds, reviews, users
├── routes/           # Express routers
├── views/            # EJS templates
├── public/           # CSS & client-side JS (maps, validation)
├── seeds/            # Database seeding scripts
├── utils/            # Error helpers (catchAsync, ExpressError)
├── middleware.js     # Auth & validation middleware
└── schema.js         # Joi validation schemas
```

<div align="center">

---

Built with 💚 by [**Keshav Kumar**](https://github.com/Keshavkumar04)

</div>
