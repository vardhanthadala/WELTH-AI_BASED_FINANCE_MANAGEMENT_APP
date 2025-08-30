# Full Stack AI Finance Platform with Next JS, Supabase, Tailwind, Prisma, Inngest, ArcJet, Shadcn UI... <img width="1470" alt="Screenshot 2024-12-10 at 9 45 45 AM" src="https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432">

[🚀 Live Demo](https://welth-red.vercel.app/)


## 📌 Overview

**Welth** is a smart personal finance tracker that helps users monitor income, expenses, and budgets while leveraging AI for receipt scanning and intelligent financial insights. The app also supports automated transactions, scheduled email summaries, and is secured with cutting-edge tools.

Built using modern technologies and deployed on **Vercel**, it offers a fast, secure, and highly interactive user experience.

---

## 🚀 Key Features

- 🤖 **AI-powered Receipt Scanning** – Extracts text and categorizes expenses automatically.
- 📊 **Expense Tracking** – Track income and expenses, set budget limits, receive alerts.
- 📅 **Scheduled Transactions** – Automatically logs recurring expenses.
- 🧠 **Financial Insights** – Sends monthly summaries via email showing patterns and trends.
- 🔐 **Security & API Protection** – Secured with ArcJet for bot protection and rate limiting.
- 📈 **Interactive Charts** – Visualize expenses daily and monthly using dynamic charts.

---

## 🛠️ Tech Stack

| Layer              | Technology                                         |
|-------------------|----------------------------------------------------|
| Frontend          | React 19, Next.js 15, Tailwind CSS, Shadcn UI      |
| Backend           | Supabase, Prisma                                   |
| Authentication    | Clerk                                              |
| Background Jobs   | Inngest                                            |
| AI Capabilities   | Receipt scanning & financial insight generation    |
| Security          | ArcJet (Bot protection, rate limiting, API shield) |
| Deployment        | Vercel                                             |

---

## 🔐 Security Highlights

- **Bot Protection**: ArcJet shield blocks automated and malicious traffic.
- **Rate Limiting**: Prevents API abuse and ensures reliable service.
- **Session Handling**: All auth and session management is done securely via Clerk.

---

## 🧾 Features in Detail

- Upload receipts and let AI handle categorization.
- Set and track budget limits.
- Schedule recurring expenses automatically via Inngest jobs.
- Get AI-powered monthly financial summaries sent via email.
- Visual dashboards show spending trends and breakdowns.
- Secure login system and fully protected APIs.

---

## ⚙️ How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/vardhanthadala/WELTH-AI_BASED_FINANCE_MANAGEMENT_APP.git
   cd WELTH-AI_BASED_FINANCE_MANAGEMENT_APP
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```


 3.**Set up environment variables**
  Create a .env.local file in the root directory and include the following:
 ```bash
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   DATABASE_URL=your_postgres_database_url
   CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   NEXT_PUBLIC_CLERK_FRONTEND_API=your_clerk_frontend_api
   INNGEST_API_KEY=your_inngest_key
   ARCJET_SECRET=your_arcjet_key
   ```


4.**Run the development server**
   ```bash
  npm run dev
   ```


5. Open http://localhost:3000  in your browser to view the app.


## 📄 License

This project is licensed under the [MIT License](./LICENSE) ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg). Feel free to use, share, and contribute.
