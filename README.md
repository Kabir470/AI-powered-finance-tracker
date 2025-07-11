# AI-Powered Finance Tracker

A modern, beautiful finance tracking application with AI-powered insights built with React, TypeScript, and Supabase.

## Features

- 📊 **Real-time Dashboard** - Beautiful charts and financial metrics
- 💰 **Transaction Management** - Add, edit, and categorize income/expenses
- 🤖 **AI Insights** - Smart financial recommendations and spending analysis
- 📈 **Data Visualization** - Interactive charts and graphs
- 🔐 **Secure Authentication** - User accounts with data protection
- 📱 **Responsive Design** - Works perfectly on all devices
- 🎨 **Modern UI** - Glass-morphism design with smooth animations

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Supabase (PostgreSQL, Auth, Edge Functions)
- **Charts**: Recharts
- **Icons**: Lucide React
- **Build Tool**: Vite

## Getting Started

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd finance-tracker
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up Supabase**

   - Create a new project at [supabase.com](https://supabase.com)
   - Copy your project URL and anon key
   - Create a `.env` file based on `.env.example`

4. **Set up the database**

   - Run the migration in `supabase/migrations/create_finance_tables.sql`
   - This creates all necessary tables and security policies

5. **Start the development server**
   ```bash
   npm run dev
   ```

## Database Schema

The application uses the following main tables:

- **transactions** - User financial transactions
- **categories** - Transaction categories
- **budgets** - Budget tracking
- **goals** - Financial goals

All tables include Row Level Security (RLS) policies to ensure data privacy.

## AI Features

The application includes AI-powered insights that analyze:

- Spending patterns and trends
- Budget alerts and recommendations
- Savings opportunities
- Category-wise expense analysis
- Financial health scoring

## Security

- All user data is protected with Supabase RLS
- Secure authentication with email/password
- API endpoints are protected with JWT tokens
- CORS policies properly configured

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request
#
