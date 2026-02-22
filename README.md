# Airbnb - Full Stack Web Application

A full-stack Airbnb-inspired web application where users can register, log in, create property listings, edit/delete their own listings, and add reviews to other listings. The application includes proper authentication and authorization to ensure users can only modify content they own.

---

## Features

Authentication & Authorization
- User Sign Up / Login / Logout
- Secure password hashing
- Session-based authentication
- Protected routes
- Authorization: Users can only edit/delete their own listings
- Review ownership validation (only the review author can delete their review)

Listings Management
- Create new property listings
- View all listings
- View individual listing details
- Edit your own listings
- Delete your own listings

Reviews & Comments
- Add reviews to listings
- Delete only your own review
- Linked reviews to listings using database relationships

UI & UX
- Responsive design using Bootstrap
- Flash messages for success/error handling
- Clean and user-friendly interface

---

## Tech Stack

Frontend
- HTML5  
- CSS3  
- JavaScript (ES6)  
- Bootstrap  

Backend
- Node.js  
- Express.js  

Database
- MongoDB  

Authentication & Session Management
- Passport.js  
- express-session  

---

## Architecture

- MVC (Model-View-Controller) pattern  
- RESTful routing  
- Middleware-based authentication & authorization  
- MongoDB relationships between Users, Listings, and Reviews  

---

## Installation & Setup

1. Clone the repository
```
git clone https://github.com/Aditya-17319/Airbnb.git
cd Airbnb
```

2. Install dependencies
```
npm install
```

3. Create a `.env` file in the root directory and add:
```
DB_URL=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
```

Note: Replace `your_mongodb_connection_string` and `your_secret_key` with your own values. Do not commit real secrets to GitHub.

4. Start the server
```
npm start
```

5. Open in browser
```
http://localhost:8080
```

Note: The server runs on port 8080. If you deploy the project, the host may assign a different port.

---

## Project Structure

```
├── models/
├── routes/
├── controllers/
├── views/
├── public/
├── app.js
└── package.json
```

---

## Screenshots

- Home page
- <img width="1898" height="910" alt="homepage png" src="https://github.com/user-attachments/assets/78f84fd9-a128-4b8b-afdc-22d4709e9c24" />

- Login Page
- <img width="994" height="652" alt="login png" src="https://github.com/user-attachments/assets/0fe7d6af-acab-4918-aa52-3ebd1622271d" />

- Add Listing Page
<img width="1157" height="933" alt="newlisting png" src="https://github.com/user-attachments/assets/c96414c6-7257-4e75-88c1-d976cf85cb44" />

- Review Section
- <img width="1054" height="857" alt="Review comment (1)" src="https://github.com/user-attachments/assets/7e4060b4-c652-4043-80a1-3e7373607766" />
 

---

## Future Improvements

- Image upload with cloud storage  
- Search & filter functionality  
- Google OAuth authentication  
- Payment integration  
- Map integration for property location  

---

## Author

Aditya Kumar

---

Note: This project is for educational purposes. Do not use it for commercial purposes without permission.
