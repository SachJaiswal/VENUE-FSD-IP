# Venue Management System

A full-stack application for managing venue bookings and displays, built with Spring Boot and Angular.

## Features

- Venue Display
  - List all venues
  - View venue details (ID, name, location, capacity)
  
- Venue Booking
  - Create new bookings
  - View existing bookings
  - Filter bookings by venue and date
  - Manage booking details (activity ID, date, start/end time)

## Tech Stack

### Backend
- Spring Boot 3.2.3
- Spring Data JPA
- H2 Database
- Lombok
- Maven

### Frontend
- Angular 17.2.0
- Angular Material
- TypeScript
- RxJS

## Getting Started

### Prerequisites
- Java 17 or later
- Node.js and npm
- Angular CLI

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
4. Access the H2 console at: http://localhost:8080/h2-console

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   ng serve
   ```
4. Access the application at: http://localhost:4200

## API Endpoints

### Venues
- GET /api/venues - Get all venues
- GET /api/venues/{id} - Get venue by ID
- POST /api/venues - Create new venue
- PUT /api/venues/{id} - Update venue
- DELETE /api/venues/{id} - Delete venue

### Bookings
- GET /api/bookings - Get all bookings
- GET /api/bookings/{id} - Get booking by ID
- POST /api/bookings - Create new booking
- PUT /api/bookings/{id} - Update booking
- DELETE /api/bookings/{id} - Delete booking
- GET /api/bookings/venue/{venueId}/date/{date} - Get bookings by venue and date

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request #   V e n u e C R U D  
 #   V e n u e - F S D - I P  
 