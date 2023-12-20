Project Overview

The Clinic Registration and Management System is a console application developed using C# and Entity Framework Core. This system is designed to offer a user-friendly platform for patients to register, select medical specializations, and book appointments. Additionally, an admin module is included to efficiently review and manage all appointments.

Project Scope

Users can choose from various medical specializations offered by the clinic. Patients can book appointments within the clinic's operating hours (12 hours a day), with each appointment lasting 30 minutes. All user data, including appointments, will be stored and managed using Entity Framework Core connected to a relational database. Features For Patients:

Registration: Users can register by providing necessary personal information (name, contact details, etc.). Specialization Selection: Patients can choose from a list of medical specializations available in the clinic. Appointment Booking: Users can schedule appointments by selecting a preferred date and time within the clinic's operating hours. For Admin:

Appointment Overview: Admins can view a comprehensive list of all appointments made by patients. Appointment Management: Admins can approve, reschedule, or cancel appointments as needed. Database Entity Structure Patient Entity: Attributes: PatientID (Primary Key), Name, ContactDetails, etc. Specialization Entity: Attributes: SpecializationID (Primary Key), SpecializationName, Description, etc. Appointment Entity: Attributes: AppointmentID (Primary Key), PatientID (Foreign Key), SpecializationID (Foreign Key), Date, Time, Status, etc. Technical Stack Language: C# Database: Entity Framework Core (Code First Approach) Frameworks: .NET Core Design Pattern: Object-Oriented Programming (OOP) User Interface: Console Application Additional Features (Optional) Email Notification: Send automated email notifications to patients regarding their upcoming appointments. Data Validation: Implement robust data validation to ensure the integrity of user inputs. Getting Started To run the Clinic Registration and Management System locally:

Clone this repository. Ensure you have .NET Core SDK installed. Set up your database connection in the ClinicDbContext class. Run the application using the command dotnet run in the project directory. Contributors Salim Al-Yaaqoubi License This project is licensed under the MIT License.

Feel free to contribute, provide feedback, or report issues. Happy coding!
