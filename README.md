# Telecom Billing System

This is a C-based mini-project for a **Telephone Billing System**. The system is designed to automate the billing process for telephone users by managing customer records, calculating bills, and providing efficient billing services.

## Project Overview

The **Telecom Billing System** aims to automate the tasks associated with managing telephone bills, such as adding and modifying customer records, viewing payment history, and generating bills. The system reduces manual labor, improves accuracy, and provides a user-friendly interface for billing operations.

### Key Features
- **Add New Records**: Allows the addition of new customer billing records.
- **Modify Records**: Facilitates updating customer records such as phone number, name, or outstanding balance.
- **View Records**: Displays a list of all customer billing records.
- **Search Records**: Provides a feature to search for customer records by phone number.
- **Payment Processing**: Handles payments made by customers and updates their billing records accordingly.

## Technologies Used

- **Programming Language**: C
- **Development Environment**: Code::Blocks, GCC Compiler
- **Operating System**: Windows, Linux

## Project Structure

- `/src` - Contains the C source code for the project
- `/docs` - Documentation for the project
- `/snapshots` - Contains screenshots of the project interface and outputs
- `/bin` - Compiled binary files (if applicable)

## Installation and Setup

### Prerequisites
- GCC or any other C compiler
- Code::Blocks or any C IDE

### Steps to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TelecomBillingSystem.git
   ```

2. Open the project in your C IDE (such as Code::Blocks).

3. Compile the code:
   - For GCC:
     ```bash
     gcc telecom_billing.c -o telecom_billing
     ```

4. Run the executable:
   ```bash
   ./telecom_billing
   ```

## How It Works

1. **Main Menu**: Upon starting the system, users are presented with a menu with options to add, list, modify, search, or process payments.
2. **Add Records**: Allows users to input customer details such as phone number, name, and initial bill amount.
3. **Modify Records**: Users can edit existing records (phone number, name, and bill amount).
4. **View Records**: The system displays a list of all customer billing records.
5. **Search Records**: Users can search for a specific customer by entering their phone number.
6. **Payment Processing**: Customers can make payments, and their outstanding balance will be updated in the system.

## Code Structure

```c
void addrecords();       // Add new customer records
void listrecords();      // List all customer records
void modifyrecords();    // Modify existing records
void searchrecords();    // Search for a record by phone number
void payment();          // Process payments
```

### Example Commands
- **Add Records**: Adds a new customer record (phone number, name, amount).
- **Modify Records**: Modify an existing record by phone number.
- **Search Records**: Search a record by phone number.
- **Payment**: Process the payment and update the customer’s outstanding balance.

## Future Enhancements

- **Graphical User Interface (GUI)**: Implement a user-friendly graphical interface for easier access and improved interaction.
- **Database Integration**: Replace file handling with a proper database system (e.g., MySQL) for better scalability and security.
- **Advanced Billing Features**: Include detailed billing features like call duration, call rates, and real-time billing.



## Contributors

- Mohammed Ali (4AD21CI036)
- Mohammed Fahad Khan (4AD21CI037)
- Ramya J R (4AD21CI043)
- Rahil Khan (4AD21CG023)

