# dreamrealm
todo is Django project creates a simple to do list 

## Table of Contents

- [Installation](#installation)


## Installation

### Prerequisites

1. **Python**: Ensure that you have Python installed on your machine. [Download Python](https://www.python.org/downloads/).
2. **Git**: Make sure you have Git installed. [Download Git](https://git-scm.com/downloads).
3. **PyCharm (Optional but recommended)**: [Install PyCharm](https://www.jetbrains.com/help/pycharm/installation-guide.html).

### Download and Setup
#### Using Venv(Optional)
1. **Clone the Repository:**
   ```In bash
   git clone https://github.com/EmmanuelMasango/dreamrealm.git

   cd dreamrealm
   virtualenv venv

   For Windows: .\venv\Scripts\activate
   For Linux/Unix or Gitbash: source venv/bin/activate
   
   pip install -r requirements.txt

2. **Apply Database Migrations:**
   ```In bash
   python manage.py migrate
   python manage.py makemigrations

3. **Run the devlopment server:**
   ```In bash
   python manage.py runserver

Open your web browser and go to http://localhost:8000/ to view the project.
