# Bus Scheduling and Booking System

The Bus Scheduling and Booking System was designed to streamline the process of scheduling bus routes and booking tickets for passengers. This application allows users to view available bus schedules, book tickets, and manage reservations efficiently. The system aims to provide a user-friendly interface for both bus operators and passengers to ensure smooth and hassle-free travel planning.

### Key Features
- **User Registration and Login:** secure authentication for users to manage their accounts.
- **Schedule Management:** Admins can add, update, and delete bus schedules.
- **Ticket Booking:** Users can book tickets on available bus routes.
- **Booking Management:** Users can view, modify, and cancel their books.
- **Admin Dashboard:** Admins have access to a dashboard for managing schedules, bookings, and users.

### Technologies Used
- **Frontend -** HTML, CSS
- **Backend -** PHP
- **Database -** MySQL
- **Local Server -** XAMPP

## How to Install and Run the Project

### Prerequisites
- **XAMPP**: Download and install from [Apache Friends](https://www.apachefriends.org/index.html).

### Installation Steps
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/it21223976/Bus_Scheduling_and_booking_system.git
    ```
2. **Move to the Project Directory**:
    ```sh
    cd Bus_Scheduling_and_booking_system
    ```
3. **Start XAMPP**:
    - Open XAMPP Control Panel.
    - Start Apache and MySQL.

4. **Set Up the Database**:
    - Open phpMyAdmin from XAMPP Control Panel.
    - Create a new database named `bus_scheduling`.
    - Import the `bus_scheduling.sql` file located in the `database` folder.

5. **Configure the Database Connection**:
    - Open `config.php` file in the project directory.
    - Update the database credentials if necessary.

6. **Run the Project**:
    - Place the project folder in the `htdocs` directory of XAMPP.
    - Open a web browser and navigate to `http://localhost/bus_scheduling_booking_system`.

## Tests

### Running Tests
1. Navigate to the project directory:
    ```sh
    cd bus_scheduling_booking_system
    ```
2. Ensure XAMPP is running with Apache and MySQL services.
3. Use a testing framework or manually test the application by interacting with various features and ensuring proper functionality.

## How to Contribute to the Project

1. Fork the repository.
2. Create your feature branch:
    ```sh
    git checkout -b feature/YourFeature
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/YourFeature
    ```
5. Open a pull request.
