# Event Ticketing Project

This project is a comprehensive event ticketing system that integrates a frontend built with Angular, a backend using Spring Boot and MongoDB, and a command-line interface (CLI) to simulate the process of multiple customers and vendors using the system at the same time. The application aims to provide a seamless and efficient way to manage events, vendors, customers, tickets, and transactions, ensuring a smooth user experience from start to finish.

---

## Table of Contents

- [Event Ticketing Project](#event-ticketing-project)
- [Tools Used](#tools-used)
- [Setup Instructions](#setup-instructions)
  - [Frontend Setup](#frontend-setup)
  - [Backend Setup](#backend-setup)
  - [CLI Setup](#cli-setup)
    - [Prerequisites](#prerequisites)
    - [Setup Instructions](#setup-instructions-1)
    - [Usage](#usage)
- [Additional Details](#additional-details)
- [Contributing](#contributing)
  - [Steps to Contribute](#steps-to-contribute)
- [License](#license)

---

## Tools Used

The following were the tools and technologies used during the development of the project:

- Angular
- Spring Boot
- Java
- TypeScript
- Docker
- MongoDB
- PrimeNG components
- Jackson for JSON
- SLF4j for Logging

---

## Setup Instructions

### Frontend Setup

The frontend of this project is built using Angular. For detailed setup instructions and troubleshooting tips, please refer to the [frontend README](https://github.com/ammar-jesliy/event-ticketing-frontend/blob/main/README.md).

### Backend Setup

The backend is developed using Spring Boot and MongoDB. For detailed setup instructions and troubleshooting tips, please refer to the [backend README](https://github.com/ammar-jesliy/event-ticketing-backend/blob/main/README.md).

### CLI Setup

The command-line interface (CLI) is designed to simulate multiple customers and vendors interacting with the system simultaneously. Follow these steps to set up the CLI:

#### Prerequisites

- Java Development Kit (JDK) 11 or later installed on your machine.
- The backend service must be running to ensure CLI operations work correctly.

#### Setup Instructions

1. **CLone the Backend repository:**

   ```bash
   git clone https://github.com/ammar-jesliy/event-ticketing-backend.git
   cd event-ticketing-backend
   ```

2. **Navigate to the Cli class**

3. **Run the Cli class**

#### Usage

When the CLI is executed, it displays a menu with various options. Users can interact with the system by selecting a number corresponding to the desired action. Below is the usage guide for each menu option:

```plaintext

*********************************************************************
*                            MENU OPTIONS                           *
*********************************************************************
    1) Start simulation of multiple users buying and selling tickets
    2) Print current configuration settings
    3) Edit configuration settings
    4) Print customer and vendor details
    0) Quit
*********************************************************************

```

1. Start Simulation

Simulates multiple users (vendors and customers) interacting with the system: - Vendors release tickets to a ticket pool. - Customers buy tickets from the same ticket pool.

2. Print Current Configuration Settings

Displays the current configuration settings for the application, including: - Max Capacity of the ticket pool - Ticket release rate of the vendors - Ticket purchase rate of the customers.

3. Edit Configuration Settings

Allows the user to modify system configurations, these new configurations then get saved in a JSON file.

4. Print Customer and Vendor Details

Fetches and displays detailed information about the customers and vendors used for the simulation.

0. Quit

Exits the CLI.

**NOTE**: Ensure the backend is running before using the CLI.

---

### Additional Details

- **PrimeNG components** are used in the frontend for UI components.
- **Jackson** is used in the backend for JSON processing.
- **SLF4j** is used for logging throughout the application.

For any issues or further assistance, please refer to the respective README files or contact me at [ammarjc1@gmail.com](mailto:ammarjc1@email.com).

## Contributing

Contributions are welcome! Please contribute to the appropriate repository based on the part of the project you wish to modify:

- Frontend: Visit the [event-ticketing-frontend repository](https://github.com/ammar-jesliy/event-ticketing-frontend).
- Backend: Visit the [event-ticketing-backend repository](https://github.com/ammar-jesliy/event-ticketing-backend).

### Steps to Contribute

1. **Fork the Appropriate Repository:**
   Click the "Fork" button in the target repository to create a personal copy.

2. **Clone Your Fork:**
   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/ammar-jesliy/repository-name.git
   ```

3. **Create a new branch**
   Create a branch for your feature or fix.

   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Commit your changes**
   Add descriptive commit messages for clarity

   ```bash
   git commit -m "Add a meaningful commit message"
   ```

5. **Open a Pull Request**

- Navigate to the respective repository (frontend or backend).
- Open a Pull Request (PR) detailing your changes and referencing any relevant issues.

## License

This project is licensed under the MIT License.
