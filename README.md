# IT Service Request Automation Workflow

## 🚀 Project Overview
This project demonstrates the design and implementation of an automated IT service request intake and lifecycle management system using Microsoft Power Platform. The solution streamlines service desk operations by automating ticket creation, routing, notifications, and status updates.

The workflow replaces manual email-based request handling with a structured, trackable, and scalable process aligned with modern IT operations practices.

---

## 🧩 Business Problem
Traditional IT request handling often leads to:
- Manual ticket tracking
- Delayed responses
- Misrouted requests
- Limited visibility into ticket status
- Inconsistent communication with users

This solution centralizes intake, enforces structured data collection, and automates request routing and lifecycle updates to improve efficiency and accountability.

---

## 🛠️ Solution Architecture
The automation workflow integrates:

- **Microsoft Forms** – Front-end intake form for IT requests  
- **SharePoint List** – Structured backend ticket tracking system  
- **Power Automate** – Workflow engine for automation logic  
- **Conditional Routing (Switch Logic)** – Dynamic team assignment  
- **Automated Email Notifications** – Confirmation and team alerts  
- **Event-Driven Status Updates** – Triggered when ticket status changes  

---

## ⚙️ Workflow Process

### Initial Ticket Creation
1. User submits an IT request via Microsoft Forms  
2. Power Automate captures the response  
3. Ticket is created in SharePoint with a unique ID  
4. Conditional logic determines the responsible team  
5. Confirmation email is sent to requester  
6. Notification email is sent to assigned team  

### Automated Ticket Status Updates
1. SharePoint item is modified (e.g., status updated)  
2. Power Automate detects the change  
3. If status = “In Progress” or “Completed”  
4. Automated notification is sent to requester  
5. Ticket lifecycle is tracked automatically  

---

## 📊 Key Features
- Structured SharePoint list schema  
- Dynamic ticket routing using Switch conditions  
- Automated confirmation emails with ticket ID  
- Team-based distribution logic  
- Event-driven ticket status notifications  
- Scalable automation design  

---

## 🎯 Skills Demonstrated
- Power Automate workflow architecture  
- Event-driven automation design  
- Conditional logic and branching  
- Microsoft 365 service integration  
- SharePoint list schema design  
- IT service process optimization  
- Lifecycle-based notification systems  

---

## 🔮 Future Enhancements
- SLA tracking and escalation workflows  
- Approval-based request categories  
- Microsoft Teams integration (Adaptive Cards)  
- Power BI dashboard reporting  
- Role-based ticket access control  

---
