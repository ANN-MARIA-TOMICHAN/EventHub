# EventHub

**EventHub** is a full-stack web application designed to streamline the booking and management of shared resources (like rooms, labs, or equipment) within an organization or campus.

Built with **React.js**, **TypeScript**, and **Tailwind CSS**, the app delivers a modern, responsive, and intuitive interface. It leverages **Supabase** for backend services such as authentication, database management (**PostgreSQL**), and file storage, ensuring scalability and real-time data handling.

---

## Core Features

- User Authentication (via Supabase)
- Resource Booking & Scheduling
- Searchable, Filterable Resource Listings
- Data Visualizations using Recharts
- PDF Generation for reports (using jsPDF)
- Form Handling & Validation with React Hook Form + Zod
- Client-side Routing with React Router
- Customizable UI using Radix UI + Tailwind CSS
- Fast Build & Dev Environment with Vite
- Efficient Server State Handling via React Query

---

## Tech Stack

### Frontend
- React.js
- TypeScript
- Tailwind CSS
- Radix UI
- React Router
- React Query
- React Hook Form + Zod
- Recharts
- jsPDF
- Vite

### Backend
- Supabase
  - PostgreSQL Database
  - Authentication
  - File Storage

### Tools & Utilities
- ESLint (Linting and Code Style)
- Vite (Build Tool)
- Chatbot integration using Dialogflow or OpenAI
- Calendar view for bookings

---

## Project Structure

resource-scheduler-suite/
│
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/             # Application views
│   ├── hooks/             # Custom React hooks
│   ├── utils/             # Utility functions
│   └── services/          # API interaction logic
│
├── public/                # Static assets
├── index.html             # Root HTML file
├── package.json           # Project metadata and dependencies
├── tailwind.config.ts     # Tailwind CSS configuration
└── vite.config.ts         # Vite configuration


---

## Future Enhancements

- Integration with a smart chatbot using Dialogflow or OpenAI
- Calendar view for bookings
- Responsive PWA experience
- Real-time notifications

---

## Getting Started

### Prerequisites
- Node.js
- Supabase Account

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/resource-scheduler-suite.git
cd resource-scheduler-suite

# Install dependencies
npm install

# Create a `.env` file with your Supabase credentials
touch .env

# Start the development server
npm run dev


