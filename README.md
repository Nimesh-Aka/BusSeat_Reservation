# BusSeat Reservation System

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The BusSeat Reservation System is a web and mobile application designed to streamline the booking of seats on long-range private buses in Sri Lanka. It aims to eliminate the need for phone calls or physical visits by allowing users to easily search, select, and reserve bus seats online. Bus operators can manage their schedules, view bookings, and communicate with customers efficiently.

## Features

- **User Authentication:** Sign-up, login, and profile management.
- **Search and Filter:** Users can search for buses based on routes, departure times, and more.
- **Seat Selection:** Interactive seat maps for selecting seats.
- **Booking Management:** Users can view, modify, and cancel bookings.
- **Payment Gateway:** Secure online payments.
- **Notifications:** Email or SMS notifications for booking confirmations.
- **Route Visualization:** Map-based route visualization.
- **User Ratings and Reviews:** Option for users to rate and review bus services.

## Technologies Used

- **Frontend:**
  - Web: Angular.js
  - Mobile: Flutter
- **Backend:** Node.js with Springboot
- **Database:** MySQL
- **Payment Gateway:** Stripe
- **APIs:** Google Maps API for route visualization
- **Deployment:** Docker, AWS/GCP/Azure

## Setup and Installation

### Prerequisites

- Node.js (20.11.0)
- npm (10.2.4)
- Angular CLI (18.1.0)
- Flutter SDK
- Docker
- MySQL (8.0.31)
- Stripe API keys
- Google Maps API key

### Installation Steps

1. Clone the repository:

   ```
   git clone https://github.com/your-username/BusSeat-Reservation-System.git
   ```

2. Navigate to the project directory:

   ```
   cd BusSeat-Reservation-System
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Set up environment variables:

   - Create a `.env` file in the root directory and add your environment variables, such as `DB_HOST`, `DB_USER`, `DB_PASSWORD`, `STRIPE_KEY`, and `GOOGLE_MAPS_API_KEY`.

5. Run the backend server:

   ```
   npm start
   ```

6. Run the frontend:

   ```
   ng serve
   ```

7. Run the Flutter mobile app:

   ```
   flutter run
   ```

8. Set up the database:

   ```
   mysql -u root -p
   CREATE DATABASE bus_seat_reservation_system;
   EXIT;
   ```

9. Import the database schema and seed data into your MySQL database.

10. Deploy the application to a cloud provider of your choice.

## Usage

- Visit the web application at `http://localhost:4200` to access the user interface.
- Use the mobile app to access the system on-the-go.
- Log in or sign up to start booking seats.

## Screenshots

![Login Screen](https://i.imgur.com/7X3X3X0.png)
![Bus Search](https://i.imgur.com/7X3X3X0.png)
![Seat Selection](https://i.imgur.com/7X3X3X0.png)
![Booking Confirmation](https://i.imgur.com/7X3X3X0.png)

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please open an issue on this repository or contact the maintainers directly.

---
