# STEM Club Platform:

This project aims to facilitate communication inside our STEM club and help manage it, it will also serve as a way to improve the overall Quality of Life in the club. I initially thought about making it because it just made sense to me that the first club in our highschool to implement a website should be the STEM club, since it is the science and technology club of the school, and who knows maybe this will start a wave of upgrades to the current quality of the clubs system in our highschool. I also decided to make it in order to genuinely learn practical coding, which i have been wanting to learn for a while, and because I believe that this would be a great investment of my free time, especially during this summer.

**Note:** To run the code locally go to the bottom of this page and follow the instructions

## Tools used in this project:
* **Backend:** Django (Python 3)
* **Database:** SQLite (Local Developement) / Migrating to PostgreSQL
* **Environments:** Python Virtual Environments ('venv')
* **Version Control:** Git and GitHub

## Development Logs:

### Day 1:
* Initialized local Git versio control repository
* Configured isolated Python Virtual Environment ('venv') to secure project dependencies
* Provisioned core Django project framework ('Club_Site') structure
* Established public upstream remote repository link to GitHub

### Day 2:


## How to run this project locally:

To replicate this environement setup on a Windows machine (Sorry IOS users!), run GitBash and type the following, line by line, pressing enter after each line:

1. Clone repository:

git clone [https://github.com/RayanM-M/STEM-Club-Platform.git](https://github.com/RayanM-M/STEM-Club-Platform.git)
cd STEM-Club-Platform

2. Rebuild and activate the virtual environment:

python -m venv venv
source venv/Scripts/activate

3. Install core depencies:

pip install django

4. Launch the local engineering server:

python manage.py runserver