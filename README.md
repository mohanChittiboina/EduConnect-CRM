# EduConnect CRM  
*A Salesforce-Based CRM Solution for Educational Institutions*  

---

## 📌 Project Overview  
EduConnect CRM is a Salesforce-based Customer Relationship Management (CRM) solution tailored for **educational institutions** such as schools, colleges, and universities. It streamlines **student admissions, course management, faculty coordination, and alumni engagement** while enhancing decision-making with reports and dashboards.  

---

## 🚀 Phases of Development  

### **Phase 1 – Requirement Gathering & Analysis**  
- Interacted with stakeholders (faculty, admin staff, and management) to identify pain points.  
- Key requirements identified:  
  - Student Admission Management  
  - Course & Faculty Allocation  
  - Alumni Tracking & Communication  
  - Attendance & Performance Monitoring  

---

### **Phase 2 – Salesforce Environment Setup**  
- Created a **Salesforce Developer Org**.  
- Configured profiles, roles, and permission sets for students, faculty, and administrators.  
- Enabled **Education Cloud features** for institutional needs.  

---

### **Phase 3 – Data Modeling**  
Designed custom objects and relationships:  
- **Student__c** (Name, Email, Phone, Admission Date, Status)  
- **Course__c** (Course Name, Duration, Credits)  
- **Faculty__c** (Name, Department, Email, Courses Taught)  
- **Enrollment__c** (Junction object between Student & Course)  
- **Alumni__c** (Batch Year, Current Organization, Contact Info)  

---

### **Phase 4 – UI & Navigation Setup**  
- Built **Lightning App Pages** for Students, Courses, and Faculty.  
- Customized **tabs and page layouts** for better navigation.  
- Added **quick actions** like "Enroll Student" and "Assign Faculty."  

---

### **Phase 5 – Business Logic with Apex & Automation**  
- **Apex Triggers & Classes** for:  
  - Auto-assigning students to default advisors upon enrollment.  
  - Updating course capacity dynamically.  
- **Flows & Process Builder** for:  
  - Sending automated welcome emails on admission.  
  - Triggering reminders for fee payments and assignment deadlines.  

---

### **Phase 6 – Reports & Dashboards**  
- Created reports for:  
  - Student Enrollment by Course  
  - Faculty Workload Distribution  
  - Alumni Engagement Statistics  
- Built **dashboards** for management to monitor KPIs in real time.  

---

### **Phase 7 – Security & Sharing Settings**  
- Defined role hierarchy (Admin > Faculty > Student).  
- Implemented **field-level security** to protect sensitive student data.  
- Configured **sharing rules** for controlled data access.  

---

### **Phase 8 – Testing & Debugging**  
- Unit tested all Apex triggers and classes.  
- Verified data integrity for enrollments and alumni records.  
- Fixed bugs in email automation and course capacity updates.  

---

### **Phase 9 – Deployment**  
- Used **Change Sets** to move configurations from sandbox to production.  
- Verified deployment with **post-deployment scripts** for data consistency.  
- Conducted end-user training sessions for staff and faculty.  

---

### **Phase 10 – Maintenance & Enhancements**  
- Scheduled **regular health checks** for data accuracy.  
- Collected feedback from users for future improvements.  
- Planned upcoming features like:  
  - **Mobile App Integration** for students.  
  - **AI-powered Student Performance Prediction** using Einstein AI.  

---

## 🛠️ Tech Stack  
- **Platform:** Salesforce CRM  
- **Tools:** Apex, Flows, Process Builder, Lightning App Builder, Reports & Dashboards  
- **Deployment:** Change Sets  

---

## 📌 Outcomes  
- Simplified **student admission and enrollment process**.  
- Improved **faculty workload tracking**.  
- Enhanced **alumni communication and engagement**.  
- Provided **real-time insights** through dashboards for management.  

---

## 📜 License  
This project is licensed under the **MIT License** – feel free to use and customize.  
