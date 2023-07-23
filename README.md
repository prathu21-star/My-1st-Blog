# My 1st Blog




![Screenshot 2023-07-23 155846](https://github.com/prathu21-star/My-1st-Blog/assets/91003319/e21adf29-ac64-4e1d-ba41-3f98fcd6e41e)

![image](https://github.com/prathu21-star/My-1st-Blog/assets/91003319/78370a2b-5964-451a-bf5e-847fe5d96e5c)


## Description

"My 1st Blog" is a simple and beginner-friendly blog web application built using Django framework. It allows users to create, edit, and publish blog posts with optional images.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- User-friendly interface for creating, editing, and publishing blog posts.
- Image upload support for blog posts.
- Responsive design for optimal viewing on various devices.
- Admin dashboard for managing blog posts and user accounts.
- Supports Markdown for formatting blog post content.

## Demo

A live demo of "My 1st Blog" can be found at http://127.0.0.1:8000/


## Installation

To run "My 1st Blog" locally on your machine, follow these steps:

1. Clone the repository:

git clone https://github.com/prathu21-star/My-1st-Blog.git
cd My-1st-Blog


2. Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate # for Windows: venv\Scripts\activate


3. Install the required dependencies:

pip install -r requirements.txt


4. Apply the database migrations:

python manage.py migrate


5. Create a superuser to access the admin dashboard:

python manage.py createsuperuser


6. Run the development server:

python manage.py runserver


7. Open your web browser and navigate to `http://127.0.0.1:8000` to access the blog.

## Usage


- To edit an existing blog post, click on the "Edit" button below the post content on the post detail page.
- Make the desired changes to the title, content, or image and click on the "Update" button to save the changes.

- To delete a blog post, click on the "Delete" button below the post content on the post detail page.

- Users can view all published blog posts on the homepage in reverse chronological order.

- The admin dashboard can be accessed by navigating to `http://127.0.0.1:8000/admin` and logging in with the superuser credentials created during installation. The admin dashboard allows you to manage blog posts and user accounts.

## Contributing

Contributions to this project are welcome and encouraged! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request. When contributing to this repository, please follow the existing code style and conventions.

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

```
git checkout -b feature/my-feature
```

3. Make your changes and commit them:

```
git commit -m "Add my feature"
```

4. Push your changes to your forked repository:

```
git push origin feature/my-feature
```

5. Open a pull request on the main repository.


## Thank you for using "My 1st Blog"! Happy blogging!
