# 100 Days of Python Portofolio Website
Hello there, welcome to my portofolio website

My name is Matthew Adrianus Mulyono, and this is my portofolio website

This website contains information about my finished projects while doing the 100 Days of Python course

Since there are like around 80 projects, I only included the projects that I liked to be shown here

The purpose of this website is to showcase my projects and improve my backend building skills using flask framework

Sorry for the 'not exactly cool' web design. I'm not experienced enough in frontend 😅

### Steps of Deployment
1. Clone this repository
2. Set up a virtual environment by typing 'python -m venv env' in the command line
3. Set your interpreter path to the virtual environment path
4. Download all the dependencies (modules) by typing 'python -m pip install -r requirements.txt'
5. Before starting the application, you need to create the database locally (using sqlite) in the python script (and comment them afterwards)
6. You also need to add new user (which will be you), so that you can log in and insert your projects
- The code for step 5-6 is:
```python 
 db.create_all()
 admin = User(name=ADMIN_NAME)
 db.session.add(admin)
 db.session.commit()
```
7. Lastly, don't forget to setup SECRET_KEY, ADMIN_NAME, ADMIN (username), and PASSWORD in .env file so that the program can start
8. Start the application by running the code, and then go to http://127.0.0.1:5000/
