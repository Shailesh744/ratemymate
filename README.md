# Student Profile Rating Website

This web application allows users to register, create profiles, and rate or review other students. It features user authentication, profile management, review and rating system, tag support, karma points, and email notifications.

## Features
- User registration, login, and email verification
- Profile creation and editing
- Submit reviews and ratings for other users
- Tag reviews with descriptive keywords
- Like reviews and accumulate karma points
- Email notifications for new reviews
- Admin panel for managing users and content


## Installation
1. **Clone the repository** to your web server directory.
2. **Install dependencies** (PHPMailer is included in `PHPMailer-6.8.0`).
3. **Create a MySQL database** and import the schema from `config/schema.sql`.
4. **Configure database and mail settings** in `config/database.php` and `config/mail.php`.
5. **Set file permissions** for the `uploads/photos/` directory.
6. **Access the site** via your local or remote web server.

## Configuration
- **Database:** Edit `config/database.php` with your MySQL credentials.
- **Email:** Edit `config/mail.php` for SMTP settings (used for verification and notifications).

## Usage
- Register a new account and verify your email.
- Create and edit your profile.
- Browse other profiles and submit reviews with ratings and tags.
- Like reviews to give karma points.
- Admins can manage users and content via the admin panel.

## License
This project is for educational purposes. PHPMailer is included under its own license in the `PHPMailer-6.8.0` directory.

## Credits
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) for email functionality.
- [Bootstrap]([Bootstrap](URL_ADDRESSbootstrap.com/) for responsive design.
- robobird it solution and service for developing and designing this project 

---
For questions or support, contact the project maintainer.

## How to Contribute

We welcome contributions to improve this project! To contribute:

1. **Fork the repository** on GitHub.
2. **Clone your fork** to your local machine.
3. **Create a new branch** for your feature or bugfix.
4. **Make your changes** with clear, descriptive commit messages.
5. **Test your changes** to ensure nothing is broken.
6. **Push your branch** to your forked repository.
7. **Open a Pull Request** describing your changes and why they should be merged.

**Contribution Guidelines:**
- Follow the existing code style and structure.
- Update documentation as needed.
- Be respectful and constructive in discussions.

Thank you for helping make this project better!
