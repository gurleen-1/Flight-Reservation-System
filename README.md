# Flight-Reservation-System

This is a project on flight reservation system
## Architecture
The application is organized into multiple classes, each with a clear responsibility:

- **Flight / DomesticFlight / InternationalFlight** – represent flight details such as origin, destination, price and departure time. DomesticFlight and InternationalFlight extend Flight for specialized behaviour.
- **Passenger and Reservation** – manage customer details and booking data.
- **LoginPage** – the main entry point; provides login screen and navigation between domestic and international booking flows. It displays flight tables and handles user events.
- **WindowUtilities and listeners** – helper classes for managing windows, events and user input.

Images (PNG/JPG) located in the `img` folder are used for icons and backgrounds.

## Prerequisites
You will need a Java Development Kit (JDK 8 or later) and a Java IDE or the command‑line tools.

## Setup & Running the Application
1. **Clone the repository:**
   ```bash
   git clone https://github.com/gurleen-1/Flight-Reservation-System.git
   cd Flight-Reservation-System
   ```
2. **Compile the source files:**
   ```bash
   javac *.java
   ```
3. **Run the application:**
   ```bash
   java LoginPage
   ```
   The login window should appear. Use the default credentials (`admin`/`admin`) to sign in and begin searching for flights.

## Repository Structure
- `*.java` – Java source code for the flights, reservations and UI.
- `*.class` – compiled class files.
- `img/` – images used in the GUI (e.g. business.jpg, economic.jpg).
- `README.md` – this project description.

## Future Improvements
This project was developed for educational purposes and does not persist data between sessions. Possible enhancements include:
- Connecting to a database to store and retrieve flights and bookings.
- Allowing users to create individual accounts rather than a single admin login.
- Implementing validation, pricing logic and error handling.
- Adding tests and documentation.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have ideas for improvements or bug fixes.

## License
This project is released under the MIT License. See [LICENSE](LICENSE) for more information.

## Contact
If you have any questions, feel free to reach out via GitHub or contact the project maintainer.
