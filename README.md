About
AFJOB_WEB is a web application designed for the recruitment process. It allows recruiters to post job openings and job seekers to browse and apply for these openings. The application has different user roles, including Admin, Recruiter, and Job Seeker, each with different permissions.

Features
✅ User Authentication: Allows different users to log in (Admin, Recruiter, Job Seeker).
✅ Recruiter Dashboard: Recruiters can post new job listings and manage existing ones.
✅ Job Seeker Profile: Job seekers can create their profiles and apply for available jobs.
✅ Search and Filter Jobs: Job seekers can search for and filter job listings based on various criteria.
✅ Admin Dashboard: Admin can manage users (recruiters and job seekers) and moderate the job listings.

Technologies Used
Frontend:

ASP.NET MVC: Used for building the web application's frontend.
Bootstrap: For responsive design and styling.
JavaScript/jQuery: Used for interactive elements on the landing page.
Backend:

ASP.NET Identity: For user authentication and role management (Admin, Recruiter, Job Seeker).
Database:

Microsoft SQL Server (SSMS): Database for storing job listings, user profiles, and application data.
Entity Framework: Used as the ORM to interact with the database.

Prerequisites
Before you begin, ensure you have the following installed:

Visual Studio 2022 (or later) with the necessary ASP.NET MVC development tools.
Microsoft SQL Server Management Studio (SSMS) to manage the database.
.NET Core SDK (version 3.1 or later).
Setup
Clone the Repository:git clone (https://github.com/preet-bajwa06/AFJOB.git)
Setup the Database:

Open SSMS and create a new database (if not already created).
Use Entity Framework migrations to create the necessary tables in the database.
Update-Database
Configure the Connection String:
Run the Application:
