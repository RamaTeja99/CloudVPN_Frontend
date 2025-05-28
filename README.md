 # CloudBasedVPN FrontEnd – Full Stack VPN as a Service

Welcome to **CloudBasedVPN**, a full-stack subscription-based VPN service built on top of **AWS Cloud**, **Spring Boot**, and **React**. This project dynamically creates VPN instances on demand and delivers secure, browser-based VPN access to users, depending on their active subscription plans.

**🌐 Live Demo:**  
🔗 [https://cloudbasedvpn.netlify.app](https://cloudbasedvpn.netlify.app)

---

## Project Overview

CloudBasedVPN is designed to provide scalable and secure VPN access to users based on their chosen subscription plans (Free Trial, Monthly, Yearly). The backend leverages AWS EC2 instances to dynamically spin up WireGuard VPN servers, while the frontend offers a smooth and responsive user experience.

Key features include:

- User authentication with JWT and role-based access
- VPN provisioning via AWS EC2
- QR code and config-based VPN connection
- Razorpay payment integration
- Admin and User dashboards
- Subscription management and security policies

---

## Tech Stack

**Frontend:**
- Vite
- React
- TypeScript
- Tailwind CSS
- shadcn/ui

---

## Getting Started – Clone and Run Locally

### Clone the Repository

```bash
# Step 1: Clone the repository
git clone https://github.com/RamaTeja99/CloudBasedVPN.git

# Step 2: Navigate to the frontend project
cd Frontend

# Step 3: Install dependencies
npm install

# Step 4: Start the development server
npm run dev



