# Full Stack AI Finance Platform with Next JS, Supabase, Tailwind, Prisma, Inngest, ArcJet, Shadcn UI...

<img width="1470" alt="Screenshot 2024-12-10 at 9 45 45 AM" src="https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432">

## 📌 AI Finance Management App

## Overview

This project is a **Personal Finance Tracker** built with the latest technologies. It allows users to securely track their income, expenses, and set budget limits, while leveraging AI for receipt scanning and financial insights.

The application is designed with a user-friendly interface using **React.js**, **Next.js**, and **Tailwind CSS**, deployed on **Vercel**. It incorporates AI for automatic expense categorization through receipt scanning and provides insightful financial summaries.

## Key Features

- **AI-powered receipt scanning**: Automatically categorizes expenses and tracks spending.
- **Real-time database**: Uses **Supabase** for storing user data and **Prisma** as the ORM.
- **Expense tracking**: Track income and expenses, set budget limits, and receive email alerts when nearing the budget limit.
- **Financial insights**: Monthly insights and detailed reports via email, showing trends and patterns in spending.
- **Scheduled transactions**: Schedule recurring expenses and automatically add them when due.
- **API Security**: Integrated **ArcJet** for API security, implementing rate limiting and bot protection to ensure the application is secure against common threats.

## Tech Stack

- **Frontend**: React.js, Next.js 15, Tailwind CSS, Shadcn UI
- **Backend**: Supabase, Prisma
- **Authentication**: Clerk
- **Email & Scheduled Jobs**: Inngest
- **AI**: Receipt scanning and financial insights generation
- **Security**: ArcJet (Bot protection, rate limiting, API shield)
- **Deployment**: Vercel

## Security Highlights

- **Bot Protection**: Using **ArcJet Shield** to prevent bots from accessing the API.
- **Rate Limiting**: To safeguard the app from abuse and ensure a smooth user experience.
- **Authentication**: Managed through **Clerk** to handle secure user login and session management.

## Features in Detail

- **Receipt Scanning**: Users can upload receipts, and the AI will automatically extract and categorize expenses.
- **Expense Tracking**: Provides a detailed breakdown of daily and monthly expenses.
- **Scheduled Transactions**: Schedule recurring expenses and track them seamlessly.
- **Financial Summaries**: Periodically email users with financial insights, including spending patterns and trends.

## How to Use

1. Clone this repository.
2. Install dependencies:
   ```bash
   npm install

