# Hospital Management System🏥

Welcome to the **Hospital Management System**, a Java-based application designed to streamline hospital operations. This system allows you to efficiently manage patients, doctors, and appointments, helping hospitals and clinics stay organized and provide better care.

## Features

- **Add Patient**: Easily register new patients into the system by adding their personal details and medical information.
- **View Patients**: Access a list of all registered patients, complete with their personal and medical details for easy reference.
- **View Doctors**: Browse a list of doctors with their specializations and availability for scheduling appointments.
- **Book Appointment**: Schedule appointments by selecting a patient using their unique patient ID and a doctor using their unique doctor ID.

## System Requirements

- Java Development Kit (JDK) 8 or above
- MySQL or any relational database for storing data
- IDE such as IntelliJ IDEA for development
- JDBC for database connectivity

## Installation

1. **Clone the repository**:
   ```bash
   git clone https:https://github.com/Abhilash9019/Hospital-MANAGMENT-SYSTEM-JDBC-.git
   ```

2. **Set up the database**:
   - Create a MySQL database named `hospital_management`.
   - Run the provided SQL script in the `/db` folder to create the necessary tables (`patients`, `doctors`, `appointments`).

3. **Configure the database connection**:
   - Open the `DatabaseConfig.java` file and update the following fields with your database details:
     ```java
     String url = "jdbc:mysql://localhost:3306/hospital";
     String user = "root";
     String password = "yourpassword";
     ```

4. **Run the application**:
   - Open the project in your preferred IDE.
   - Compile and run the `HospitalManagementSystem` file.

## Usage

1. **Add a New Patient**:
   - From the menu, select "Add Patient."
   - Enter the patient's details such as name, age, contact information, and medical history.

2. **View Patients**:
   - Select "View Patients" to see a list of all registered patients with their details.

3. **View Doctors**:
   - Select "View Doctors" to see a list of doctors available for appointments.

4. **Book an Appointment**:
   - Choose "Book Appointment" from the menu.
   - Enter the patient’s ID and the doctor’s ID to confirm the appointment.

## Project Structure

- `src/`: Contains all the Java source files.
  - `HospitalManagementSystem`: Entry point of the application.
  - `Patient.java`, `Doctor.java`, `Appointment.java`: Models for handling patient, doctor, and appointment data.

- `db/`: Contains SQL scripts for setting up the database.

## Future Enhancements

- Add features to update or delete patient and doctor records.
- Implement an admin login for better security and access control.
- Add reporting features for generating summaries of hospital operations.

#
