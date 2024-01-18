# Outfield Blog Project

## Project Overview

This repository contains the initial setup for a blog project for Outfield. The project is built using Django and includes a basic `blog` app with a `Post` model. This setup serves as a starting point for a live coding exercise where additional functionalities will be built on top of this model.

For candidates who prefer not to use Django, you are encouraged to prepare a similar setup in a backend framework of your choice, ensuring there is a comparable `Post` model or equivalent.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.10 or higher
- pip (Python package manager)

### Cloning the Repository

To clone the repository and start working on the project, follow these steps:

```bash
# Clone the repository
git clone https://github.com/outfieldtech/technical-assessment.git

# Navigate to the project directory
cd technical-assessment

### Setting Up a Virtual Environment (Optional but Recommended)

It's recommended to use a virtual environment to keep dependencies required by the project separate from your global Python environment.


# Creating a virtual environment
python -m venv venv

# Activating the virtual environment
# On Windows
venv\Scripts\activate
# On MacOS/Linux
source venv/bin/activate
```

# Installing Dependencies

Install the required packages using pip:
```bash
pip install -r requirements.txt
```

# Running the Project
Once the setup is complete, you can run the Django development server:
```bash
python manage.py runserver
```

After running the command, you should see output indicating the server is running, and you can visit http://127.0.0.1:8000/ in your browser to view the application.



# The Blog App

Within this Django project, the blog app is a basic implementation with a Post model. The Post model includes fields such as title, content, author, and date_posted.

During the live coding exercise, you'll be asked to extend the functionality of this blog application, focusing on backend development and API creation.

### For Non-Django Candidates
If you choose not to use Django, please prepare a similar setup with the backend technology you're comfortable with. Ensure that your setup includes a similar basic model to represent blog posts and that you are able to run a local server to demonstrate your work during the live coding exercise.
