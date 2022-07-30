# Flasky - The web application blog website

## What is Flasky?

This project is a blog website developed using python, flask, html, css, and other technologies to enable users to post their ideas, comments, editing it and following each other.

## Technologies used

- [Flask](https://flask.palletsprojects.com/) - The web framework used in this project.
- [Python](https://www.python.org/) - The programming language used in this project.
- [Markdown](https://en.wikipedia.org/wiki/Markdown) - The markup language used in this project.
- [Bootstrap](https://getbootstrap.com/) - The framework used in this project.
- [JQuery](https://jquery.com/) - The library used in this project.
- [SQLite](https://www.sqlite.org/) - The database used in this project.
- [Git](https://git-scm.com/) - The version control system used in this project.

## How to use Flasky?

- [Register](#register) - Register a new account.
- [Confirm](#confirm) - Confirm your account vie email link.
- [Login](#login) - Login to your account.
- [Post](#post) - Post a new idea.
- [Edit](#edit) - Edit your post.
- [Comment](#comment) - Comment on any post.
- [Logout](#logout) - Logout of your account.

## How Install the Project

### Create a token for sending email from your gmail account:

- [Create](https://myaccount.google.com/u/0/apppasswords) - Create a token for sending email from your gmail account. https://myaccount.google.com/u/0/apppasswords
- Copy the token.
- Paste the token in the `token` variable in the `MAIL_PASSWORD` field in `env.sh` file.
- Put your email in the `MAIL_USERNAME` field in `env.sh` file.
- Put the email of the person who will be the blog admin in the `ADMIN_MAIL` field in `env.sh` file.
- Run the following commands to run the app:
  - Clone the project to your machine:
    - `git clone https://github.com/miguelgrinberg/flasky`
  - `cd flasky`
  - `python3 -m venv venv`
  - `. venv/bin/activate`
  - `pip install -r requirements/prod.txt`
  - `source env.sh`
  - `python3 -m flask deploy`
  - `python3 -m flask run`

## Register

- go to http://127.0.0.1:5000/
- register using your admin email and password.

## Confirm

- check you email and confirm the link received.

## Login

- Use your email and password to login.

## Post

- Create any post you need via interface.

## Edit

- Edit your posts via interface.

## Comment

- Comment any post vis interface.

## Logout

- Leave the app and logout.

## PDF Explanation:

- [PDF Explanation](https://github.com/longvision/Flask-Website-Blog/blob/main/cs531_week9_flask_website_blog_project_horiguchi_ricardo_19618.pdf)
