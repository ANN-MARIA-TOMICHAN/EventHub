<<<<<<< HEAD
# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/5d0f8da4-3016-4af5-a02e-a946ab787110

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/5d0f8da4-3016-4af5-a02e-a946ab787110) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with .

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/5d0f8da4-3016-4af5-a02e-a946ab787110) and click on Share -> Publish.

## I want to use a custom domain - is that possible?

We don't support custom domains (yet). If you want to deploy your project under your own domain then we recommend using Netlify. Visit our docs for more details: [Custom domains](https://docs.lovable.dev/tips-tricks/custom-domain/)
=======
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


>>>>>>> e0892a263b3726025f946491dd21cf6803011644
