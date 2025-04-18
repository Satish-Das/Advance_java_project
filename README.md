# Food Donation Web Application - Food Donate

## Project Overview
Jeevan Asha is a web-based food donation platform that connects food donors with those in need. This application helps to reduce food waste and address hunger by facilitating the donation process. Users can register, login, donate food, and track their donations through an intuitive interface.

## Features
- **User Authentication**: Secure registration and login system
- **Profile Management**: Users can view and edit their profiles
- **Food Donation**: Simple form to donate food with details like food type, quantity, and location
- **Admin Dashboard**: For managing users and donations
- **Responsive Design**: Works on various screen sizes and devices

## Technology Stack
- **Backend**: Java Servlets (Jakarta EE)
- **Frontend**: JSP, HTML, CSS, JavaScript, Bootstrap
- **Database**: MySQL
- **Server**: Apache Tomcat
- **File Upload**: MultipartConfig for image uploads

## Database Schema
The application uses a MySQL database with the following main tables:
- **users_register**: Stores user registration information
- **donations**: Records all food donation transactions

## Project Structure
- **src/main/java/**: Contains all Java servlets
  - LoginServlet.java: Handles user authentication
  - RegisterServlet.java: Manages user registration
  - DonateServlet.java: Processes food donations
  - EditProfileServlet.java: Updates user profiles
  - And more...
- **src/main/webapp/**: Web resources
  - **Pages/**: JSP pages (index, donate, login, etc.)
  - **Components/**: Reusable UI components
  - **CSS/**: Stylesheets
  - **JavaScript/**: Client-side scripts
  - **assets/**: Images and other media

## Setup Instructions
1. **Prerequisites**:
   - JDK 11 or higher
   - Apache Tomcat 10.0 or higher
   - MySQL 8.0 or higher

2. **Database Setup**:
   - Create a database named `food_donate`
   - Import the SQL schema (if available)
   - Default credentials: username: `root`, password: `` (empty)

3. **Build & Deployment**:
   - Build the project using your IDE (Eclipse recommended) or Maven
   - Deploy the WAR file to Tomcat

4. **Access**:
   - Open your browser and navigate to `http://localhost:8080/Project/`

## Usage
1. **Register/Login**: Create an account or login with existing credentials
2. **Donate Food**: Fill out the donation form with required details
3. **Profile Management**: View and edit your profile information
4. **Admin Access**: Administrators can access additional features through the admin panel

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any queries or support, please contact the project maintainers.

---
Developed by Satish Das 