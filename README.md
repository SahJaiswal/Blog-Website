# Django Blog Website

This is a Django-based website that allows users to post, delete, and update blogs. Users can also maintain their profiles on the website. The project includes a registration system where users can create an account, login, and reset their password through email.

## Features

- User Registration: Users can create an account by providing their details such as username, email, and password.

- Login and Authentication: Registered users can log in to the website using their credentials. Authentication is implemented to ensure secure access to user-specific features.

- Blog Creation: Users can create blog posts by providing a title, content, and optionally uploading an image.

- Blog Editing and Deletion: Users have the ability to edit or delete their own blog posts.

- Profile Management: Each user has a profile page where they can update their personal information, including their profile picture.

- Password Reset: If a user forgets their password, they can initiate a password reset process. An email will be sent to their registered email address containing a unique link. By following the link, the user can reset their password.

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/django-blog-website.git
```

2. Set up the database:

```
python manage.py migrate
```

3. Start the development server:

```
python manage.py runserver
```

4. Open your web browser and visit `http://localhost:8000` to access the website.

## Configuration

- Email Settings: Configure the email settings in the `settings.py` file to enable the password reset functionality. You will need to provide your email service provider's SMTP details, such as the host, port, username, and password.

- Secret Key: Generate a new secret key and update the `settings.py` file with the new value. It is recommended to keep the secret key confidential and not share it publicly.

## Usage

- Create an account by clicking on the "Register" link on the homepage and providing the necessary information.

- Log in using your credentials to access the blog creation, editing, and deletion features.

- Manage your profile by navigating to the profile page and updating your information.

- In case you forget your password, click on the "Forgot Password" link on the login page and follow the instructions in the email to reset it.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the project's GitHub repository.
