## Ticket Booking System
A Python-based ticket booking backend built with FastAPI, allowing users to browse events, select venues and available seats, make reservations, and complete simulated payments.

Manages the booking lifecycle through interconnected modules responsible for event management, venue management, seat availability, bookings, and payment processing. Booking confirmations are sent to users via email.

# Features
- Event Management: Browse and manage available events.
- Venue Management: Organize events according to their respective venues.
- Seat Selection: Select available seats for specific events.
- Booking Management: Create and manage ticket reservations.
- Seat Availability: Check seat availability during the booking process.
 -Payment Processing: Handle simulated payments associated with ticket bookings.
 -Email Notifications: Send booking confirmation emails to users.

# Technical Implementation
Developed using Python and FastAPI, following a modular backend architecture.

The project is organized into dedicated modules, each responsible for a specific part of the booking process:

- Configures API endpoints.
- Handles booking-related operations.
- Manages PostgreSQL database configuration and initialization.
- Handles email notifications.
- Manages event-related operations.
- Defines the application's data models.
- Handles simulated payment operations.
- Manages seat selection and availability.
- Handles venue-related operations.

# Technologies Used
- Python
- FastAPI
- PostgreSQL
- REST API

# Architecture
The application separates its core functionality into independent modules, making the different aspects of the booking process easier to maintain and extend.

Users interact with the system through API requests, without a dedicated frontend interface.
