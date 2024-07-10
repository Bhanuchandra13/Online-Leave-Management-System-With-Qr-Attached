# Online Leave Management System with QR

## Project Overview

The Online Leave Management System with QR is a Django-based web application designed to manage student leaves and outings efficiently. The system uses QR code scanning to streamline the process and ensure accurate tracking.

## Features

- **User Authentication:** Secure login and registration for students and administrators.
- **Leave Requests:** Students can request leave online, and administrators can approve or reject requests.
- **QR Code Generation and Scanning:** QR codes are generated for approved leaves, which can be scanned for validation.
- **Admin Dashboard:** Administrators have a dashboard to view and manage leave requests and user information.
- **Notification System:** Email notifications are sent for leave request updates.

## Technologies Used

- **Backend:** Django, Python
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite (default, can be configured to use other databases)
- **QR Code:** QR code generation and scanning functionality

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/Bhanuchandra13/Online-Leave-Management-System-with-QR.git
    ```

2. Navigate to the project directory:

    ```sh
    cd Online-Leave-Management-System-with-QR
    ```

3. Create and activate a virtual environment:

    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

4. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

5. Apply the migrations:

    ```sh
    python manage.py migrate
    ```

6. Create a superuser (admin):

    ```sh
    python manage.py createsuperuser
    ```

7. Run the development server:

    ```sh
    python manage.py runserver
    ```

8. Open your browser and navigate to `http://127.0.0.1:8000/` to access the application.

## Usage

- **Students:** Register, log in, and request leaves using the leave request form.
- **Administrators:** Log in to the admin dashboard to manage leave requests and users.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [your email address].

---

Feel free to modify this template to better fit your project.
