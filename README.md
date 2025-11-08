# 🩸 Blood Bank Management System (Laravel)

A full-featured **Blood Bank Management System** built with **Laravel** to digitalize blood donation, testing, inventory, and hospital requests.  
It’s designed for **Admins, Staff, Hospitals, and Donors** — providing a secure, automated, and efficient way to manage blood collection and distribution.

---

## 🚀 Features Overview

### 👨‍⚕️ Admin Panel
- Manage blood banks, staff, hospitals, donors, and drives  
- Monitor donations, inventory, and stock levels  
- Approve drives, requests, and oversee all operations  
- Generate reports (PDF) for compliance and analytics  
- View charts and trends (donors, blood types, stock usage)

### 👩‍🔬 Staff Panel
- Handle donor registrations and donations  
- Perform screening and mark tested units  
- Manage blood components (Whole Blood, RBC, Plasma, Platelets)  
- Track issued and discarded units  
- Manage storage equipment (freezers, agitators, refrigerators)  

### 🩸 Donor Portal
- Register and verify account via email  
- Book appointments online  
- Host and view blood drives  
- Manage personal donation history and profile  

### 🏥 Hospital Requests
- Send and track blood requests  
- View availability of components in real-time  
- Transparent issuance tracking by staff/admin  

---

## 🧱 Tech Stack

| Technology | Description |
|-------------|--------------|
| **Laravel** | PHP Framework for backend |
| **MySQL** | Database |
| **Blade** | Templating engine |
| **Bootstrap / Tailwind** | Responsive UI |
| **Chart.js / ApexCharts** | Data visualization |
| **DOMPDF** | PDF reporting |
| **Auth Middleware** | Role-based access control |

---

## ⚙️ Installation Guide

Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/blood-bank-management-system.git
cd blood-bank-management-system
composer install
php artisan migrate
php artisan db:seed
php artisan serve

 If you need Help Hire me https://www.fiverr.com/ali_raza_tawry
