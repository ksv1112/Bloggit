# Bloggit
Bloggit is a Django-based blogging application that provides a platform for users to create, publish, and manage blog posts. It includes features such as user authentication, CRUD operations for blog posts, user profile modifications and pagination for better navigation.

## Description

Bloggit is a Dockerized Django-based blogging application that provides a platform for users to create, publish, and manage blog posts. It includes features such as user authentication, CRUD operations for blog posts, user profile modifications, pagination for better navigation, and email functionality for password reset.


## Features

- ****Sign In and Sign Up****:
  
  Users can register new accounts and log in securely to access the blogging platform.
  
- ****Authentication and Authorization****:
  
  Bloggit ensures that only authorized users can perform actions such as creating, editing, and deleting blog posts.
  
- ****CRUD Operations****:
  
  Users can perform CRUD operations (Create, Read, Update, Delete) on blog posts, allowing them to write, publish, edit, and remove content as needed.

- ****User Profile Modifications****:
  
  Registered users can modify their user profiles, such as updating their display names, avatars, and bio information.
  
- ****Pagination****:
  
  Bloggit implements pagination to divide long lists of blog posts into multiple pages, enhancing the user experience and making it easier to navigate through the content.

- ****Email for Password Reset****:
  
  Users can request a password reset via email if they forget their passwords, providing a convenient way to regain access to their accounts.

## Technologies Used

- Django
- Bootstrap
- SQLite (default Django database)

## Installation

### Prerequisites

- Python 3.8 or higher

### Steps

1. **Clone the Repository**

```bash
   git clone https://github.com/ksv1112/bloggit.git
   cd bloggit
````

2.  **Create a Virtual Environment**

```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
````

3.  **Install Dependencies**

```bash
   pip install -r requirements.txt
````

4.  **Setup the Database**

```bash
   python manage.py migrate
````

5. **Run the Server**

```bash
   python manage.py runserver
````

6. **Access the Application**

Open your browser and go to (http://127.0.0.1:8000)[http://127.0.0.1:8000]

<br>


## Pulling the Docker Image

### Install Docker
Make sure Docker is installed on the other local machine. You can download and install Docker Desktop from the official Docker website.

<br>

### Pull Image
Open a terminal or command prompt on the other local machine and use the following command to pull the Docker image from Docker Hub:

```bash
docker pull krutarth1112/django_project-web:latest
```
Replace `<your_dockerhub_username>` with your Docker Hub username.

<br>

### Verify Image
You can verify that the image has been successfully pulled by listing all Docker images:

```bash
docker images
```
You should see the django_todo_app image listed among other images.

<br>

### Run Docker Container
Start a Docker container from the pulled image:

```bash
docker run --name django_project-web_remote -d -p 8000:8000 krutarth1112/django_project-web:latest
```
This command starts a Docker container named django_todo_app_remote from the pulled image and runs your Django application inside it.

<br>

### Access Application

Open a web browser on the other local machine and navigate to [http://127.0.0.1:8000](http://127.0.0.1:8000) to access your Django application running inside the Docker container.

<br>

## Main Functionalities

### Sign In and Sign Up

Users can register new accounts and log in securely to access the blogging platform.

### Authentication and Authorization

Bloggit ensures that only authorized users can perform actions such as creating, editing, and deleting blog posts.

### CRUD Operations

Users can perform CRUD operations (Create, Read, Update, Delete) on blog posts, allowing them to write, publish, edit, and remove content as needed.

### User Profile Modifications

Registered users can modify their user profiles, such as updating their display names, avatars, and bio information.

### Pagination

Bloggit implements pagination to divide long lists of blog posts into multiple pages, enhancing the user experience and making it easier to navigate through the content.

### Email for Password Reset

Users can request a password reset via email if they forget their passwords, providing a convenient way to regain access to their accounts.

<br>

## Contributing

1. **Fork the repository**

2. **Create your feature branch**

    ```bash
    git checkout -b feature/AmazingFeature
    ```

3. **Commit your changes**

    ```bash
    git commit -m 'Add some AmazingFeature'
    ```

4. **Push to the branch**

    ```bash
    git push origin feature/AmazingFeature
    ```

5. **Open a Pull Request**

<br>

## Acknowledgements

This project is built using the following technologies:

- [Bootstrap](https://getbootstrap.com/)
- [Django](https://www.djangoproject.com/)
- [Docker](https://www.docker.com/)

<br> 

## Contributor 

- [Krutarth Vora](https://github.com/ksv1112)

<br>
