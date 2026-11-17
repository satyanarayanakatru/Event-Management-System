# EventPulse - Event Management System

An Event Management System built using React.js, Tailwind CSS, Context API, React Router, and Third-Party APIs.

## 🚀 Tech Stack

- **Framework**: React.js (Vite)
- **Styling**: Tailwind CSS
- **State Management**: Context API
- **Routing**: React Router DOM
- **HTTP Client**: Axios
- **Form Handling**: React Hook Form
- **Notifications**: React Toastify
- **Icons**: Lucide React
- **Storage**: Local Storage

## 📁 Project Structure

```text
src/
├── assets/          # Static assets & images
├── components/      # Reusable UI components (Modals, Skeletons, Navbar, Sidebar)
│   ├── common/
│   └── layout/
├── context/         # Context API stores (Auth, Event, etc.)
├── pages/           # Module Views (Auth, Dashboard, Events, Venues, etc.)
├── routes/          # Route definitions & Protected Routes
├── services/        # Axios API client & endpoints
└── utils/           # Helper functions & formatting utilities
```

## 📋 Modules Roadmap

1. **Module 1**: Authentication (Login, Register, Forgot Password, Protected Routes)
2. **Module 2**: Dashboard (KPIs, Charts, Recent Activity, Quick Actions)
3. **Module 3**: Event Management (Third-party API CRUD, Filters, Search, Pagination)
4. **Module 4**: Venue Management (Venue CRUD, Capacity Filters, Availability)
5. **Module 5**: Ticket Booking (Seat calculation, Booking summary & confirmation)
6. **Module 6**: Attendee Management (Registration, Search, Status management)
7. **Module 7**: QR Ticket (UI generation, Download, Share preview)
8. **Module 8**: Reports (Analytics, Revenue, Ticket sales, Monthly statistics)

## 🛠️ Development

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview build
npm run preview
```
