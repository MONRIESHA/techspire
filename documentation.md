# Nursing and Midwifery Council Management System
## Technical Documentation

### 1. System Overview
- Web-based management system for the Nursing and Midwifery Council of Sierra Leone
- Built using Django framework with a modular architecture
- Secure role-based access control

### 2. Key Features
#### User Management
- Multiple user roles (Admin, Registrar, Deputy Registrar, Secretary, Finance, Exam IT, Student)
- Profile management with photo upload
- Secure authentication and authorization

#### Application Processing
- Multiple application types:
  - SRN Indexing
  - License Renewal
  - SRN Application
  - Midwives Application
  - International Application
  - State Board Exam
- Document verification
- Status tracking

#### Student Management
- Comprehensive student records
- Academic progress tracking
- Hospital posting management
- Examination management

#### Financial Management
- Fee structure management
- Transaction tracking
- Payment processing
- Financial reports generation

#### Reporting System
- Customizable reports
- Export functionality (PDF, Excel)
- Letterhead integration
- Print-friendly formats

### 3. Technical Architecture
- Frontend: HTML5, CSS3, JavaScript
- Backend: Django (Python)
- Database: PostgreSQL
- Authentication: Django Auth System
- File Storage: Django File Storage

### 4. Security Features
- Password encryption
- Session management
- CSRF protection
- Role-based access control
- Secure file handling

### 5. Deployment Requirements
- Python 3.8+
- Django 3.2+
- PostgreSQL 12+
- Web server (e.g., Nginx)
- SSL certificate 