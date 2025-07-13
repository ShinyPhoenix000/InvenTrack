# InvenTrack

InvenTrack is a modern inventory and order management system designed for small to medium businesses. It allows you to manage products, monitor stock levels, and place orders — all in a clean, responsive interface powered by React, Supabase, and Tailwind CSS.

⸻

Features
	•	Add, update, and delete products with SKU, quantity, and price
	•	Place orders with automatic stock updates
	•	Low stock alerts based on threshold values
	•	Dashboard showing total orders, revenue, and top-selling products
	•	Sales velocity insights (units/day) with radial charts
	•	Analytics using visual charts (Recharts)

⸻

Tech Stack
	•	React + Vite + TypeScript for frontend development
	•	Supabase (PostgreSQL) for database and API
	•	Tailwind CSS for modern, responsive UI
	•	Recharts for data visualization
	•	Lucide Icons for lightweight UI icons
 
Getting Started

1. Clone the Repository

In bash:

git clone https://github.com/your-username/InvenTrack.git
cd InvenTrack

2. Install Dependencies
  npm install

3.Create Environment Variables

Create a .env file at the root of your project and add your Supabase credentials:

VITE_SUPABASE_URL=https://your-project.supabase.co

VITE_SUPABASE_ANON_KEY=your-anon-public-key

4.Run the App
npm run dev

5.Folder Structure:

src/
├── components/       // Reusable UI components

├── pages/            // Main pages like Dashboard

├── lib/              // Supabase client setup

├── types/            // TypeScript interfaces

├── App.tsx           // Main application logic

├── main.tsx          // Entry point
