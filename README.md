# Farm_tour_request_project
# Farm Tour Request Form Project

This project demonstrates a simple web application for a farm that allows users to request a farm tour through a form. The form collects the user's name, email, phone number, preferred tour date, and an optional additional message. The submitted form data is stored in a MySQL database for further processing.

## Features

- User-friendly form for requesting a farm tour.
- Form validation to ensure required fields are filled out.
- Backend PHP script to handle form submission and store data in a MySQL database.
- Basic styling using HTML and CSS.

## Setup

1. **Database Setup:**

   Create a MySQL database named `farm_tours` with a table named `tour_requests`. The table should have columns: `id` (auto-increment), `name`, `email`, `phone`, `tour_date`, and `message`.

2. **Web Server Setup:**

   Ensure you have a web server (e.g., Apache) with PHP and MySQL support installed.

3. **Repository Setup:**

   - Clone this repository to your web server's document root.
   - Configure the database connection in the `process_form.php` file (update `$servername`, `$username`, `$password`, and `$dbname`).

4. **Usage:**

   Access the project through your web browser, and you will see the farm tour request form. After filling out the form and submitting it, the data will be stored in the MySQL database.

## Customization

Feel free to customize the project according to your needs:

- Modify the form fields or styling in `index.html`.
- Enhance the PHP script for form processing in `process_form.php`.
- Add additional validation, security measures, or error handling.

## Contributing

Contributions are welcome! If you have any improvements, bug fixes, or additional features, feel free to submit a pull request.



**Disclaimer:** This is a basic example and might not cover all aspects of a production-ready application. Be sure to consider security best practices, data validation, and error handling when adapting this project for real-world use.

For any questions or assistance, feel free to contact dannganizip@gmail.com
