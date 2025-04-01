# Movie Booking Application

A full-stack movie booking application built with React, Spring Boot, and MySQL.

## Features

- Browse movies from TMDB API
- View movie details
- Book movie tickets
- Responsive modern UI
- Secure backend API

## Prerequisites

- Node.js and npm
- Java 17
- MySQL
- Maven

## Setup Instructions

### Database Setup

1. Create a MySQL database named `random`
2. Update the database credentials in `backend/src/main/resources/application.properties` if needed

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Build and run the Spring Boot application:
```bash
mvn spring-boot:run
```

The backend server will start on http://localhost:8080

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

The frontend application will start on http://localhost:3000

## Environment Variables

The application uses the following environment variables:

- TMDB API Key: `c6b0d76711aafd7e790051984c15dcac`
- Database URL: `jdbc:mysql://localhost:3306/random`
- Database Username: `root`
- Database Password: `Password`

## API Endpoints

- `GET /api/bookings` - Get all bookings
- `GET /api/bookings/{id}` - Get booking by ID
- `POST /api/bookings` - Create a new booking

## Technologies Used

- Frontend:
  - React
  - Material-UI
  - Axios
  - React Router

- Backend:
  - Spring Boot
  - Spring Data JPA
  - MySQL
  - Lombok

## Contributing

Feel free to submit issues and enhancement requests. 