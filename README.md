# GigInsurence
# SafeDeliver AI
### Ideate & Know Your Delivery Worker

## 1. Problem Statement
Delivery workers face financial insecurity and lack affordable insurance. 
Their income varies daily, making traditional insurance difficult to maintain.

This project proposes a solution that provides **weekly micro-insurance and AI-powered risk prediction** for delivery workers.

---

## 2. Persona Based Scenarios

### Persona 1
**Name:** Ravi  
**Age:** 26  
**Job:** Zomato Delivery Partner  

**Problem:**  
Ravi delivers food late at night. If he meets with an accident, he loses income and has no financial support.

---

### Persona 2
**Name:** Suresh  
**Age:** 32  
**Job:** Amazon Delivery Agent  

**Problem:**  
Suresh sometimes faces fake delivery complaints that affect his earnings.

---

## 3. Application Workflow

1. Delivery worker downloads the mobile application.
2. Registers using phone number.
3. Links their delivery platform account.
4. App tracks delivery activity.
5. Weekly insurance premium is calculated.
6. Worker pays small weekly premium.
7. Insurance claim is triggered automatically during accidents.

---

## 4. Weekly Premium Model

Premium will be calculated based on worker activity.

Example formula:

Weekly Premium = Base Price + Risk Score + Delivery Distance

Parameters:
- Number of deliveries
- Night deliveries
- Distance travelled
- Area risk level

Example:

| Deliveries | Risk Level | Premium |
|------------|------------|---------|
| 20 | Low | ₹20 |
| 40 | Medium | ₹40 |
| 70 | High | ₹60 |

---

## 5. Parametric Triggers

Automatic insurance payout will happen when certain conditions are detected.

| Trigger | Action |
|-------|-------|
| Accident detected | ₹5000 payout |
| Hospital visit | ₹3000 support |
| 3+ days inactivity | Income support |

---

## 6. AI / ML Integration

AI will be used in the following areas:

### Premium Prediction
AI predicts risk level based on worker behavior and delivery patterns.

### Fraud Detection
Machine learning detects suspicious insurance claims.

### Risk Area Detection
AI analyzes accident data to detect high-risk delivery zones.

---

## 7. Platform Choice

We chose a **Mobile Application** because:
- Delivery workers primarily use smartphones
- GPS tracking is required
- Real-time alerts and notifications are easier

---

## 8. Tech Stack

Frontend:
- React Native

Backend:
- Node.js
- Express.js

Database:
- MongoDB

AI / ML:
- Python
- Scikit-learn

Cloud:
- Firebase / AWS

---

## 9. Development Plan

| Week | Task |
|-----|------|
| Week 1 | Research and idea development |
| Week 2 | UI prototype design |
| Week 3 | Backend API development |
| Week 4 | AI model integration |
| Week 5 | Testing and deployment |

---

## 10. Future Scope

- Emergency SOS feature
- Health insurance integration
- Smart accident detection using sensors

---

## Repository Link
(To be used for further phases of the project)

---

## Video Presentation
Link to the 2-minute explanation video will be added here.
