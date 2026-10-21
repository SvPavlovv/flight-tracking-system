
# Real-Time Flight Tracking Web Application

### Bachelor's Thesis Project | Computer and Software Engineering

## About the Project

For my bachelor's thesis, I developed a web application that allows users to track aircraft and view flight information on an interactive map.

The idea was to build a complete application, not just a map displaying aircraft positions. I wanted to work with external APIs, backend development, databases, user authentication, and frontend functionality in the same project.

The application retrieves flight data from OpenSky Network, processes it through a Python backend, and displays aircraft positions using Leaflet and OpenStreetMap.

I also developed a user management system with authentication, different access levels, and an administration panel.

## Main Features

### Live Flight Tracking

- Aircraft displayed on an interactive map
- Flight information including position, altitude, speed, and heading
- Search and filtering options
- Aircraft details and additional flight information
- Flight traffic statistics
- Periodic updates of flight data
- Flight history

The application also includes temporary caching and a demo fallback mode when the external flight data source is unavailable.

### User Authentication

I implemented a user authentication system with:

- User registration and login
- Email-based two-factor authentication (2FA)
- Password recovery
- User session management
- Role-based access control

### Premium Features

The application includes additional functionality for users with Premium access:

- Saving favorite flights
- Tracking selected aircraft
- Managing Premium access

I also created a demonstration subscription page. It simulates Premium activation without processing real payments.

### Administration Panel

Users with administrator permissions can:

- View registered users
- Manage user roles
- Terminate active user sessions
- Remove user accounts
- View user statistics

### Interface Settings

- Light and dark themes
- Bulgarian and English language support
- Interactive map controls

## Technologies Used

| Component | Technology |
|-----------|------------|
| Backend | Python, FastAPI |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite |
| Interactive Map | Leaflet, OpenStreetMap |
| Flight Data | OpenSky Network API |
| Architecture | Client-server |

## How the Application Works

The application follows a client-server architecture.

The frontend handles the user interface, map visualization, and user interactions.

The FastAPI backend processes requests, retrieves external flight information, handles authentication, and communicates with the SQLite database.

SQLite stores user accounts, sessions, authentication-related information, flight history, and favorite flights.

When flight information is available, the backend processes it and sends it to the frontend, where aircraft are displayed on the map.

## What I Learned

This was one of my larger development projects, and it helped me gain practical experience in both backend and frontend development.

I worked with API integration, database design, authentication, user roles, and handling data that changes over time.

One of the more interesting parts was connecting the different components into a single application and making sure they worked together.

The project also helped me improve my debugging skills and better understand how a web application is structured beyond the user interface.

## Documentation

The full technical documentation is available in this repository.

It includes the system requirements, architecture, database design, implementation details, and screenshots of the application.

## Source Code

The source code is kept in a private repository and is not publicly available.

This repository is intended to present the project and its technical documentation.
