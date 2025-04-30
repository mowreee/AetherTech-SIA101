# AetherTech

## 👥 Team Members & Roles

- **Marc Christian C. Delos Santos** – Team Leader / Full Stack Developer  
- **Felix C. Leid Jr** – Backend Developer  
- **Lance Krystian D. Andres** – Frontend Developer  
- **Rohann Harold Mondiguing** – Documentation Specialist  

---

## 🧰 Tech Stack

- **Frontend**: React  
- **Backend**: Node.js (Express)  
- **Database**: MongoDB  
- **Message Broker**: RabbitMQ (AMQP)  
- **Communication Protocols**: REST (Axios, Express)  
- **Architecture**: Microservices (3–4 services max)  
- **Integration Styles**:  
  - **Point-to-Point**: For direct service-to-service communication  
  - **Hub-and-Spoke**: Via RabbitMQ or an API Gateway  

---

## 📄 Design Choice Rationale

We opted for a **microservices architecture** to ensure modularity, scalability, and independent deployment of components.  

- **Point-to-Point Integration** allows lightweight and straightforward direct communication between services where real-time interaction is necessary.  
- **Hub-and-Spoke Integration** using **RabbitMQ** enables asynchronous communication, better fault tolerance, and decoupled service interaction.  

These choices help optimize performance while maintaining a flexible and maintainable system.

---

## 🗓️ Project Timeline

| **Date**     | **Activity**                                       | **Development Tools**                 | **Deadline**      | **Status**   |
|--------------|----------------------------------------------------|---------------------------------------|-------------------|--------------|
| April 30     | Roles and Assignments, Calendar of Activities      | Google Docs                           | April 30, 2025    | ✅ Finished   |
| May 3        | UI for both BUYER and SELLER                       | Visual Studio Code (React)            | May 10, 2025      | ⏳ Scheduled  |
| May 8        | Backend Development - REST API                     | Visual Studio Code (Express, Axios)   | May 12, 2025      | ⏳ Scheduled  |
| May 14       | Backend Dev - REST API & Integration of RabbitMQ   | Visual Studio Code (Express, Axios)   | May 18, 2025      | ⏳ Scheduled  |
| May 21       | Testing and Implementation                         | Visual Studio Code, Free Tools        | May 27, 2025      | ⏳ Scheduled  |

---

## 📁 How to Use This Repository

1. **Clone the repository**  
   ```bash
   git clone <repo-url>
