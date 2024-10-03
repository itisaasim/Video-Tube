
# VideoTube - YouTube Clone Project

## Overview

VideoTube is a full-featured YouTube clone built using PHP, MySQL, JavaScript, and HTML/CSS. It replicates core YouTube functionality including video uploads, comments, likes/dislikes, user profiles, subscriptions, and more.

## Key Features

- Video upload and conversion 
- Video player with custom controls
- Comment system with replies
- Like/dislike functionality
- User registration and profiles
- Subscription system
- Video search
- Trending videos section
- Responsive design

## Technical Details

### Backend
- PHP for server-side logic
- MySQL database for data storage
- PDO for database interactions
- Custom classes for key entities (User, Video, Comment etc.)

### Frontend  
- HTML5 video player
- JavaScript/jQuery for dynamic interactions
- Bootstrap for responsive layout
- Custom CSS for styling

### Key Components

- Video processing using FFmpeg
- Thumbnail generation
- AJAX for asynchronous actions (likes, comments etc.)
- Session-based authentication

## Setup and Usage

1. Install XAMPP or similar PHP/MySQL environment
2. Clone repository to web server directory
3. Import provided SQL file to set up database
4. Configure database connection in `includes/config.php`
5. Access via `http://localhost/VideoTube`

## File Structure

- `index.php` - Homepage
- `watch.php` - Video viewing page  
- `upload.php` - Video upload page
- Classes in `includes/classes/`
- JavaScript in `assets/js/`
- CSS in `assets/css/`

## Key Functionality

- Video upload converts to MP4 and generates thumbnails
- Comments support nested replies
- Like/dislike affects both videos and comments
- Trending algorithm based on view count
- Search queries video titles and uploader usernames

This project demonstrates a complex, feature-rich web application built primarily with PHP. It showcases database design, OOP principles, frontend/backend integration, and handling of multimedia content.
