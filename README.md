# Newspaper App

A web application developed to share articles among the members of the community. Although users can read articles just by visiting the web application, they are required to sign up before they post an article. Further users can also voice their views by writing them into the comment section below the articles.

## Technologies Used
- Backend: Django
- Database: SQLite
- Virtual Environment: Pipenv
## Setup
1. Clone the repository `git clone https://github.com/aayush-05/Newspaper-App.git`
2. Create the virtual environment by running `pipenv shell`
3. Open command prompt/terminal and run `pip install -r requirements.txt` to install all the dependencies.
4. To create database schema, run 
	* `python manage.py makemigrations`
	* `python manage.py migrate`
5. Finally run the application at `127.0.0.1:8000` using `python manage.py runserver`

## Screenshots
* Homepage
  ![Homepage](/static/screenshots/Homepage.PNG)
* Signup page
  ![Signup page](/static/screenshots/Signuppage.PNG)
* Article Listing page
  ![Listing page](/static/screenshots/Articlelistingpage.PNG)
* Article Details page
  ![Details page](/static/screenshots/Articledetailpage.PNG)
* New Article page
  ![Article page](/static/screenshots/Newarticlepage.PNG)

## Contribution
Feel free to raise Issues or PRs! Fork the repository, set up the project on your local machine and make a PR. 
