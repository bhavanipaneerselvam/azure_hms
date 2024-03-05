# Hospital Management System

Hospital Management System is a web application designed to streamline the process of managing patient appointments, prescriptions, and overall hospital operations efficiently. It provides separate interfaces for patients, doctors, and administrators to interact with the system.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributors](#contributors)

## Features

### Patient Portal
- **Login**: Patients can securely login to their accounts.
- **Book My Appointment**: Patients can schedule appointments with their preferred doctors.
- **My Appointments**: View a list of upcoming and past appointments.
- **Prescriptions**: Access and manage prescriptions provided by doctors.

### Doctor Portal
- **Login**: Doctors can securely login to their accounts.
- **View Appointments**: Doctors can see a list of appointments scheduled with them.
- **Prescription Management**: Doctors can create and manage prescriptions for patients.

### Admin Portal
- **Login**: Administrators can securely login to their accounts.
- **User Management**: Add, edit, or remove patient and doctor accounts.
- **Appointment Management**: View and manage all appointments.
- **System Monitoring**: Monitor system health and usage statistics.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP
- **Database**: MySQL (or any other preferred database system)
- **Cloud Services**: Azure for hosting, Apache for server deployment
- **Monitoring**: Integrating monitoring AI services for system health monitoring

## Installation

To set up the Hospital Management System locally, follow these steps:

1. **Clone the repository**: 
    ```bash
    git clone https://github.com/your/repository.git](https://github.com/bhavanipaneerselvam/azure_hms
    ```

2. **Setup the Database**:
    - Create a MySQL database named `hospital_management`.
    - Import the database schema from `database.sql` file.

3. **Configure Database Connection**:
    - Open `config.php` file located in the `backend` directory.
    - Update the database connection details (hostname, username, password, database name).

4. **Deploy the Application**:
    - Host the `frontend` directory on a web server (e.g., Apache).
    - Host the `backend` directory on a PHP-enabled server.

5. **Access the Application**:
    - Visit the URL where you hosted the frontend to access the Hospital Management System.

## Usage

1. **Patient Portal**:
    - Patients can sign up or log in to their accounts.
    - They can book appointments with preferred doctors and view/manage their appointments and prescriptions.

2. **Doctor Portal**:
    - Doctors can log in to view appointments scheduled with them.
    - They can create and manage prescriptions for patients.

3. **Admin Portal**:
    - Administrators can log in to manage user accounts, appointments, and system monitoring.


## Azure Services 

## Azure Virtual Machines:

Host the backend PHP code and MySQL database.
Ensures high availability and scalability by enabling easy scaling of compute resources.
Provides flexibility in choosing operating systems and configuring virtual machine sizes.
## Azure Resource Groups:

Organizes all Azure resources related to the hospital management system into a logical group.
Simplifies resource management, access control, and monitoring.
## Azure Virtual Network:

Establishes a private network in the Azure cloud for secure communication between virtual machines and services.
Enables isolation and segmentation of resources to enhance security and compliance.
## Azure Monitor Insights:

Monitors the performance and health of the hospital management system.
Provides real-time insights, metrics, and logs for proactive troubleshooting and optimization.
Enables alerting and notification mechanisms for critical events.
## Azure AI Services:

Integrates AI capabilities for language understanding and chatbot functionalities.
Enhances patient engagement through conversational interfaces for appointment scheduling, prescription management, and FAQs.
Utilizes Azure Cognitive Services such as Language Understanding (LUIS) and Azure Bot Service for AI-powered interactions.\



## ScreenShort 
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/1a61c622-9466-4d30-9a80-e9dce4f6dcc8)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/bb94872c-9557-4441-bea3-4e9f7eba6cdb)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/b97a7e10-6053-49c1-9256-d4692086854d)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/3a854ba0-2206-4db5-8ff1-eb3fd38ff9cb)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/6c30fefb-5f15-491e-be4a-ffcc17aefef3)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/058467d3-5092-40b7-95c8-9d87e8f28c31)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/df0af038-04f7-4c7c-ac12-167320a38dc4)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153912844/62726717-2824-49a6-996d-c3bf35ffacc6)

![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/17acb5e9-9e08-4c58-a7aa-ad63af8dfcd0)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/ef163471-a692-4d7d-bc52-a0f030ce8604)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/6b7c5528-d44c-43ef-a48d-7fb7314af947)
















