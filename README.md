# Guidewire-Kevin-rep-roj

# NammaCover: Hyperlocal Income Protection for Gig Workers


## 2min video link :https://drive.google.com/file/d/1xHtC9wtKZvWLRcDss-foT0rxJNW5kvEQ/view?usp=sharing 
## Overview
Persona's:

Ravi is a Swiggy delivery partner in Chennai. On a normal day, he earns around ₹600.  
But during heavy rains or extreme weather, his earnings drop drastically — sometimes by 40–60%.  

The problem is not that he cannot work at all.  
The real issue is that his **earning potential reduces due to external disruptions**.

Today, there is no system that protects gig workers from this **partial income loss**.

**NammaCover** is an AI-powered parametric insurance platform designed to protect delivery partners from income loss caused by real-world disruptions like rain, pollution, and traffic conditions.

---

## Problem Statement

Gig workers in India face income instability due to:

- Heavy rain and flooding
- Extreme heat
- Air pollution
- Traffic congestion
- Sudden curfews or local restrictions

These disruptions do not always stop work completely but reduce:
- Number of orders
- Delivery efficiency
- Working hours

👉 Result: **Significant income loss with no safety net**

---

## Our Solution

NammaCover provides:

- AI-based risk assessment
- Weekly subscription-based insurance
- Automatic claim detection
- Instant payout for income loss

Instead of insuring events, we insure **actual income reduction**.

---

## Key Innovation

### Earning Drop Index (EDI)

We introduce a new concept:

> **EDI (Earning Drop Index)** — measures real-time earning loss instead of just environmental conditions.

EDI is calculated using:
- Weather severity
- Order volume drop
- Worker activity levels
- Zone congestion

👉 Claims are triggered based on **actual earning impact**, not just rain.

---

## System Workflow

1. User registers on platform
2. System tracks:
   - Location
   - Active working hours
   - Orders completed
3. AI calculates weekly premium
4. APIs monitor:
   - Weather data
   - Traffic conditions
   - Zone activity
5. If disruption occurs:
   - System calculates EDI
   - Verifies income loss
   - Automatically triggers claim
6. Instant payout is processed

---
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/58c90362-b933-44b0-b049-17f3a074e4d2" />

## Target Persona

- Food delivery partners (Swiggy, Zomato)
- Location: Chennai (initial focus)
- Daily earning range: ₹400–₹1000
- Highly dependent on daily working conditions

---

##  Parametric Triggers

Claims are triggered when:

- Rainfall exceeds threshold AND
- Order volume drops significantly AND
- Worker activity reduces

Example:

```
Rainfall > 40mm  
Orders drop by 40%  
Worker active hours drop by 30%  
 
→ Claim automatically triggered
```
---

## Weekly Pricing Model

Dynamic pricing based on:

- Area risk level (flood-prone zones)
- Historical disruption data
-  Worker profile

### Example:

| Zone Type        | Weekly Premium |
|----------------|---------------|
| Low Risk Area   | ₹20/week      |
| Medium Risk     | ₹30/week      |
| High Risk Area  | ₹45/week      |

---

## Payout Model

Payout is based on **actual income loss**, not fixed values.

### Formula:
```
Payout = % of average daily earnings lost
```
### Example:
```
- Avg earning = ₹600/day  
- Loss detected = 50%  
👉 Payout = ₹300  
  ```
---

##  AI/ML Components

### 1. Risk Prediction Model
- Predicts high-risk days using:
  - Weather forecast
  - Historical disruption patterns

---

### 2. Dynamic Pricing Engine
- Adjusts weekly premium based on:
  - Location risk
  - Seasonal changes
  - Worker activity patterns

---

### 3. Fraud Detection System

Real-world fraud scenarios handled:

- Fake GPS location
- Logging in without actual work
- Duplicate claims

#### Detection Methods:
- GPS consistency validation
- Order activity verification
- Cross-check with zone-level data

---

##  Integration Capabilities

-  Weather APIs (OpenWeather / mock)
- Traffic data (Google Maps API / mock)
- Platform simulation APIs
- Payment gateway (Razorpay test mode / UPI simulation)

---

## Dashboard

### Worker Dashboard
- Weekly coverage status
- Earnings protected
- Risk alerts

### Admin Dashboard
- Fraud alerts
- High-risk zones
- Claim analytics
- Loss ratio tracking

---

## Real-World Enhancements

### Smart Alerts
- Notify workers about upcoming disruptions  
  Example: “Heavy rain expected today — consider early shifts”

---

### Offline Support
- Handles low network conditions with cached tracking

---

### Micro Coverage Options
- Flexible plans:
  - Basic: ₹10/week
  - Standard: ₹30/week
  - Premium: ₹50/week

---

## Tech Stack

### Frontend
- React.js / Android (Kotlin)

### Backend
- Node.js / Java Spring Boot

### AI/ML
- Python (Scikit-learn / TensorFlow)

### Database
- MongoDB / PostgreSQL

### APIs
- Weather API
- Traffic API
- Payment Gateway (Sandbox)


## Future Scope

- Expand to:
  - Amazon delivery partners
  - Zepto/Blinkit workers
- Add:
  - Hyperlocal predictive analytics
  - Real-time incentive optimization
  - Integration with gig platforms

---

## Conclusion

NammaCover is not just an insurance product.  
It is a **financial safety layer for gig workers**, designed around real-world conditions.

By focusing on **income protection instead of event coverage**,  
we create a system that is practical, scalable, and truly beneficial.

---
