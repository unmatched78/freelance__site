# Freelancer Platform

A modern freelancing platform connecting clients with skilled professionals, built with Django (backend) and React-Vite/Next.js (frontend).

## Core Features

### User Roles
- **Clients**: Post jobs, manage contracts, make payments
- **Freelancers**: Bid on projects, manage proposals, track earnings
- **Admin**: Manage users, monitor transactions, resolve disputes

### Core Functionalities
1. **User Authentication**
   - Email-based registration
   - Social login (Google, GitHub)
   - JWT authentication
   - Password reset functionality

2. **Profile Management**
   - Client profile (company info, job history)
   - Freelancer profile (portfolio, skills, ratings)
   - Profile verification system

3. **Job Marketplace**
   - Job posting with rich text editor
   - Advanced search/filters (skills, budget, location)
   - Proposal submission system
   - Bid management interface

4. **Contract System**
   - Milestone-based payments
   - Time tracking integration
   - Dispute resolution center
   - Contract termination flow

5. **Payment System**
   - payment integration
   - Escrow management
   - Payout dashboard
   - Transaction history

6. **Communication**
   - Real-time messaging
   - File sharing
   - Notification system
   - Video call integration (optional)

## Tech Stack

### Backend (Django)
- Django REST Framework
- PostgreSQL
- Celery (async tasks)/,djangoq
- Redis (caching)
- WebSockets (Django Channels)
- JWT Authentication

### Frontend (React-Vite/Next.js)
- TypeScript/JavaScript 
- Tailwind CSS
- Redux Toolkit
- React Query
- Axios
- Socket.io Client
- Formik/Yup

## Project Setup

### Backend Setup
```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Database setup
python manage.py migrate

# Run server
python manage.py runserver
