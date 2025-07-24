# flipkart-intern#
Employee Leave Management System (ELMS)

## Overview
The Employee Leave Management System (ELMS) is a comprehensive web application designed to streamline and automate the process of managing employee leave requests. It provides features for employees to request leave, managers to approve/reject requests, and administrators to manage the system and generate reports.

## Features
- **User Authentication**: Secure login for employees, managers, and administrators
- **Leave Request Management**: Submit, view, and track leave requests
- **Approval Workflow**: Managers can approve/reject pending leave requests
- **Leave Balance Tracking**: Automatic tracking of available leave days
- **Reporting**: Detailed reports on leave trends and department statistics
- **Admin Dashboard**: Comprehensive system management tools
- **Responsive Design**: Works on desktop and mobile devices

## Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Backend**: Python, Flask
- **Database**: SQLite (with SQLAlchemy ORM)
- **Authentication**: Flask-Login
- **Charts**: Chart.js

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sairam-somisetti/flipkart-intern.git
   cd elms
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Access the application at `http://localhost:127.0.0.1:5000

## Usage
### Login Credentials
- **Admin**: username `admin`, password `admin123`
- **Employee**: username `employee`, password `emp123`
- **Manager**: username `manager`, password `man123`

### Employee Features
- View leave balances
- Submit new leave requests
- Track request status
- View request history

### Manager Features
- Approve/reject leave requests
- View team leave calendar
- Monitor pending approvals

### Admin Features
- Manage all users
- Configure leave types
- Generate system reports
- Monitor system activity

## Screenshots

### Login Page
<img width="1894" height="901" alt="Image" src="https://github.com/user-attachments/assets/3fc1e0d2-b7fa-432a-a6ed-3371c27d0ac2" />

### Employee Dashboard
<img width="1918" height="963" alt="Image" src="https://github.com/user-attachments/assets/6bed3582-248b-46cf-94c6-2cfe16af5032" />

### Leave Request Form
<img width="1904" height="955" alt="Image" src="https://github.com/user-attachments/assets/09649452-8cba-4e88-8f55-eb8c2b192afe" />

### Manager Approval Dashboard
<img width="1918" height="962" alt="Image" src="https://github.com/user-attachments/assets/e79c25a9-a9f8-4ed4-8c8c-af9ee2a5d835" />

### Reports Dashboard
<img width="1906" height="964" alt="Image" src="https://github.com/user-attachments/assets/dd9f49c8-4dd3-45da-a744-aac931c35586" />

## Database Schema
The system uses the following database tables:
- `User`: Stores employee information
- `LeaveType`: Defines different types of leave
- `LeaveRequest`: Tracks all leave requests
- `LeaveBalance`: Maintains leave balances for employees

## API Endpoints
- `/api/dashboard_stats`: Returns dashboard statistics (JSON)
- `/api/leave_status/<request_id>`: Returns status of a leave request

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Contact
For questions or support, please contact the project maintainer at sgvnpsairam@example.com
