# Prajaahar Rakshak

<a href="https://github.com/AtharvaKulkarniIT/Prajaahar_Rakshak"><img src="https://visitor-badge.laobi.icu/badge?page_id=AtharvaKulkarniIT.Prajaahar_Rakshak" alt="Visitors"/></a>
<a href="https://github.com/AtharvaKulkarniIT/Prajaahar_Rakshak/stargazers"><img src="https://img.shields.io/github/stars/AtharvaKulkarniIT/Prajaahar_Rakshak" alt="Stars Badge"/></a>
<a href="https://github.com/AtharvaKulkarniIT/Prajaahar_Rakshak/network/members"><img src="https://img.shields.io/github/forks/AtharvaKulkarniIT/Prajaahar_Rakshak" alt="Forks Badge"/></a>
<a href="https://github.com/AtharvaKulkarniIT/Prajaahar_Rakshak/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/AtharvaKulkarniIT/Prajaahar_Rakshak?color=green"></a>



This repository houses a comprehensive System developed using Node.js, Express, EJS, Bootstrap and MongoDB. The system facilitates the seamless coordination of surplus food donations from donors to NGOs or local food banks, optimizing the process through dynamic assignment of delivery agents.

## Features

- **User Roles:** Donor, receiver(admin) and agent roles for tailored user experiences.
- **Dynamic Donations:** Submit and track surplus food donations with ease.
- **Agent Assignment:** Efficient assignment of delivery agents based on predefined criteria.
- **Real-time Updates:** Keep donors, agents and receivers informed with real-time status updates.
- **Responsive Design:** Bootstrap ensures a visually appealing and responsive UI across devices.

## Setup Instructions

1. **Clone the repository:**
 ```
git clone https://github.com/AtharvaKulkarniIT/Prajaahar_Rakshak.git
```


2. **Install dependencies:** 
```
npm install
   ```


4. **Configure MongoDB connection using environment variables:**
   - Install MongoDB following the [official installation guide](https://docs.mongodb.com/manual/installation/).
   - Create a `.env` file in the root of your project and add the MongoDB connection URL:

     ```env
     MONGO_URI=mongodb://localhost:27017/PrajaaharRakshak
     ```

     Adjust the URL according to your MongoDB setup.

   - Update the `config/db.js` file to use the environment variable:

     ```javascript
     // config/db.js
     require('dotenv').config(); // Load environment variables
     module.exports = {
         // other configurations
         url: process.env.MONGO_URI || 'mongodb://localhost:27017/PrajahaarRakshak',
     };
     ```

5. **Start the application:** `npm start`
6. **Access the system at:** `http://localhost:5000`

## Technologies Used

- **Front-end:** EJS, Bootstrap
- **Back-end:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** Passport.js

## Demo
Watch the demo [click here](https://youtu.be/XmYxlQWBnvo?si=VYcf5Zjhqxq1d-eE).

