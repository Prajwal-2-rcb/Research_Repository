Research Repository


Research Repository is a robust web application built using Django that allows users to upload, manage, and download research papers. It serves as a centralized platform for researchers, students, and academics to share their work, access scholarly papers, and manage their profiles. The project includes essential features for seamless research management while providing an intuitive user interface and administrative capabilities.

Key Features
User Registration and Authentication:
Users can sign up, log in, and access their personalized dashboard to manage their papers and profile.

Research Paper Management:
Users can upload research papers, view all their submissions, and download any paper from the repository.

Profile Management:
Each user has a dedicated profile page where they can update their personal details and change their password.

Administrative Panel:
An admin panel is available for managing users, uploaded research papers, and overall system moderation, ensuring smooth operation and integrity of the repository.

Technologies Used
Django Framework:
Backend functionality and web application logic.

MySQL Database:
Manages data for users, research papers, and system settings.

HTML/CSS with Enhanced Styling:
Visually appealing and responsive front-end design, incorporating gradient colors, animations, and custom fonts.

How It Works
User Accounts:
Upon registration, users can create and manage their profiles, upload research papers, and browse the repository.

Research Paper Upload:
Users can submit research papers, providing details such as title, abstract, keywords, and manuscript file.

Paper Download:
Any paper in the repository is available for download, enabling easy access to the latest research.

Profile Customization:
Users can update their profile information, upload profile pictures, and reset passwords through their dashboard.

Admin Capabilities:
The admin panel allows system administrators to review user activity, manage submissions, and maintain the integrity of the repository.

Future Enhancements
Citation Tracking:
Adding a feature to track citations for each paper to enhance visibility and academic impact.

API Integration:
Incorporating APIs to fetch the latest research papers from external databases.

Advanced Search and Filtering:
Implementing advanced search functionality for better navigation of the repository.


Setup Instructions
Clone the repository:

Copy code
git clone https://github.com/yourusername/research-repository.git
Navigate to the project directory and install dependencies:
bash
Copy code
pip install -r requirements.txt
Set up the database and run migrations:
bash
Copy code
python manage.py migrate
Create a superuser for accessing the admin panel:
bash
Copy code
python manage.py createsuperuser
Run the server:
bash
Copy code
python manage.py runserver

