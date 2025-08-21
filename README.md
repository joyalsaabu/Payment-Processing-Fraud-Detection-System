
💳 Payment Processing & Fraud Detection System Simulation  

A web-based interactive simulation of a full-lifecycle payment processing system. This project visually demonstrates how a transaction flows through a backend microservices architecture — from authorization to settlement — including a real-time fraud detection layer.  

---

## 🌟 Key Features
- Interactive Payment Form – Initiate new payments to any recipient with a specified amount.  
- Live System Monitor – Watch in real-time as the transaction progresses through each simulated microservice:  
  - 🟦 Authorization Service (Java/Spring Boot)  
  - 🟩 Fraud Detection API (Python/Scikit-learn)  
  - 🟧 Clearing House  
  - 🟨 Settlement & Database Logging (PostgreSQL)  
- Simulated Fraud Detection – Payments over $1,000 are flagged by a simulated ML model.  
- Dynamic Wallet Balance – Real-time wallet balance updates after settlement.  
- Persistent Transaction Log – All transactions (completed ✅, failed ❌, or flagged 🚩) are stored in a simulated database log.  

---

## 🛠️ Technologies Simulated
- Backend: Core Java, Spring Boot (Microservices)  
- Machine Learning: Python, Scikit-learn (Fraud Detection module)  
- APIs: RESTful communication between services  
- Database: PostgreSQL (Transaction Logging)  
- Frontend: HTML, Tailwind CSS, JavaScript  

---

##  How to Run
This is a self-contained web application — no installation required.  

1. Clone the repository:  
   
   git clone https://github.com/your-username/payment-processing-simulation.git

2. Open the project folder.
3. Launch the simulation by opening the `index.html` file in any modern browser (Chrome, Firefox, Edge).

That’s it!  The simulation is ready to use immediately.


## 📂 Project Structure


payment-processing-simulation/
│── index.html          # Main entry point
│── /assets             # CSS, JS, and static files
│── README.md           # Project documentation

📖 Learning Outcomes

This project demonstrates:

* End-to-end payment processing flow (Auth → Clearing → Settlement)
* Real-time fraud detection integration using ML simulation
* Microservices communication via REST APIs
* Logging and persistence with PostgreSQL
* How frontend can simulate backend architecture


🙌 Acknowledgements

Inspired by real-world Core Payments systems and fraud detection workflows used in financial services.

 

