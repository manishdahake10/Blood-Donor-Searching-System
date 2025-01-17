# Blood Donor Searching System

## Overview
This is a Blood Donor Searching System built using PHP, JSON, HTML, CSS, JavaScript, and SQL. The system allows users to search for blood donors based on blood type, location, and other criteria. It helps connect individuals in need of blood with available donors, making it a vital tool for hospitals, blood banks, and emergency situations.

## Features
- Search for blood donors by blood type, location, and availability.
- View a list of blood donors with their contact details and availability status.
- Add new blood donors to the system.
- Edit or update donor information.
- Delete donor records from the system.
- Provide easy access for users to request or donate blood.

## Technologies Used
- **PHP**: Server-side scripting language used for the backend.
- **HTML/CSS**: Used for the structure and styling of the user interface.
- **JavaScript**: For dynamic interactions and form validation.
- **SQL**: Used to manage and interact with the donor database.
- **JSON**: For data exchange between the client and server.

## Requirements
- A server with PHP support (e.g., Apache or Nginx).
- MySQL or MariaDB for database management.
- A modern web browser (e.g., Chrome, Firefox).

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/manishdahake10/BloodDonorSearchSystem.git
    ```

2. Navigate to the project directory:
    ```bash
    cd BloodDonorSearchSystem
    ```

3. Set up the database:
    - Create a new MySQL database (e.g., `blood_donor_db`).
    - Import the database schema from `database.sql` into the newly created database.

4. Configure database connection:
    - Edit the `config.php` file to set your database connection details (host, username, password, database name).

5. Start the server (if using Apache or Nginx):
    - Place the project files in the server's root directory (e.g., `/var/www/html` for Apache on Linux).
    - Access the system through `http://localhost` or your server's address.

6. The system should be ready to use.

## Usage
Once the system is running, you can access it via your web browser. Here's how you can use it:

- **Search Donors**: Enter the required blood type and location to search for available blood donors.
- **View Donors**: The list of matching blood donors will be displayed along with their contact details and availability.
- **Add Donor**: Click the "Add Donor" button to add a new donor to the system.
- **Edit Donor**: Select an existing donor and click "Edit" to modify their details.
- **Delete Donor**: Select a donor and click "Delete" to remove them from the system.
- **Exit**: Close the application through your browser.

### Output Screenshots

**Home page**
![Capture1](https://github.com/user-attachments/assets/a43faa08-fd5d-4e04-86e0-728eba6545f9)<br><br>

**Donor List Page**
![Home BDS_Bar](https://github.com/user-attachments/assets/afcf8326-6133-4a8e-b5ac-cc965d66c0ec)<br><br>

**User login Form**
![UserLogin](https://github.com/user-attachments/assets/a5ee5b65-d02a-4f55-a380-59ab7d55687b)<br><br>

**User Dashboard**
![UserDashboard](https://github.com/user-attachments/assets/860ae567-8970-4791-accf-c1d9ab8c8bd3)
<br><br>
**User Detail**
![UserDetail](https://github.com/user-attachments/assets/24b14ef4-da27-4e3c-b277-2da90f7dc1b9)<br><br>

**User Info update**
![UserUpdateInfo](https://github.com/user-attachments/assets/1cc9bc37-51c2-4a2a-8cdc-64789f7bef8d)<br><br>

**Admin Login**
![Admin Login](https://github.com/user-attachments/assets/0c88733c-263f-48c4-863e-68d6dd783be7)<br><br>

**User Dashboard**
![admindashboard](https://github.com/user-attachments/assets/d2e9202f-8594-4466-99fd-33997a10c7e5)<br><br>


## Code Structure
The project consists of the following structure:

- `index.php`: The main file that handles user interactions and displays the donor search results.
- `add_donor.php`: A form for adding new blood donors to the system.
- `edit_donor.php`: A page to edit the details of an existing donor.
- `delete_donor.php`: Handles the deletion of a donor's information.
- `config.php`: Contains the database connection configuration.
- `database.sql`: SQL file containing the schema for the blood donor database.

## Contribution
Feel free to fork this repository and contribute by opening issues or pull requests. Suggestions for additional features or improvements are always welcome!

## Author 
GitHub: [manishdahake10](https://github.com/manishdahake10)
## Collaborator
GitHub: [pankaj1892](https://github.com/pankaj1892)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
