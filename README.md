💰 **Finance Tracker**

A modern web-based personal finance management system that helps users track expenses, manage budgets, and visualize spending patterns through an interactive dashboard.

📌 **Overview**

Finance Tracker is designed to simplify personal financial management by providing a centralized platform where users can record transactions, monitor budgets, and gain insights into their spending habits. The application combines an intuitive user interface with data visualization tools to help users make informed financial decisions.

✨ **Features**
Add, view, and manage income and expense transactions
Set and update monthly budgets
Track category-wise spending
View total expenses and remaining budget
Interactive charts and financial insights using Chart.js
Responsive design for desktop and mobile devices
Secure data storage with database integration
REST-based communication between frontend and backend

🛠️ **Tech Stack**
Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- Chart.js
Backend
- Python
- Flask
Database
- SQLite
- 
🏗️ **System Architecture**
User
  │
  ▼
Frontend (HTML, CSS, JS, Bootstrap)
  │
  ▼
REST API Calls (Fetch API)
  │
  ▼
Flask Backend
  │
  ▼
SQLite Database

🚀 **Installation & Setup**
1. Clone Repository
git clone https://github.com/Ghost2507/Project-Works.git
2. Navigate to Project Directory
cd "dbms finance manager"
3. Install Dependencies
pip install flask flask-cors
4. Run Application
python app.py
5. Open Browser
http://127.0.0.1:5000

📂 **Project Structure**
Finance-Tracker/
│
├── app.py
├── finance_manager.db
├── templates/
│   └── base.html
│
├── frontend/
│   ├── index.html
│   ├── features.html
│   ├── how-it-works.html
│   ├── demo.html
│   ├── about.html
│   ├── contact.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       ├── script.js
│       └── api.js
│
└── README.md

📊 **Key Functionalities**
- Transaction Management
- Create new transactions
- View transaction history
- Delete transactions
- Categorize expenses
- Budget Management
- Set monthly budget
- Track spending against budget
- Calculate remaining balance
- Analytics Dashboard
- Expense summaries
- Category-wise spending distribution
- Real-time financial visualization
  
🧪 **Testing**
  Test Type	                   Status
- Frontend Functionality	    ✅ Passed
- Backend Routes	            ✅ Passed
- Database Connectivity	      ✅ Passed
- Responsive Design	          ✅ Passed

📈 **Project Outcomes**
- Managed and processed 200+ transaction records
- Implemented complete CRUD functionality
- Developed interactive financial dashboards
- Enabled budget monitoring and spending analysis
- Built a scalable and maintainable finance management solution
  
🔮 **Future Enhancements**
- User Authentication & Authorization
- Cloud Database Integration
- Monthly Report Generation
- AI-based Expense Prediction
- Mobile Application Support
- Data Export (PDF/Excel)
