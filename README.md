# DealDrop - Smart Product Price Tracker
### Live Link - https://deal-stash.vercel.app/
Track product prices across e-commerce sites and get alerts on price drops. Built with Next.js, Firecrawl, and Supabase.

## 🎯 Features

- 🔍 **Track Any Product** - Works with Amazon, Zara, Walmart, and more
- 📊 **Price History Charts** - Interactive graphs showing price trends over time
- 🔐 **Google Authentication** - Secure sign-in with Google OAuth
- 🔄 **Automated Daily Checks** - Scheduled cron jobs check prices automatically
- 📧 **Email Alerts** - Get notified when prices drop via Resend

## 🛠️ Tech Stack

- **Next.js 16** - React framework with App Router
- **Firecrawl** - Web data extraction API
  - Handles JavaScript rendering
  - Rotating proxies & anti-bot bypass
  - Structured data extraction with AI
  - Works across different e-commerce sites
- **Supabase** - Backend platform
  - PostgreSQL Database
  - Google Authentication
  - Row Level Security (RLS)
  - pg_cron for scheduled jobs
- **Resend** - Transactional emails
- **shadcn/ui** - UI component library
- **Recharts** - Interactive charts
- **Tailwind CSS** - Styling

## 📋 Prerequisites

Before you begin, ensure you have:

- Node.js 18+ installed
- A [Supabase](https://supabase.com) account
- A [Firecrawl](https://firecrawl.dev) account
- A [Resend](https://resend.com) account
- Google OAuth credentials from [Google Cloud Console](https://console.cloud.google.com/)

## 🚀 Setup Instructions

##Clone and Install

```bash
git clone https://github.com/piyush-eon/smart-product-price-tracker.git
cd smart-product-price-tracker
npm install
```
## 📸 Screenshots

<img width="1338" height="641" alt="image" src="https://github.com/user-attachments/assets/4369432d-a608-4351-893f-5dd8bd678310" />
<img width="1308" height="682" alt="image" src="https://github.com/user-attachments/assets/5d646b66-829d-4f01-9f3f-08c877aacc34" />
<div align="center">
<img width="905" height="653" alt="image" src="https://github.com/user-attachments/assets/519bee94-4152-410d-87a4-da4df6521558" />
</div>
