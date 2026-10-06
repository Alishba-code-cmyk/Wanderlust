#  Wanderlust — Full-Stack Travel & Stay Platform

Wanderlust is a full-stack web application inspired by Airbnb that allows users to discover, create, manage, and review property listings.

The project was built to understand how a real-world web application works across the frontend, backend, database, authentication, authorization, image storage, and deployment.

##  Live Demo

🔗 **Live Demo:** [https://your-project-name.onrender.com](https://wanderlust-mom6.onrender.com/listings)

## 📌 Features

###  User Authentication
- User registration and login
- Logout functionality
- Session-based authentication
- Protected routes for authenticated users

###  Property Listings
- Create new property listings
- View all available listings
- View individual listing details
- Edit listings
- Delete listings
- Listing ownership and authorization

### Search & Discovery
- Browse available properties
- Filter and search listings
- Location-based listing information

###  Reviews & Ratings
- Add reviews to listings
- Delete reviews
- Display reviews with author information
- Review authorization

###  Image Upload
- Upload listing images
- Cloudinary integration for image storage
- Display uploaded images dynamically

###  Location & Maps
- Convert listing locations into geographical coordinates
- Display listing locations using an interactive map
- OpenStreetMap/Leaflet integration

###  Authorization & Security
- Authentication using Passport.js
- Protected routes
- Owner-based authorization
- Session management
- Environment variables for sensitive credentials

---

##  Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- EJS
- Bootstrap

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- MongoDB Atlas
- Mongoose

### Authentication
- Passport.js
- Passport Local Strategy
- Express Session

### Image Storage
- Cloudinary
- Multer

### Maps & Geolocation
- Leaflet.js
- OpenStreetMap
- Nominatim

### Deployment
- Render

### Development Tools
- Git
- GitHub
- VS Code
- npm

---

##  Project Architecture

```text
Wanderlust
│
├── controllers/
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
│
├── models/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── routes/
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── views/
│   ├── layouts/
│   ├── listings/
│   ├── users/
│   └── includes/
│
├── public/
│   ├── css/
│   └── js/
│
├── utils/
├── middleware.js
├── cloudConfig.js
├── app.js
├── package.json
└── README.md
