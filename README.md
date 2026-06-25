# 📝 Blog App

A full-stack Blog Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). Users can create, edit, delete, and view blog posts with image uploads, category filtering, authentication, and comments.

## 🚀 Features

### User Authentication
- User Registration
- User Login & Logout
- JWT Authentication
- Protected Routes

### Blog Management
- Create New Posts
- Edit Existing Posts
- Delete Posts
- Upload Featured Images
- View Single Blog Post
- View All Posts

### Categories
- Technology
- Sports
- Food
- Travel
- Filter Posts by Category

### Comments
- Add Comments on Posts
- View Comments

### Responsive Design
- Mobile Friendly
- Modern UI
- Easy Navigation

---

## 🛠️ Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JSON Web Token (JWT)
- bcryptjs

### File Upload
- Multer

---

## 📂 Project Structure

```
blog-app/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── context/
│   │   └── utils/
│   │
│   └── public/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── uploads/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/blog-app.git
cd blog-app
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start Backend Server:

```bash
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:

```bash
http://localhost:5173
```

Backend will run on:

```bash
http://localhost:5000
```

---

## 📸 Screenshots

### Home Page
<img width="1896" height="995" alt="image" src="https://github.com/user-attachments/assets/a21780f8-5d19-49bf-9cad-cbc83a6c30eb" />
<img width="1903" height="994" alt="image" src="https://github.com/user-attachments/assets/482fd179-3331-4bee-9883-c9deb7cb16b9" />

### Post Details
<img width="1902" height="1002" alt="Screenshot 2026-06-25 214811" src="https://github.com/user-attachments/assets/ca11577e-4334-4382-b7ce-bb00aa38948a" />
<img width="1912" height="1001" alt="image" src="https://github.com/user-attachments/assets/f9d2cee5-0b63-42e6-aa81-e4908bdedb29" />

### Add Post
<img width="1386" height="994" alt="image" src="https://github.com/user-attachments/assets/8cecdcdb-3196-4ef2-954a-ab5c6177f5f2" />
### Edit Post
<img width="1292" height="865" alt="Screenshot 2026-06-25 215121" src="https://github.com/user-attachments/assets/5d10e8a8-a239-4b2f-91f1-ce3ec1775fd4" />

<img width="1180" height="785" alt="image" src="https://github.com/user-attachments/assets/2d948f50-c9f0-468c-88d3-e169ad348ed5" />

### Authentication
<img width="1356" height="983" alt="image" src="https://github.com/user-attachments/assets/6365846a-0e43-4005-a8ba-03ce28c14caa" />
<img width="1104" height="886" alt="image" src="https://github.com/user-attachments/assets/115f09a6-cb05-4377-89c8-0a78fae7697f" />

---

## 🔐 Environment Variables

Backend `.env`

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```

---

## 🎯 Future Improvements

- Like & Dislike Posts
- User Profiles
- Search Functionality
- Rich Text Editor
- Dark Mode
- Pagination
- Admin Dashboard

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Mahi Gupta
