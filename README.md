# Hotel Management System

The Hotel Management System is a Java-based application designed to facilitate the management of hotel operations including room booking, customer management, reservation handling, and invoice generation. It utilizes a MySQL database to store and manage hotel-related data.

## Features

- **Room Management:** Allows adding, updating, and deleting room information including room type, availability, and price.
  
- **Customer Management:** Enables managing customer details including name, contact information, and booking history.
  
- **Reservation:** Facilitates making, modifying, and canceling reservations.
  
- **Invoice Generation:** Automatically generates invoices for customer bookings.

## Project Structure

- **build:** Contains build-related files.
  
- **dist:** Contains distribution files.
  
- **nbproject:** Contains NetBeans project configuration files.
  
- **src:** Contains the source code files.
  
- **.DS_Store:** macOS system file.
  
- **.gitignore:** Specifies intentionally untracked files to ignore.
  
- **build.xml:** Ant build script.
  
- **manifest.mf:** Manifest file.

## Getting Started

1. **Clone Repository:** Clone this repository to your local machine using:

    ```
    git clone https://github.com/Rushikesh197/Hotel-Management-Project-JAVA-DBMS.git
    ```

2. **Import Project:** Import the project into NetBeans or any Java IDE of your choice.

3. **Database Setup:**
   
   - Install MySQL if not already installed.
   
   - Create a new database named `hotel_management_system`.
   
   - Import the SQL file `hotel_management_system.sql` provided in the `database` directory to set up the database schema and sample data.

4. **Database Configuration:**

   - Open `DBConnect.java` file located in the `src` directory.
   
   - Update the `DB_URL`, `USERNAME`, and `PASSWORD` variables with your MySQL database credentials.

5. **Run Application:** Run the application from your IDE.

## Contributing

Contributions are welcome. Feel free to fork the repository, make changes, and submit pull requests.

## Contact

For any inquiries or support, please contact rushikeshgadewar@gmail.com.
