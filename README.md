# 🔗 URL Shortener

This is a URL shortener application built with Node.js, Express, and MongoDB. It allows users to shorten URLs, track their visit history, and view analytics.

## 📋 Features

- 🔐 User authentication (signup and login)
- 🔗 URL shortening
- 📊 URL visit tracking
- 📈 URL analytics

## 📁 Project Structure



```
.  
├── 🚫 .gitignore               # Files to ignore in version control  
├── 🌐 connect.js               # Database connection setup  
├── 🧑‍💻 controllers/           # Controller logic  
│   ├── 🔗 url.js               # URL-related operations  
│   └── 👤 user.js              # User-related operations  
├── 🎯 index.js                 # Application entry point  
├── 🔧 middlewares/             # Middleware functions  
│   └── 🔐 auth.js              # Authentication middleware  
├── 🏗️ models/                  # Database models  
│   ├── 🔗 url.js               # URL schema  
│   └── 👤 user.js              # User schema  
├── 📦 package.json             # Project dependencies and scripts  
├── 🌍 routes/                  # Application routes  
│   ├── 🌐 staticRouter.js      # Static page routes  
│   ├── 🔗 url.js               # URL-related routes  
│   └── 👤 user.js              # User-related routes  
├── ⚙️ service/                 # Service logic  
│   └── 🔐 auth.js              # Authentication service  
└── 🌅 views/                   # Frontend views  
    ├── 🏠 home.ejs             # Home page  
    ├── 🔑 login.ejs            # Login page  
    └── 📝 signup.ejs           # Signup page

```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/pawan-r4ju/URL-SHORT.git
   cd URL-SHORT
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up MongoDB:
- 🛠️ Ensure MongoDB is installed and running on your machine.
- 🌐 Update the MongoDB connection URL in connect.js if necessary.

## ⚙️Usage

1. Start the server:
   ```bash
   npm start
   ```

2. Open your browser and navigate to:
   [http://localhost:8001](http://localhost:8001)

## 📚 API Endpoints

### 🌍 Public Endpoints
- **GET /** - 🏠 Home page
- **GET /signup** - 📝 Signup page
- **GET /login** - 🔑 Login page

### 👤 User Endpoints
- **POST /user** - 📝 Handle user signup
- **POST /user/login** - 🔑 Handle user login

### 🔗 URL Endpoints
- **POST /url** - ➡️ Generate a new short URL
- **GET /url/:shortId** - 🔄 Redirect to the original URL and track visits
- **GET /url/analytics/:shortId** - 📊 Get analytics for a specific short URL

## 📜 License

This project is licensed under the [ISC License](https://opensource.org/licenses/ISC).

## ✍️ Author
Pawan Raju
