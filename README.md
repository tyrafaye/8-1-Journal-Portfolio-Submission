# 8-1-Journal-Portfolio-Submission

# Travlr Getaways

A full-stack travel booking and management application built with Node.js, Express, and MongoDB.

## Project Overview

Travlr Getaways is a comprehensive travel management platform that allows users to browse, book, and manage travel experiences. The application features both a customer-facing frontend and an administrative interface for managing travel listings, rooms, and meals.

## Tech Stack

- *Backend*: Node.js with Express.js
- *Database*: MongoDB with Mongoose ODM
- *Frontend*: Handlebars (HBS) templating engine
- *Authentication*: Passport.js with JWT
- *API*: RESTful API with CORS support
- *Admin Dashboard*: Separate admin interface for content management

## Project Structure

- app_api/ - API endpoints and database models
  - models/ - MongoDB schemas and models
  - routes/ - API route handlers
  - config/ - Configuration files including Passport setup
- app_server/ - Server-side rendering and routes
  - views/ - Handlebars templates
  - routes/ - Web route handlers
- public/ - Static assets
- travlr-admin/ - Admin dashboard application
- bin/ - Application startup scripts

## Key Features

1. *User Authentication*
   - Secure login/signup system
   - JWT-based authentication
   - Passport local strategy implementation

2. *Travel Management*
   - Browse travel packages
   - Room bookings
   - Meal plans
   - User profile management

3. *Admin Dashboard*
   - Content management system
   - Travel package administration
   - User management
   - Booking oversight

4. *API Integration*
   - RESTful API endpoints
   - CORS enabled for cross-origin requests
   - Secure routes with JWT authentication

## Getting Started

1. Install dependencies:
   
   npm install
   

2. Set up environment variables:
   Create a .env file with necessary configurations

3. Start the application:
   
   npm start
   

4. For database seeding:
   
   npm run seed
   

## Dependencies

- Express.js - Web application framework
- Mongoose - MongoDB object modeling
- Handlebars - Template engine
- Passport - Authentication middleware
- JWT - Token-based authentication
- CORS - Cross-origin resource sharing
- And various other utilities (see package.json)

## Architecture

The application follows a modular architecture with clear separation of concerns:
- MVC pattern for web routes
- RESTful API design
- Separate admin interface
- Component-based frontend
- Secure authentication layer

## Security Features

- JWT-based authentication
- Passport local strategy
- Encrypted passwords
- Protected API endpoints
- Environment variable configuration

## Contributing

This is a proprietary project for Travlr Getaways. Please refer to internal documentation for contribution guidelines.

## License

Private and Proprietary - All rights reserved
