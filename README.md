# PG Life - Paying Guest Accommodation Platform

## 📋 Project Overview

PG Life is a full-stack web application designed to help users find and book paying guest (PG) accommodations across multiple cities. This project was developed as part of the **Internshala Full Stack Web Development Internship Training Program**.

## 🎯 Key Features

### 🏠 Home Page
- **Smart Search Bar**: Search for PGs by city name (case-insensitive)
- **City Quick Access**: Clickable circular city sections for instant browsing
- **Dynamic Results**: Real-time property listings based on database availability

### 📝 Property Listing Page
- **Beautiful Card Layout**: Property cards displaying key features and information
- **Advanced Filtering**: Sort properties by rent and rating (ascending/descending)
- **Popularity Indicator**: View how many users are interested in each property
- **Interactive Wishlist**: Heart icon to mark properties as interested (login required)
- **Real-time Updates**: Dynamic interest counter updates

### 🏡 Property Details Page
- **Image Carousel**: Beautiful image gallery of the selected property
- **Comprehensive Information**: Amenities, testimonials, and exact address
- **User Engagement**: See popularity metrics and add to wishlist
- **Detailed View**: All property features displayed in an organized layout

### 👤 User Dashboard
- **Profile Management**: View and manage account details
- **Saved Properties**: Collection of all interested properties across cities
- **Quick Actions**: Remove properties from wishlist with one click
- **Dynamic Updates**: Real-time UI changes based on user actions

### 🧭 Navigation Features
- **Responsive Navbar**: Brand name, login/signup options, and user greeting
- **Session Management**: Displays logged-in user's first name
- **Breadcrumb Navigation**: Easy tracking of current location in the app
- **Informative Footer**: Quick links to popular cities and copyright information

## 💻 Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- AJAX

### Backend
- PHP
- MySQL

## ✨ Technical Highlights

- **Fully Responsive Design**: Works seamlessly on all devices (mobile, tablet, desktop)
- **User-Friendly Interface**: Intuitive design with smooth navigation
- **Session Management**: Secure user authentication and authorization
- **Dynamic Content Loading**: AJAX for real-time updates without page refresh
- **Database Integration**: Efficient MySQL queries for data retrieval
- **Error Handling**: Custom UI for exceptions and user-friendly error messages
- **Guest Browsing**: Most features accessible without login for better UX

## 🚀 Features in Detail

### Authentication System
- User registration and login
- Session-based authentication
- Secure logout functionality
- Protected routes for dashboard access

### Search & Filter
- Case-insensitive city search
- Multiple filter options (rent, rating)
- Sort in ascending/descending order
- Real-time result updates

### Wishlist Management
- Add/remove properties with heart icon
- Visual feedback with color toggle
- Persistent across sessions
- Accessible from multiple pages

### Data Management
- Dummy data SQL file included
- Structured database schema
- Efficient query optimization
- Real-time data synchronization

## 📂 Project Structure

```
PGLIFE/
├── api/              # Backend API endpoints
├── css/              # Stylesheets
├── img/              # Images and assets
├── includes/         # Reusable PHP components
├── js/               # JavaScript files
├── index.php         # Home page
├── property_list.php # Property listing page
├── property_detail.php # Property details page
├── dashboard.php     # User dashboard
├── logout.php        # Logout functionality
├── dummy_data.sql    # Sample database data
└── README.md         # Project documentation
```

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience with:
- Full-stack web development workflow
- Frontend-backend integration
- Database design and management
- Responsive web design principles
- User authentication and session management
- AJAX and asynchronous JavaScript
- PHP and MySQL integration
- UI/UX best practices

## 🌟 Highlights

- **Internship Project**: Completed as part of Internshala Full Stack Web Development Training
- **Custom Implementation**: Personalized features based on user perspective
- **Production-Ready**: Fully functional and operational web application
- **Clean Code**: Well-organized and maintainable code structure

## 📱 Responsive Design

The application is fully responsive and tested on:
- Desktop (1920px and above)
- Laptop (1366px - 1920px)
- Tablet (768px - 1024px)
- Mobile (320px - 767px)

## 🔧 Setup Instructions

1. Clone the repository
2. Import `dummy_data.sql` into your MySQL database
3. Configure database connection in the includes folder
4. Set up a local server (XAMPP/WAMP/MAMP)
5. Access the application through localhost

## 👨‍💻 Developer

**Santhosh**  
Data Analyst | Full Stack Web Development Trainee

## 📝 License

This project was created for educational purposes as part of the Internshala training program.

---

⭐ If you found this project interesting, please consider giving it a star!
