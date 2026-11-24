# 🏡 ESTATEX – Global Real Estate Marketplace

ESTATEX is a modern full-stack real estate marketplace designed to help users discover, buy, rent, and list properties through a single digital platform.

It connects property buyers, tenants, property owners, real estate agents, and administrators with an easy-to-use interface and powerful property search features.

## 🌟 Project Overview

ESTATEX makes property discovery simple and convenient. Users can explore residential and commercial properties, view property details, compare options, contact agents, and schedule property visits.

The platform provides dedicated features for customers, property owners, agents, and administrators.

## 🎯 Problem Statement

Finding the right property can be difficult because property information is spread across multiple websites and agents. Customers may struggle to compare prices, locations, facilities, and availability.

ESTATEX solves this problem by providing a centralized real estate platform where users can search, compare, and manage property listings online.

## ✨ Key Features

### 👤 User Features
- User registration and login
- User profile management
- Browse available properties
- Search properties by location
- Filter properties by price and property type
- View detailed property information
- Save favourite properties
- Compare properties
- Contact property owners and agents
- Schedule property visits

### 🏠 Property Management
- Add new property listings
- Upload property images
- Edit property information
- Delete property listings
- Manage property availability
- Support residential and commercial properties
- Buy, rent, and lease property categories

### 🔍 Advanced Search
- Search by city and location
- Filter by minimum and maximum price
- Filter by bedrooms and bathrooms
- Filter by property type
- Filter by furnishing status
- Sort by price and latest listings

### 🧑‍💼 Agent Features
- Agent registration and login
- Create and manage property listings
- View customer enquiries
- Manage property visit appointments
- Update property information

### 🛠️ Admin Dashboard
- Admin authentication
- Manage users and agents
- Manage property listings
- Approve or reject listings
- Monitor customer enquiries
- Manage appointments
- View platform statistics

### 🤖 Smart Features
- AI-based property recommendations
- Property price estimation
- Interactive map integration
- Mortgage / EMI calculator
- Real-time property availability (planned)

## 💻 Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Website styling |
| JavaScript | Frontend functionality |
| Python | Backend programming |
| Flask | Backend web framework |
| SQLite | Database |
| Bootstrap | Responsive design (optional) |
| Google Maps API | Property location maps (optional) |

## 📂 Project Structure

```text
ESTATEX/
│
├── app.py
├── requirements.txt
├── README.md
├── .env.example
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── properties.html
│   ├── property_details.html
│   ├── add_property.html
│   ├── favourites.html
│   ├── dashboard.html
│   ├── agent_dashboard.html
│   └── contact.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│
├── database/
│   └── estatex.db
│
└── README.md
```

*This is a suggested project structure. Update it to match your actual files.*

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder

```bash
cd ESTATEX
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

### 6. Open in Browser

```text
http://127.0.0.1:5000
```

## 🔐 Security Features

- Secure password hashing
- User authentication
- Role-based access control
- Protected admin dashboard
- Input validation
- Secure session management
- Environment variables for secret keys

## 🚀 Future Enhancements

- AI-powered property recommendations
- Real-time chat between buyers and agents
- Online booking and payment integration
- Virtual property tours
- 360-degree property viewing
- Advanced location-based search
- Property price prediction
- Mobile application
- Multi-language support

## 🎯 Project Objectives

1. Build a complete real estate marketplace.
2. Make property searching easier and faster.
3. Connect buyers, sellers, tenants, and agents.
4. Provide property management functionality.
5. Develop a responsive and user-friendly interface.
6. Implement frontend, backend, and database integration.

## 👨‍💻 Project Information

| Detail | Information |
|---|---|
| Project Name | ESTATEX |
| Project Type | Full-Stack Web Application |
| Domain | Real Estate |
| Frontend | HTML, CSS, JavaScript |
| Backend | Python Flask |
| Database | SQLite |
| Version | 1.0.0 |

## 📜 Disclaimer

ESTATEX is an educational project. Property listings, prices, images, and availability may contain sample data. Actual property transactions and payments require appropriate verification and secure integrations.

---

⭐ If you find this project useful, consider giving the repository a star!

**Built with ❤️ for smarter property discovery.**
