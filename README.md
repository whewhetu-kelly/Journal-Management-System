# Web-Based Journal Management System

A comprehensive web-based Journal Management System developed for the Petroleum Training Institute (PTI), Effurun, to streamline manuscript submission, peer review, editorial workflow, publication management, and academic journal administration. The platform supports Authors, Reviewers, Editors, and Administrators through a secure role-based system with automated workflow management, grammar checking, similarity analysis, notifications, and publication tracking.

---

## Features

- Multi-role authentication (Author, Reviewer, Editor, Administrator)
- Manuscript submission and revision management
- Peer review workflow
- Reviewer assignment
- Editorial decision management
- Publication scheduling
- Similarity analysis
- Grammar checking with LanguageTool
- Internal messaging and notifications
- Audit trail and activity logs
- Administrative dashboard and reports
- Secure role-based access control

---

## Tech Stack

- PHP 8.2+
- MySQL 8.0+
- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Apache 2.4+
- LanguageTool REST API

---

## Installation

1. Clone or copy the project into your web server directory.
2. Create the project database.
3. Import the database schema and seed files.
4. Configure the database credentials.
5. Ensure the upload directory is writable.
6. Configure Apache and enable `mod_rewrite`.
7. Install and start LanguageTool.
8. Launch the application and log in using the administrator account.

---

## User Roles

### Author

- Submit manuscripts
- Upload revisions
- Track submission status
- View reviewer feedback

### Reviewer

- Review assigned manuscripts
- Submit structured evaluations
- Recommend acceptance or rejection

### Editor

- Assign reviewers
- Monitor review progress
- Run similarity analysis
- Run grammar checks
- Make publication decisions

### Administrator

- Manage users
- Manage roles
- View reports
- Monitor system activities

---

## Workflow

Draft → Submitted → Under Review → Revision Required ↔ Revised → Accepted → Published / Rejected

---

## System Architecture

The application follows a layered architecture consisting of:

- Presentation Layer
- Business Logic Layer
- REST API Layer
- Database Layer
- LanguageTool Integration

---

## Security

- Role-based authentication
- Session management
- Password hashing
- CSRF protection
- Input validation
- SQL injection prevention
- XSS protection

---

## Deployment

Compatible with:

- Apache
- XAMPP
- WAMP
- LAMP
- Shared PHP Hosting

---

## License

MIT License.

---

## Support

For questions or project inquiries, create an issue in this repository.
