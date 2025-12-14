![Release](https://img.shields.io/badge/version-3.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PHP](https://img.shields.io/badge/PHP-7.4%2B-purple)
![Status](https://img.shields.io/badge/status-stable-success)

# PHPHR – Open Source HR Management Software

PHPHR is a modern Human Resource Management (HRM) platform available in two
flexible deployment models, enabling organizations to choose the approach that
best fits their operational needs, data policies, and long-term growth
strategy.

- **PHPHR Open-Source** – A free, self-hosted edition designed for startups,
  small to mid-sized businesses, and organizations that require full control
  over their hosting environment, infrastructure, and HR data. This edition
  provides essential HR capabilities such as employee management, attendance
  tracking, leave management, payroll processing, and an intuitive HR
  dashboard, while allowing complete customization and on-premise deployment.

- **PHPHR Cloud** – A fully managed, enterprise-grade HRMS built for growing
  and large organizations that require scalability, reliability, and minimal
  technical overhead. PHPHR Cloud includes secure cloud hosting, automatic
  updates, regular backups, performance optimization, enhanced security
  standards, and dedicated support. It enables HR teams to focus entirely on
  workforce operations and strategic initiatives without the burden of server
  management or infrastructure maintenance.

---

## 🚀 Features (Open-Source Edition)

- Employee Management  
- Attendance Tracking  
- Leave Management  
- Payroll Management  
- HR Dashboard  
- Secure Authentication System  

---

## ☁ Deployment Models

PHPHR is available in two deployment options:

- **PHPHR Open-Source** – Free, self-hosted HR software  
- **PHPHR Cloud** – Fully managed, enterprise-grade HRMS  

This flexibility allows organizations to select the deployment model that best
aligns with their hosting preferences, data governance policies, and long-term
scalability goals.

---

## 🛠 Technology Stack

- PHP 7.4+ (PHP 8+ recommended)  
- MySQL / MariaDB  
- Apache or Nginx  
- Bootstrap-based User Interface  

---



## 📦 Installation


1. Download the PHPHR Open-Source package and extract it into your
   web server root directory (for example: htdocs, www, or public_html).

2. Create a new MySQL / MariaDB database.
   (UTF8MB4 character set is recommended.)

3. Import the database schema using the SQL file located at:
       /database/phphr_install.sql

4. Open the database configuration file:
       /app/config/database.php

   Update the following database credentials:
       DB_HOST
       DB_NAME
       DB_USER
       DB_PASS

5. Open the application configuration file:
       /app/config/config.php

   Update company details and HR system settings as required.

6. Open your browser and access PHPHR using:
       http://localhost/your-project-folder/public/

7. Log in using the default admin credentials and
   change the password immediately after first login.

---

## ☁ PHPHR Cloud

PHPHR Cloud is a fully managed, enterprise-grade HR management solution designed
for organizations that require high availability, security, and scalability.
It provides automatic updates, secure cloud infrastructure, routine backups,
performance optimization, and continuous platform enhancements.

The cloud edition removes server maintenance and technical complexity, allowing
HR teams to focus entirely on workforce management, operational efficiency, and
organizational growth.

---

## 🎥 Demo Video

Watch the official PHPHR demo walkthrough to explore employee management,
attendance tracking, leave workflows, payroll processing, and dashboard
features in action:

▶️ https://youtu.be/nfCiNBBcwec?si=ggUVwILo-NG2rlf2

---

## 🌐 Links

- **Website:** https://www.phphr.com  
- **Live Demo:** https://www.phphr.com/hr-software-demo/  
- **Download:** https://www.phphr.com/download-hr-software/  

---

## 🤝 Contributing

Contributions are welcome!  
You can help improve PHPHR by submitting bug reports, feature requests, or pull
requests to enhance the Open-Source edition.

---

## 📄 License

PHPHR is released under the **MIT Open Source License**.  
You are free to use, modify, rebrand, and deploy this software commercially,
provided that the original copyright notice is preserved.

---


---

## 📸 Screenshots

### Dashboard
![PHPHR Dashboard](screenshots/login.png)

### Employee Management
![Employee Management](screenshots/dashboard.png)





⭐ If you find PHPHR useful, please **star this repository** to support the
project!

