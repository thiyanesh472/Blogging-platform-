# 📝 Blogging Platform

A full-featured blogging platform that allows users to **create**, **edit**, **publish**, and **manage** blog posts easily.  
It includes user authentication, comment management, category tagging, and an intuitive admin dashboard.  


## 🚀 Features

- 🧑‍💻 **User Authentication** (Signup, Login, Logout)
- ✍️ **Create, Edit, Delete Blog Posts**
- 💬 **Comment System**
- 🏷️ **Category & Tag Management**
- 🔍 **Search & Filter Posts**
- 👤 **User Profile Management**
- 📰 **Responsive Design**
- ⚙️ **Admin Dashboard** for managing users, posts, and comments
- 🌐 **RESTful API Integration**


## 🏗️ Project Structure

blogging-platform/ │ ├── backend/ │   ├── server.js │   ├── routes/ │   ├── controllers/ │   ├── models/ │   └── config/ │ ├── frontend/ │   ├── src/ │   ├── public/ │   ├── components/ │   └── pages/ │ ├── .env ├── package.json ├── README.md └── LICENSE

## ⚙️ Tech Stack

| Layer | Technologies |
|-------|---------------|
| Frontend | React.js, Tailwind CSS, Axios |
| Backend | Node.js, Express.js |
| Database | MongoDB / PostgreSQL |
| Authentication | JWT (JSON Web Token) |
| Deployment | Render / Vercel / AWS |
| Version Control | Git & GitHub |

## 🧩 API Endpoints

### **Auth Routes**
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/api/auth/register` | Register a new user |
| POST | `/api/auth/login` | Login user |
| GET | `/api/auth/logout` | Logout user |

### **Post Routes**
| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | `/api/posts` | Get all posts |
| GET | `/api/posts/:id` | Get single post |
| POST | `/api/posts` | Create new post |
| PUT | `/api/posts/:id` | Update post |
| DELETE | `/api/posts/:id` | Delete post |

### **Comment Routes**
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/api/comments/:postId` | Add comment to a post |
| GET | `/api/comments/:postId` | Get comments for a post |

## 💻 Installation Guide

### Prerequisites
- Node.js (v16 or higher)
- MongoDB / PostgreSQL
- Git

### Steps
```bash
# 1. Clone the repository
git clone https://github.com/your-username/blogging-platform.git

# 2. Navigate into project folder
cd blogging-platform

# 3. Install dependencies
npm install

# 4. Configure environment variables
Create a `.env` file in root and add:
PORT=5000  
MONGO_URI=your_database_uri  
JWT_SECRET=your_secret_key  

# 5. Run the app
npm start

🧠 Future Enhancements

🌙 Dark/Light mode toggle

📱 Mobile app version

🧵 Rich text editor (Markdown / WYSIWYG)

📈 Analytics dashboard for authors

🧑‍🤝‍🧑 Multi-author collaboration


🛡️ License

This project is licensed under the MIT License — see the LICENSE file for details.

👨‍💻 Contributing

Contributions are welcome!
To contribute:

1. Fork the repository

2. Create a new branch (feature/your-feature-name)

3. Commit your changes

4. Push to your branch

5. Open a Pull Request

📬 Contact

For questions or feedback, reach out via:

Email: yourname@example.com

GitHub: yourusername
