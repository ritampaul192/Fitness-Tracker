# 📁 Final Project File Structure

## ✅ **Final File Structure**
```
📁 project-root/
│── 📁 assets/              # Stores images, icons, fonts, avatars
│   ├── avatars/           # User profile avatars (10 options)
│   ├── images/            # Other UI images/icons
│
│── 📁 config/              # Configuration files
│   ├── db.js              # MongoDB connection setup
│   ├── env.js             # Environment variables setup
│
│── 📁 controllers/         # Handles backend logic (API requests)
│   ├── authController.js   # User authentication (login, register)
│   ├── userController.js   # User profile & health tracking logic
│   ├── progressController.js # Progress tracking logic
│
│── 📁 models/              # Database Schemas (MongoDB + Mongoose)
│   ├── User.js            # User Schema (Name, email, password, gender)
│   ├── Health.js          # Health data schema (BMI, weight, meal intake, etc.)
│   ├── Progress.js        # Progress tracking schema
│
│── 📁 routes/              # Defines API endpoints
│   ├── authRoutes.js      # Authentication routes (login, register)
│   ├── userRoutes.js      # Routes for user-related operations
│   ├── progressRoutes.js  # Routes for progress tracking
│
│── 📁 middleware/          # Middleware functions
│   ├── authMiddleware.js  # JWT Authentication middleware
│
│── 📁 utils/               # Utility/helper functions
│   ├── helpers.js         # Helper functions (e.g., BMI calculation)
│
│── 📁 public/              # Static files accessible by frontend
│   ├── css/               # Stylesheets
│   │   ├── styles.css     # Main CSS file
│   │   ├── dark-mode.css  # Dark mode styles
│   │
│   ├── js/                # Client-side JavaScript
│   │   ├── main.js        # UI interactions, API calls
│   │   ├── charts.js      # Chart.js integration for data visualization
│   │   ├── gamification.js # Handles badges, rewards
│   │
│   ├── pages/             # Different UI pages
│   │   ├── index.html     # Homepage
│   │   ├── login.html     # Login page
│   │   ├── register.html  # Registration page
│   │   ├── dashboard.html # User dashboard (health tracking, progress)
│   │
│   ├── components/        # Reusable HTML components
│   │   ├── navbar.html    # Navigation bar
│   │   ├── footer.html    # Footer
│
│── 📄 server.js            # Main backend entry file (Node.js + Express)
│── 📄 package.json         # Dependencies & scripts
│── 📄 .env                 # Environment variables (MongoDB URI, JWT secret)
│── 📄 README.md            # Project Documentation
```

---

## 📌 **Explanation of Key Folders**

### **1️⃣ assets/**
- Contains images, icons, and avatars.
- `avatars/`: Stores 10 different profile avatars.
- `images/`: Stores UI images and icons.

### **2️⃣ config/**
- `db.js`: Connects MongoDB database.
- `env.js`: Stores environment variables (like API keys, DB URI).

### **3️⃣ controllers/**
- Handles backend logic.
- `authController.js`: Manages user authentication (login/register).
- `userController.js`: Manages user data like profile and health tracking.
- `progressController.js`: Tracks user progress, badges, and rewards.

### **4️⃣ models/**
- Defines MongoDB schemas using Mongoose.
- `User.js`: Stores user details (name, email, gender, password, etc.).
- `Health.js`: Stores BMI, weight, meal intake, etc.
- `Progress.js`: Tracks user progress data.

### **5️⃣ routes/**
- Defines Express.js API endpoints.
- `authRoutes.js`: Authentication routes (`/login`, `/register`).
- `userRoutes.js`: User-related operations (`/profile`, `/update-health`).
- `progressRoutes.js`: Handles progress tracking (`/track-progress`).

### **6️⃣ middleware/**
- Contains middleware functions.
- `authMiddleware.js`: Protects routes using JWT authentication.

### **7️⃣ utils/**
- Contains helper functions.
- `helpers.js`: Functions like BMI calculation, progress percentage.

### **8️⃣ public/**
- Contains frontend static files.
- `css/`: Stylesheets for UI.
- `js/`: JavaScript files (UI interactions, gamification, Chart.js integration).
- `pages/`: HTML pages like `index.html`, `login.html`, `dashboard.html`.
- `components/`: Reusable UI components like `navbar.html`, `footer.html`.

### **9️⃣ server.js**
- Main backend entry file (Express.js application).

### **🔟 package.json**
- Lists dependencies (Express.js, Mongoose, bcrypt, JWT, etc.).

### **🔟 .env**
- Stores sensitive data like database URI and JWT secret.

### **🔟 README.md**
- Documentation for the project.

---

## 🔥 **Next Steps**
- ✅ **Set up Express.js server**
- ✅ **Implement MongoDB schemas**
- ✅ **Design and implement UI pages**
- ✅ **Connect frontend with backend via API calls**
- ✅ **Add Chart.js for health progress visualization**
- ✅ **Implement gamification features (badges, rewards)**

Let me know if you need code samples or a guide for specific features! 🚀
