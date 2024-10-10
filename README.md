

  <h1 align="center">Blog Post Management</h1>


A Blog application in Django contains all the features of a blog site, such as login/register into the system, adding blog posts with title, description, and image, as well as editing or deleting the blog post.




<br />


## 📃 Description


Creating a Blog in Django offers an interactive UI design where users can see what others are posting. It also has an admin panel through which all blog posts and users can be managed.

<br>
<br>

Sigup Page
<img width="1147" alt="image" src="https://github.com/user-attachments/assets/2976323c-ba6f-4ffe-b3e3-b949e4639b92">

Login Page
<img width="1151" alt="image" src="https://github.com/user-attachments/assets/41a33bbc-eca7-41ce-943c-832c34400e9e">

Blog page
<img width="1157" alt="image" src="https://github.com/user-attachments/assets/e2c658f9-3783-4170-ad93-ad0392e4c5b1">

Blog Details
<img width="1151" alt="image" src="https://github.com/user-attachments/assets/36539c47-e4c3-4634-affd-913fcbf71274">


## Features 

- **Manage Blog**: This feature includes CRUD operations on the blog content, such as adding, editing, and deleting blog posts.
- **Login System**: This feature allows the admin to log in to the system and manage all functionalities.
- **Blog**: This feature is the core functionality, enabling users to create, view, and manage blog posts.
- **Media Management**: This feature handles all the media that is uploaded within the system.
- **Templates**: This feature defines the design of the system, consisting of HTML, CSS, and JavaScript for the front-end.



## Getting Started


### Installation

## Docker

1. Download and install [Docker Community Edition](https://www.docker.com/).

2. Once you've installed Docker Community Edition, click the Docker icon in Launchpad and start the engine.

3. Clone the project repository from GitHub:

   ```bash
   git clone https://github.com/n1ranam/Blog-Post-Management.git
   ```
   
4.Open the project in Visual Studio Code

5.Navigate to the project directory:

   ```bash
   cd blogmanagement
   ```
6. Open terminal and run:

```sh
# Build or rebuild services
docker-compose build

```
```sh
# Create and start containers
docker-compose up

```

7. Open your web browser and visit (http://0.0.0.0:8000/) to access the Django Blog project.

That's it! You now have a running Docker container.

## Locally

Before you begin, ensure you have Python and Django installed on your system. 
To install Django, use pip:

```bash
pip install Django
```

### Project Setup

1. Clone the project repository from GitHub:

   ```bash
   git clone https://github.com/n1ranam/Blog-Post-Management.git
   ```

2. Navigate to the project directory:

   ```bash
   cd blogmanagement
   ```

3. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv blogenv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     \blogenv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source blogenv/bin/activate
     ```

5. Install project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Run the development server:

   ```bash
   python3 manage.py runserver
   ```

7. Open your web browser and visit [http://localhost:8000/](http://localhost:8000/) to access the Django Blog project.

## 🛠 Built With

* HTML
* CSS
* JAVASCRIPT
* PYTHON
* DJANGO
* DATABASE 

The system is fully built using the Django Framework for the back-end, with HTML, CSS, and JavaScript for the front-end. It features a full-fledged user interface with all the required functionalities.


## ⭐️ Show your support 

Give a ⭐️ if you like this project!

