# Doctor Booking Platform

A full-stack web application for booking doctor appointments, built with React, Node.js, Express, and MongoDB.

## Project Structure

```
admin/      # Admin and doctor dashboard (React)
backend/    # Node.js/Express API server
frontend/   # User-facing web app (React)
```

## Features

- User registration and login
- Browse doctors by speciality
- Book, view, and cancel appointments
- User profile management
- Admin panel for managing doctors and appointments
- Doctor dashboard for managing availability and appointments

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- MongoDB Atlas account (or local MongoDB)
- Cloudinary account (for image uploads)

### Setup

1. **Clone the repository**

   ```sh
   git clone <your-repo-url>
   cd Doctor_Booking
   ```

2. **Configure environment variables**

   - Copy `.env` files in `backend/`, `admin/`, and `frontend/` folders and update with your credentials.

3. **Install dependencies**

   ```sh
   cd backend
   npm install
   cd ../admin
   npm install
   cd ../frontend
   npm install
   ```

4. **Start the backend server**

   ```sh
   cd backend
   npm run server
   ```

5. **Start the frontend and admin apps**

   ```sh
   cd frontend
   npm run dev
   # In a new terminal
   cd ../admin
   npm run dev
   ```

## Usage

- **Frontend**: Visit `http://localhost:5173` for the user-facing app.
- **Admin/Doctor Panel**: Visit `http://localhost:5174` for admin and doctor dashboard.
- **Backend API**: Runs on `http://localhost:4000`.

## Technologies

- **Frontend**: React, Vite, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB, Mongoose, JWT, Cloudinary
- **Admin Panel**: React, Vite, Tailwind CSS

## Folder Overview

- [`backend/`](backend/) - Express API, controllers, models, routes, middlewares
- [`frontend/`](frontend/) - User web app, React components, pages, context
- [`admin/`](admin/) - Admin/doctor dashboard, React components, pages, context

## License

MIT

---

For any issues or contributions, please open an issue or pull request.
