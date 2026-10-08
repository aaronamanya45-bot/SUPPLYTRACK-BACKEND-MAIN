# SUPPYTRACK-BACKEND-MAIN

The backend service for **SupplyTrack**, a comprehensive supply chain and order management system. It provides a RESTful API built with Node.js to manage users, items, categories, carts, orders, pickup stations, supplier workflows, and real-time package tracking.

## Features

* **Authentication & Authorization**: Secure JWT-based auth with role-based access control (Admin, Customer, Supplier, Station).
* **Catalog Management**: CRUD operations for items, categories, and item images upload.
* **Cart & Order Processing**: Customer shopping cart handling, checkout flows, and order management[cite: 1].
* **Station & Supplier Integration**: Management of pickup stations and dedicated supplier orders/profiles[cite: 1].
* **Tracking System**: Package tracking functionality and timeline management[cite: 1].

## Tech Stack

* **Runtime**: Node.js[cite: 1]
* **Database**: MySQL / Relational Database (via schema and seed scripts)[cite: 1]
* **Middleware**: Custom async handlers, authentication, role verification, and file uploads (Multer)[cite: 1]

## Project Structure

* `config/`: Database configuration and connections (`db.js`)[cite: 1]
* `controllers/`: Business logic for admin, auth, cart, categories, items, orders, pickup stations, profiles, suppliers, and tracking[cite: 1]
* `database/`: SQL schema definitions (`schema.sql`) and seed data (`seed.sql`)[cite: 1]
* `middleware/`: Authentication, role-checking, upload handling, and async error-catching middleware[cite: 1]
* `routes/`: API route endpoints mapped to controllers[cite: 1]
* `uploads/`: Local storage for item images[cite: 1]
* `server.js`: Application entry point[cite: 1]

## Getting Started

### Prerequisites

* Node.js installed[cite: 1]
* MySQL database instance[cite: 1]

### Installation & Setup

1. Clone the repository[cite: 1].
2. Install dependencies:
   ```bash
   npm install
