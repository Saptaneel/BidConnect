# BidConnect

BidConnect is a freelancing platform built with HTML, CSS, PHP, and MySQL, utilizing the XAMPP Control Panel. It allows employers to post job offers and freelancers to bid on projects, promoting competitive pricing and efficient project matching.

## Features

- *Job Posting and Bidding System*: Developed a platform where employers can post job offers and freelancers can bid on projects, ensuring competitive pricing and efficient project matching.
- *Advanced Messaging*: Implemented a messaging system for direct communication, searchable by username or email, facilitating smooth interactions and document sharing.
- *Comprehensive Search*: Enabled robust search functionality, allowing users to find job offers and freelancers quickly using filters by username, email, or keywords.
- *Job Management*: Designed features to display recent and older job postings, ensuring visibility of new opportunities and easy access to archived listings.
- *Cover Letter Review*: Added functionality for freelancers to submit cover letters with bids, providing employers with tools to review and assess candidate suitability effectively.

## Technologies Used

- *Frontend*: HTML, CSS
- *Backend*: PHP
- *Database*: MySQL
- *Development Environment*: XAMPP Control Panel

## Getting Started

### Prerequisites

- XAMPP Control Panel
- Web Browser

### Installation

1. Clone the repository or download the source code.
2. Copy the project folder into the htdocs directory in your XAMPP installation.
3. Start the Apache and MySQL modules from the XAMPP Control Panel.
4. Import the database:
   - Open your web browser and go to http://localhost/phpmyadmin.
   - Create a new database called bidconnect.
   - Import the SQL file provided in the database folder to set up the necessary tables.
5. Open your web browser and navigate to http://localhost/bidconnect to start using the platform.

## Usage

1. *Employer*:
   - Register and log in to your account.
   - Post job offers with details and requirements.
   - Review bids and cover letters from freelancers.
   - Select a freelancer for the project.

2. *Freelancer*:
   - Register and log in to your account.
   - Browse job offers and submit bids.
   - Send cover letters to highlight your suitability for the job.
   - Communicate directly with employers through the messaging system.

## Project Structure

- index.php: The main entry point of the application.
- register.php: User registration functionality.
- login.php: User login functionality.
- post_job.php: Allows employers to post job offers.
- bid.php: Allows freelancers to bid on job offers.
- messages.php: Messaging system for communication between users.
- search.php: Search functionality to find jobs and freelancers.
- db_connection.php: Database connection setup.

## Learnings

- Gained experience in developing a full-stack web application with HTML, CSS, PHP, and MySQL.
- Improved skills in creating user authentication, job posting, and bidding systems.
- Enhanced understanding of implementing messaging systems and comprehensive search functionality.

## License

This project is open-source and available under the MIT License.
