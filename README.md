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
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/86bf13fe-d323-41ea-bda9-d6dc28d59681
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/ebfc50f9-27a8-4a71-b5a0-f74d700c7d0d)

![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/9febcbe9-1912-420f-bf64-4c253658fb3f)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/e0a1b31e-2100-44c4-8f82-0411ac8b7693)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/db894ecd-6451-4506-8dac-ec21131ef91f)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/25e9c4f0-7f05-4f8b-b1c6-61f03df42f77)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/064c10b1-748e-445b-a31d-8ca4783cf6f4)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/d507ed18-03bc-42d3-aa57-776247537225)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/778b6a59-e6e1-4fdb-8c81-bf5b70b2cf78)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/9bb0453d-1a50-4ecc-ac0c-8122c30bdd94)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/7f382ef8-6acb-42d7-86f8-1090284c7359)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/b1d87221-68e0-4967-8bef-7e8df910dba3)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/d2fb51e3-cbd3-42c7-acf2-cc983a93a838)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/78365688-d561-427c-a030-ab25fcac8d3d)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/5cb2d0a3-471a-495f-b6f7-046a565bb12b)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/79fb773a-2c1e-4a6c-80a9-a12f256f8a54)
![image](https://github.com/bhavanipaneerselvam/azure_hms/assets/153825193/d662fa9a-b107-4201-99b1-c4bfcffec653)
![Uploading image.png…]()






































