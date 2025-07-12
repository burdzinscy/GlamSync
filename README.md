# GlamSync: Smart Booking & Cashflow Management for Beauty Services

![GlamSync Logo](https://img.shields.io/badge/GlamSync-Salon%20Management-blue.svg)
![Release Version](https://img.shields.io/github/release/burdzinscy/GlamSync.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

GlamSync is a comprehensive booking and cashflow management system tailored for salons, spas, and barbershops in Kenya. This platform streamlines appointment scheduling, client management, and financial tracking, integrating with M-Pesa for easy transactions. It also supports walk-ins and loyalty tracking, ensuring that businesses can manage their operations efficiently.

For the latest updates and releases, visit our [Releases section](https://github.com/burdzinscy/GlamSync/releases).

## Features

- **Appointment Scheduling**: Easily manage bookings with a user-friendly calendar interface.
- **Client Management**: Keep track of client information and history for personalized service.
- **M-Pesa Integration**: Simplify payments with seamless M-Pesa transactions.
- **Walk-in Management**: Cater to walk-in clients with ease.
- **Loyalty Tracking**: Reward loyal customers and enhance retention.
- **Revenue Management**: Analyze cashflow and generate financial reports.
- **Point of Sale System**: Manage sales directly from the platform.
- **User Roles**: Define roles for staff and manage permissions effectively.

## Technologies Used

- **Frontend**: React.js, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Integration**: M-Pesa API
- **Deployment**: Heroku, Docker

## Installation

To set up GlamSync locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/burdzinscy/GlamSync.git
   ```

2. Navigate to the project directory:

   ```bash
   cd GlamSync
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file and configure your environment variables. You can refer to `.env.example` for guidance.

5. Start the application:

   ```bash
   npm start
   ```

Your application should now be running on `http://localhost:3000`.

For downloadable releases, check the [Releases section](https://github.com/burdzinscy/GlamSync/releases) for the latest version.

## Usage

After installation, you can start using GlamSync. Here’s a quick guide:

1. **Create an Admin Account**: Upon first launch, create an admin account to manage the system.
2. **Add Services**: Navigate to the services section to add available services for clients.
3. **Manage Appointments**: Use the calendar to view, add, or modify appointments.
4. **Track Clients**: Access the client management section to view client history and preferences.
5. **Process Payments**: Use the integrated M-Pesa system for handling transactions.

## API Documentation

GlamSync provides a RESTful API for developers to integrate with other systems. Here’s a brief overview of the main endpoints:

- **GET /api/appointments**: Retrieve all appointments.
- **POST /api/appointments**: Create a new appointment.
- **GET /api/clients**: Fetch all clients.
- **POST /api/clients**: Add a new client.
- **POST /api/payments**: Process payments through M-Pesa.

For more detailed API documentation, please refer to the `API_DOCS.md` file in the repository.

## Contributing

We welcome contributions from the community. To contribute to GlamSync:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Submit a pull request detailing your changes.

Please ensure your code adheres to our coding standards and passes all tests.

## License

GlamSync is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or support, please contact us at support@glamsync.com.

For the latest updates, check the [Releases section](https://github.com/burdzinscy/GlamSync/releases).