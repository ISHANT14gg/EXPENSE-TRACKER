# 💰 Expense Tracker – MERN Stack Application

<div align="center">

![Expense Tracker](https://img.shields.io/badge/MERN-Stack-success?style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)

A full-stack web application to manage daily expenses efficiently with secure authentication and clean UI.

**[🔗 Live Demo](https://expense-tracker-gamma-rust-93.vercel.app/)** • **[📂 View Code](https://github.com/ISHANT14gg/EXPENSE-TRACKER)**

</div>

---

## ✨ Features

- 🔐 **User Authentication** - Secure register/login functionality
- 🔒 **JWT Security** - Token-based authentication
- ➕ **Add Expenses** - Create new expense entries
- 👁️ **View Expenses** - Track all your expenses in one place
- 🗑️ **Delete Expenses** - Remove unwanted entries
- 📊 **Total Tracking** - Real-time expense calculations
- 🎨 **Responsive Design** - Works seamlessly on all devices
- 🧠 **Clean Architecture** - Well-structured REST API

---

## 🛠️ Tech Stack

### Frontend
```
⚛️ React.js         - UI Framework
🔄 Axios            - HTTP Client
🎨 CSS/Tailwind     - Styling
```

### Backend
```
🟢 Node.js          - Runtime Environment
⚡ Express.js       - Web Framework
🍃 MongoDB          - Database
📦 Mongoose         - ODM Library
🔐 JWT              - Authentication
🔒 bcrypt           - Password Hashing
```

---

## 🌐 Live Deployment

The application is deployed and live using modern cloud platforms:

### 🔗 Live URL
**Frontend:** [https://expense-tracker-gamma-rust-93.vercel.app/](https://expense-tracker-gamma-rust-93.vercel.app/)

### Deployment Architecture

| Component | Platform | Status |
|-----------|----------|--------|
| Frontend | Vercel | ✅ Live |
| Backend | Render | ✅ Live |
| Database | MongoDB Atlas | ✅ Live |

#### Frontend (Vercel)
- ⚡ Built with React
- 🔄 Auto-deploy from GitHub
- 🌍 Global CDN distribution
- ⚙️ Environment variables configured

#### Backend (Render)
- 🟢 Node.js & Express server
- 🔗 Connected to MongoDB Atlas
- 🔄 Auto-deploy on git push
- 🔒 Secure environment variables

---

## 📁 Project Structure

```
expense-tracker/
│
├── backend/
│   ├── controllers/       # Request handlers
│   ├── models/           # MongoDB schemas
│   ├── routes/           # API routes
│   ├── middleware/       # Auth & validation
│   ├── server.js         # Entry point
│   └── .env              # Environment variables
│
├── frontend/
│   ├── src/
│   │   ├── components/   # React components
│   │   ├── pages/        # Page components
│   │   ├── services/     # API calls
│   │   └── App.jsx       # Main app component
│   └── package.json
│
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- MongoDB (local or Atlas)
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/ISHANT14gg/EXPENSE-TRACKER.git
cd EXPENSE-TRACKER
```

2. **Backend Setup**
```bash
cd backend
npm install
```

Create `.env` file in backend folder:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start backend server:
```bash
npm start
```

3. **Frontend Setup**
```bash
cd frontend
npm install
npm start
```

4. **Access the application**
```
http://localhost:3000
```

---

## 🔗 API Endpoints

### Authentication
| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/auth/register` | Register new user |
| `POST` | `/api/auth/login` | Login user |

### Expenses
| Method | Endpoint | Description |
|--------|----------|-------------|
| `GET` | `/api/expenses` | Get all expenses |
| `POST` | `/api/expenses` | Add new expense |
| `DELETE` | `/api/expenses/:id` | Delete expense |

---

## 📈 Future Enhancements

- 📊 **Expense Analytics** - Visual charts and graphs
- 💵 **Budget Limits** - Set monthly spending limits
- 🏷️ **Categories** - Filter expenses by category
- 🔐 **OAuth Login** - Google authentication
- 📥 **Export Data** - Download expenses as CSV/PDF
- 🔔 **Notifications** - Budget limit alerts
- 🌙 **Dark Mode** - Theme toggle
- 📱 **Mobile App** - React Native version

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Ishant Sharma**

- 📧 Email: ishant6589@gmail.com
- 💼 GitHub: [@ISHANT14gg](https://github.com/ISHANT14gg)
- 💼 LinkedIn: [Ishant Sharma](https://www.linkedin.com/in/ishant-sharma888/)

---

<div align="center">

### ⭐ If you like this project, don't forget to star the repository!

**Made with ❤️ using MERN Stack**

</div>
