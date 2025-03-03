# Book Car Maintenance Project
<img src="https://github.com/user-attachments/assets/e26f2915-5c18-43c1-8e98-a922c9d1c5b6" width="800" />

## Project Overview
This project is a C# Windows Forms application that allows users to book a car maintenance appointment. The form includes validation for customer details (such as name, contact information, and vehicle details) and ensures that the appointment is booked correctly based on the provided information.

## Features
- **Book Appointment**: Users can fill out a form with their details (customer name, contact info, car make/model, appointment date) to book a car maintenance appointment.
- **Input Validation**: The application validates the input for customer name, email, postal code, phone numbers, year, and appointment date.
- **Pre-fill**: A button that pre-fills the form with example data for testing purposes.
- **Reset**: Clears all fields in the form to their default values.
- **Close**: Closes the application.
- **Save Appointment**: After successful validation, the appointment is saved to a file called `appointment.txt`.

## Technologies Used
- C# .NET (Windows Forms)
- File I/O using `StreamWriter` for saving appointments
- Validation helper methods for form validation
