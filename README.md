# Social Web

This Django project is a social app that allows users to register, log in, and interact with each other through various features such as following other users, liking images, and bookmarking images.

## Features

### 1. Authentication and User Management:
- Users can register for an account using a registration form.
- Registered users can log in using their username and password.
- The project utilizes Django's built-in authentication system for user management.

### 2. Social Features:
- Users can follow other users, and the app tracks these relationships using a Contact model.
- Actions such as user registration, following users, and liking images are recorded using the Action model, allowing for activity feeds and user engagement tracking.
- Social authentication is implemented with Facebook, Twitter, and Google OAuth2, allowing users to log in using their social media accounts.

### 3. Image Management:
- Users can upload images, providing a title, description, and URL.
- Images are associated with users and stored in the database, along with metadata such as upload date, likes, and bookmarks.
- Users can like images, and the total number of likes for each image is tracked.

### 4. Views and Templates:
- Various views are provided for functionalities such as user registration, login, profile editing, dashboard display, image uploading, and image listing.
- Templates are used for rendering HTML pages, providing a user interface for different actions and functionalities.

### 5. Middleware and Debugging:
- Middleware such as Debug Toolbar is included for debugging purposes.
- The project uses SQLite as the database backend for development.

### 6. URL Routing and Configuration:
- URLs are defined using Django's URL routing mechanism, directing requests to appropriate views.
- Settings are configured to manage static files, media files, and other project-related configurations.

### 7. Forms and Models:
- Django forms are used for user input validation and data handling.
- Models are defined for user profiles, image data, social interactions, and other application data.


## Contributing
Contributions are welcomed! Please feel free to submit a Pull Request.
