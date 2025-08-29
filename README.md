# BFHL API

A simple REST API built with **Node.js + Express**, deployed on **Vercel**.  
Implements the requirements for the **Full Stack Question Paper – VIT**.

---

## 🚀 Features
- **POST /bfhl** → Processes an array and returns:
  - Status (`is_success`)
  - User ID (format: `fullname_ddmmyyyy`)
  - Email & Roll Number
  - Odd / Even numbers
  - Alphabets (converted to uppercase)
  - Special characters
  - Sum of numbers (as string)
  - Concatenated alphabets in reverse alternating caps
- **GET /** → Health message
- **GET /bfhl** → API status check

---

## 📦 Installation
```bash
git clone https://github.com/your-username/bfhl-api.git
cd bfhl-api
npm install
