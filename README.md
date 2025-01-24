# Blood Bank Management System

This project is a Blood Bank Management System that provides various features for blood donors, recipients, and administrators. It allows users to register, donate, and request blood, while keeping track of blood group data and donor information.

## Features

- **Home Page:** Overview of the system and navigation options.
- **Blood Donation:** Allows users to donate blood and submit personal details.
- **Need Blood:** Request for blood from users in need.
- **Search Blood Group:** Search for available blood groups based on location and requirements.
- **About Us:** Information about the organization and its mission.
- **Contact Us:** Contact form for inquiries or suggestions.
- **Why Donate Blood:** Educational page on the importance of blood donation.

## Files

- `index.html`: The main homepage.
- `about_us.php`: About Us page.
- `contact_us.php`: Contact form page.
- `donate_blood.php`: Blood donation page.
- `footer.php`: Footer section for all pages.
- `head.php`: Common header for pages.
- `home.php`: Homepage content.
- `need_blood.php`: Request blood page.
- `savedata.php`: Handles form submissions and data saving.
- `search_blood_group.php`: Search blood group by type.
- `slider.php`: Image carousel for the homepage.
- `ticker.php`: News ticker for announcements.
- `why_donate_blood.php`: Educational content about blood donation.
- `blood_bank_database.sql`: SQL file for the blood bank database structure.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-repo/blood-bank-management-system.git
cd blood-bank-management-system
```

2. Import the `blood_bank_database.sql` into your MySQL database:

```bash
mysql -u your_username -p your_database_name < blood_bank_database.sql
```

3. Set up the PHP environment on your server and ensure `conn.php` is correctly configured to connect to the database.

4. Open the project in your browser and start using the system.
