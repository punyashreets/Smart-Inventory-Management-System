# 🏢 Smart Inventory Management System

A comprehensive inventory management system for small businesses with user authentication, role-based access control, and real-time inventory tracking.

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Web Browser

### Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/punyashreets/Smart-Inventory-Management-System
cd Smart-Inventory-Management-System
```

2. **Create virtual environment**
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the application**
```bash
python app.py
```

5. **Open in browser**
```
http://localhost:5000
```

### Default Login Credentials
- **Username**: `admin`
- **Password**: `Admin@123`

## 📁 Project Structure

```
Smart Inventory Management System/
├── backend/              # Backend logic (authentication, inventory, reports)
├── database/            # Database schema and connection utilities
├── frontend/            # HTML/CSS/JS frontend files
│   ├── css/            # Stylesheets
│   ├── js/             # JavaScript files
│   └── *.html          # HTML pages
├── tests/              # Test files
├── docs/               # Documentation
│   ├── README.md       # Detailed setup guide
│   ├── PRD.md          # Product Requirements Document
│   ├── SETUP_GUIDE.md  # Complete installation guide
│   └── API_DOCUMENTATION.md
├── app.py              # Main Flask application
├── config.py           # Configuration settings
├── requirements.txt    # Python dependencies
└── .env.example        # Environment variables template
```

## ✨ Features

### ✅ Milestone 1 - Complete (Weeks 1-2)
- **User Authentication**: JWT-based login and registration
- **Role Management**: Admin and Employee roles
- **Password Security**: Bcrypt hashing
- **Session Management**: Token-based authentication
- **Profile Management**: Password reset functionality

### ✅ Milestone 2 - Complete (Weeks 3-4)
- **Product Management**: Full CRUD operations for products
- **SKU Management**: Unique product identification
- **Stock Tracking**: Real-time inventory levels
- **Stock Operations**: Stock-in, stock-out, and adjustments
- **Movement History**: Complete audit trail of stock changes
- **Categories & Suppliers**: Organized product classification
- **Search & Filters**: Advanced product search and filtering
- **Low Stock Detection**: Automatic identification of low stock items


### 🔔 Milestone 3 (Week 5): Low-Stock Alerts & Notifications
This module focuses on intelligent inventory monitoring to prevent stock shortages.

- Define minimum stock thresholds for each product
- Allow admins to configure custom alert levels
- Automatically detect low-stock conditions
- Display real-time alerts on the dashboard
- Send notifications (Email/SMS) to responsible staff

👉 Outcome: Ensures timely restocking and avoids inventory shortages.

---

### 📦 Milestone 4 (Weeks 6–7): Transaction Management
This module enables complete tracking of inventory movements through structured transactions.

- Record all purchase and sales transactions
- Capture details like product name, quantity, type, date, and user
- Maintain a full audit trail of stock changes
- Automatically update stock levels based on transactions
- Provide real-time reflection of inventory changes

👉 Outcome: Improves transparency, accountability, and accurate stock tracking.

---

### 📊 Milestone 5 (Week 8): Reports & Export System
This module provides analytical insights and reporting capabilities for better decision-making.

- Generate inventory summary reports
- Include stock levels, product details, and transaction history
- Filter reports by date, category, or supplier
- Export reports in PDF and CSV formats
- Enable download or sharing of reports

👉 Outcome: Helps in data-driven decision-making and business analysis.


## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: Python Flask
- **Database**: SQLite (Development) / MySQL (Production)
- **Authentication**: JWT (JSON Web Tokens)
- **Security**: Bcrypt password hashing

## 📖 Documentation

Detailed documentation is available in the `docs/` folder:
- [Setup Guide](docs/SETUP_GUIDE.md) - Complete installation instructions
- [Product Requirements](docs/PRD.md) - Full PRD with all milestones
- [API Documentation](docs/API_DOCUMENTATION.md) - API endpoints reference
- [Git Workflow](docs/GIT_WORKFLOW.md) - Contribution guidelines

## 🔐 Security Features

- JWT-based authentication with 24-hour token expiry
- Bcrypt password hashing
- Role-based access control (RBAC)
- Input validation and sanitization
- SQL injection prevention

## 🧪 Testing

Run tests:
```bash
python -m pytest tests/
```

## 📝 License

This project is part of academic coursework.

## 👥 Contributors

- Project Team

## 📞 Support

For issues or questions, please create an issue in the GitHub repository.

---

**Last Updated**: March 28, 2026  

