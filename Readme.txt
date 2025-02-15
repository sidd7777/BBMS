
# Blood Bank Management System (BBMS)

## Overview
The Blood Bank Management System is a Java-based GUI application designed to manage blood donations, donor records, and blood inventory. The system was built using Eclipse with a drag-and-drop interface for the GUI design and hand-coded logic for the functionality. MySQL is used for the backend database, and JDBC handles connectivity.

## Project Structure
- **GUIFormExamples/test/**  
  Contains all the Java source files for the application. This folder is the main codebase.
  
- **Blood_Bank_Management_System/Libraries/**  
  Contains the required JAR files:
  - **jcalendar.jar** – Provides date-selection functionality.
  - **rs2xml.jar** – Used for processing and displaying table data.
  
- Other folders and files may be included as sample projects or examples; these are not essential to the core application.

## Prerequisites
- **Java JDK 8 or above** – Ensure you have Java installed.
- **Eclipse IDE** – Recommended for compiling and running the project.
- **MySQL** – Used as the database backend.
- **JDBC Driver for MySQL** – Included in your project dependencies (if not, download and add it).

## Setup Instructions
1. **Clone the Repository**
   - Open your terminal/command prompt and run:
     ```
     git clone https://github.com/sidd7777/bbms.git
     cd bbms
     ```

2. **Import the Project into Eclipse**
   - Open Eclipse.
   - Navigate to *File → Import → Existing Projects into Workspace*.
   - Select the root folder of the repository.
   
3. **Add Required Libraries**
   - The required JAR files (`jcalendar.jar` and `rs2xml.jar`) are located in the `Blood_Bank_Management_System/Libraries` folder.
   - Right-click on your project in Eclipse, select *Properties → Java Build Path → Libraries*, and add these JAR files to your build path.

4. **Configure the MySQL Database**
   - Import the provided SQL script (if available) to set up the database schema.
   - Update the database connection settings in your code (typically in a file such as `ConnectionProvider.java`).

5. **Run the Application**
   - Navigate to the main class (for example, `login.java` or `Main.java` in the `GUIFormExamples/test` folder).
   - Right-click the file in Eclipse and select *Run As → Java Application*.

## Usage
- **Admin Login:** Use valid credentials to access the system.
- **Donor Management:** Add, update, and delete donor details.
- **Inventory Management:** Manage blood stock by increasing or decreasing available units.
- **Search Functionality:** Look up donors based on blood group or location.

## Notes
- This repository includes several sample files and folders that demonstrate various aspects of the project. These extra files can be removed if not needed.
- If you wish to exclude these samples from your repository, consider adding a `.gitignore` file with the paths to the unwanted files/folders.

## Future Enhancements
- Cloud-based database integration.
- SMS or email notifications for donor registration and blood requests.
- Enhanced user interface improvements.
- Mobile application integration.
