Hi,

This is a Library Management project made with Django(backend) and React JS(very-basic,frontend).

How to run:-

1. Clone the project in your system and open in VScode
2. Start the terminal in VScode for the project, it should automatically run the virtual environment if it doesn't type- source libraryvenv/bin/activate
3. Open another terminal inside the VS code so that you have two terminals with virtual environment running.
4. On one terminal type cd frontend
5.Now start the servers-
type- npm start - for running the frontend server
type-python manage.py runserver- for running the backend server


After running the server, you can easily login and sign up on the website. You can enter the type of the user(either 'admin' or 'student'(it can't be any other)) while signing up to initialize the user type.
After signingup, an admin can login and create, edit, delete and view books in the system whereas a student won't be able to perform any other task apart from viewing the books.


Create Method is using POST request
View Method is using GET request
Edit Method is using PUT request
Delete Method is using DELETE request


