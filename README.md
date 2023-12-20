# Project: Edunify - Web Development Assignment

This mini-project involves designing a web application using Next.js and MySQL, consisting of two pages. Page 1 allows users to input and store school data, while Page 2 fetches and displays the stored school data.

### Frontend (Next.js, React, HTML, CSS, JavaScript):

#### Project Structure:

- **/addSchool/addSchool.jsx**: Form page for adding school data.
- **/showSchools/showSchools.jsx**: Page to display a list of schools.
- **/components/SearchBox.jsx**: Component for a responsive search box.
- **/components/Navbar.jsx**: Component for the navigation bar.
- **/components/HeroSection.jsx**: Component for the hero section.

#### Setup Instructions:

1. Install Node.js and npm on your machine.
2. Clone the repository: `git clone https://github.com/Triptiskillz/edunify_TriptiSharma.git`.
3. Navigate to the project directory: `cd client`.
4. Install dependencies: `npm install`.
5. Start the development server: `npm run dev`.

### Backend (MySQL, Node.js):

#### Project Structure:

- **/server.js**: Node.js server script.
- **/routes/api.js**: API routes for handling school data.
- **/models/school.js**: MySQL schema and model for the `schools` table.

#### Setup Instructions:

1. Install Node.js and npm on your machine.
2. Set up a MySQL database with the name `edunify`.
3. Configure MySQL connection in `/server.js`.
4. Install dependencies: `npm install`.
5. Start the server: `npm start`.

### Database (MySQL):

#### Database Schema:

```sql
CREATE TABLE schools (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name varchar,
  address varchar,
  city varchar,
  state varchar,
  contact varchar,
  image varchar,
  email_id varchar
);
```

### Additional Notes:

- Ensure MySQL is running before starting the server.
- Access the frontend at `http://localhost:3000` and the backend at `http://localhost:3001/api`.
- The project uses `react-hook-form` for form handling.

### Contributors:

- Tripti Sharma

Feel free to modify the structure and instructions based on your project's specific requirements.
