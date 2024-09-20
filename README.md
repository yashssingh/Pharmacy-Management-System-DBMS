
# Pharmacy Management System (DBMS)

This project is a comprehensive Pharmacy Management System developed using Python and SQL, aiming to efficiently manage various tasks involved in running a pharmacy. The system covers essential features such as managing medicines, customers, suppliers, orders, and sales.

## Features

- **Medicine Management**: Add, update, delete, and view medicines in stock.
- **Customer Management**: Store and manage customer information.
- **Supplier Management**: Keep track of suppliers, their products, and contact details.
- **Order Processing**: Handle customer orders, including prescription verification.
- **Sales Management**: Track daily sales and generate sales reports.

## Technologies Used

- **Backend**: Python
- **Database**: SQL (e.g., MySQL, SQLite)
- **Tools/Frameworks**: Python SQL connector for database operations
- **Version Control**: GitHub

## File Structure

- `med.py`: The primary Python script handling the core functionalities of the system.
- `/sql/`: SQL files containing database schema and initialization scripts (if applicable).
- `/docs/`: Any related documentation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yashssingh/Pharmacy-Management-System-DBMS.git
   cd Pharmacy-Management-System-DBMS
   ```

2. Install necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database:
   - Import the SQL scripts provided (if applicable).
   - Configure the database connection settings in the `med.py` file.

4. Run the application:

   ```bash
   python med.py
   ```

## Usage

1. Navigate to the interface using the command-line.
2. Use the appropriate menu options to manage customers, medicines, suppliers, and sales.
3. Regularly update stock information and generate reports.

## Future Improvements

- Integrating a graphical user interface (GUI) for better user experience.
- Enhancing security features such as user authentication.
- Implementing additional reporting features for advanced sales analytics.

## Contribution

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
