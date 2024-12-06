# Real Estate Management System

A web application for efficient property management, enabling users to manage buildings, apartments, and occupants. The app offers detailed property insights, occupancy roles, and statistical views, simplifying real estate operations for professionals.

## Features
- Manage buildings, apartments, and occupants.
- View detailed information on properties and tenants/owners.
- Generate statistics for properties and buildings.
- Intuitive web interface for seamless navigation.

## Technology Stack
- **Backend:** Java Spark
- **Frontend:** FreeMarker Templates
- **Database:** H2 (embedded)
- **Database Access:** JDBC (Java Database Connectivity)

## URIs
- `/` : Landing page
- `/login` : User login
- `/register` : User registration
- `/homepage` : Navigation page
- `/buildings` : List of buildings
- `/buildings/{id}` : Details of a specific building
- `/buildings/{id}/apartments` : Apartments in a specific building
- `/apartments/{id}` : Details of a specific apartment
- `/apartments/{id}/occupants` : Occupants of a specific apartment
- `/occupants/{id}` : Details of a specific occupant
- `/statistics` : Overall real estate statistics
- `/buildings/{id}/statistics` : Statistics for a specific building

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-estate-management.git
2. Navigate to the project directory:
   ```bash
   cd real-estate-management
3. Build the project:
   ```bash
   mvn clean install
4. Run the application:
   ```bash
   java -jar target/real-estate-management.jar
5. Access the app at `http://localhost:4567.`

## Future Enhancements
- User roles with varying permissions.
- Advanced analytics and reporting.
- Integration with external property listing services.

## License
This project is licensed under the MIT License
   
