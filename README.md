# Lotto System 🎰

A comprehensive lottery system with user and admin dashboards, mobile money integration (TNM/Airtel Money), automated winner selection, and real-time notifications.

## Features

### User Features
- ✅ User Registration & Login
- ✅ Purchase lottery tickets
- ✅ Mobile Money Payment (TNM/Airtel Money)
- ✅ Real-time notifications for winners
- ✅ View transaction history
- ✅ See winners display
- ✅ Dashboard with account info

### Admin Features
- ✅ Admin Login & Dashboard
- ✅ User Management
- ✅ Lottery Configuration (set winner count, dates, times)
- ✅ Mobile Money Settings
- ✅ Automated Winner Selection
- ✅ View all records & transactions
- ✅ Winners management
- ✅ Analytics & Reports
- ✅ Edit all system configurations

### System Features
- ✅ Automated winner selection
- ✅ Mobile money integration (TNM/Airtel Money)
- ✅ Real-time notifications
- ✅ Responsive design
- ✅ Secure authentication
- ✅ Logo & Favicon support
- ✅ Cross-platform ads for updates

## Project Structure

```
captured_enough/
├── backend/                 # Node.js/Express backend
│   ├── models/             # Database models
│   ├── routes/             # API routes
│   ├── controllers/        # Business logic
│   ├── middleware/         # Authentication, validation
│   ├── services/           # External services (mobile money, notifications)
│   ├── config/             # Configuration files
│   └── server.js           # Entry point
├── frontend/               # React frontend
│   ├── src/
│   │   ├── components/    # Reusable components
│   │   ├── pages/         # Page components
│   │   ├── admin/         # Admin dashboard
│   │   ├── user/          # User dashboard
│   │   ├── services/      # API services
│   │   ├── assets/        # Images, logos, favicon
│   │   └── App.js         # Main app
│   └── public/            # Static files
├── database/              # Database schemas
└── docs/                  # Documentation
```

## Tech Stack

- **Backend**: Node.js, Express.js, MongoDB
- **Frontend**: React.js, Axios, TailwindCSS
- **Mobile Money**: TNM/Airtel Money API
- **Notifications**: Socket.io, Email, SMS
- **Authentication**: JWT
- **Deployment**: Docker (optional)

## Installation

See individual README files in `/backend` and `/frontend` folders.

## API Documentation

See `/docs/API.md` for complete API endpoints.

## License

MIT License

## Author

Your Name

---

**Logo Placement**: `/frontend/src/assets/logo.png`
**Favicon Placement**: `/frontend/public/favicon.ico`
