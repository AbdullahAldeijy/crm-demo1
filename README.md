# Mizzanine CRM Platform

A comprehensive B2B construction marketplace and CRM system built with Flask, featuring bilingual support (English/Arabic), company management, product catalog, payment systems, and task management.

## Features

### Core Functionality
- **Bilingual Support**: Full English and Arabic language support with RTL layout
- **Company Management**: Multi-company platform with 7 pre-configured companies
- **Product Catalog**: Complete product management with inventory tracking
- **Department Hierarchy**: 10 specialized Arabic departments with role-based access
- **Purchase Orders**: Order management with rating system for completed orders
- **Task Management**: Create, assign, and track tasks with rewards
- **Chat System**: Real-time messaging between companies
- **Payment Integration**: Torbiona payment gateway with installment plans (20%, 40%, 25%, 15%)
- **Contract Generation**: PDF contracts and POS printer receipts using ReportLab
- **Dark Mode**: Toggle dark mode with localStorage persistence
- **Notification System**: Enhanced notification modal with announcements

### User Roles & Permissions
- **Manager**: Full access to all features
- **Sales**: Product management and marketplace access
- **Purchase**: Order creation and rating
- **Marketing**: Company page management
- **HR**: Employee management
- **Finance**: Financial operations
- **IT**: Technical support
- **Logistics**: Delivery services
- **Quality**: Quality control
- **Legal**: Contract management

## Installation

### Prerequisites
- Python 3.8+
- pip

### Setup
```bash
# Clone the repository
git clone https://github.com/AbdullahAldeijy/crm-demo1.git
cd crm-demo1

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

The application will be available at `http://localhost:5000`

## Project Structure

```
crm-demo/
├── app.py                      # Main Flask application
├── requirements.txt            # Python dependencies
├── static/
│   ├── style.css              # Main stylesheet with dark mode
│   ├── app.js                 # CRM functionality and dark mode
│   └── payment.js             # Payment window functionality
└── templates/
    ├── index.html             # Main platform landing page
    ├── crm.html               # CRM dashboard
    ├── company.html           # Company profile pages
    └── torbiona_calculator.html # Payment plan calculator
```

## Usage

### Login Credentials

**Company Login:**
- Username: `binladin` (or any company name)
- Password: `admin123`

**Employee Login:**
- Username: `ahmed.manager` (format: firstname.role)
- Password: `emp123`

### Key Features

**Dashboard:**
- View statistics (products, employees, low stock items)
- Quick actions for adding products/employees
- Role-based menu access

**Marketplace:**
- Browse all companies and products
- Create purchase orders with delivery dates
- Chat with suppliers
- Rate completed orders

**Department Management:**
- 10 specialized departments in Arabic
- Employee assignment and tracking
- Role-based permissions

**Task Management:**
- Create tasks with rewards
- Assign to employees
- Track completion status

**Payment System:**
- Torbiona installment plans
- 4-payment schedule (20%, 40%, 25%, 15%)
- Contract PDF generation
- POS printer receipts

## Technologies

- **Backend**: Flask (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **PDF Generation**: ReportLab
- **Styling**: Custom CSS with CSS variables and gradients
- **Storage**: In-memory data structures (demo purposes)

## Deployment

This Flask application can be deployed on:
- **Render.com** (Recommended)
- **Heroku**
- **PythonAnywhere**
- **AWS Elastic Beanstalk**

Note: Netlify is not suitable for Flask applications as it only supports static sites.

## Demo Companies

1. **Bin Ladin Group** - Construction
2. **Saudi Oger** - Construction
3. **Al Rashid Trading** - Construction
4. **Nesma & Partners** - Construction
5. **El Seif Engineering** - Construction
6. **SABIC** - Chemicals
7. **Fast Logistics** - Logistics Services

## License

This project is for demonstration purposes.

## Author

Abdullah Aldeijy

## Repository

https://github.com/AbdullahAldeijy/crm-demo1.git
