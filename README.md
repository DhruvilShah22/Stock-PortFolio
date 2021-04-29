Stock Portfolio
Created a basic Stock-Portfolio Website using Django. For now its without a login/signup system, but in an version upgrade will add the authentication.
Django has inbuilt authentication and database systems.

To run this on your system, follow the following steps:
Step (1) -> Download / Clone this repository on your system.
Step (2.1) -> If you have downloaded the above folder in zip format :
Create a folder called djangostock in your C drive.
Copy all the contents of the zip folder in this new one
Step (2.2) -> If you have cloned the above folder on some other folder on your desktop/other location :
Create a folder called djangostock in your C drive.
Copy all the contents of your cloned folder in this new one
Step (3) -> Open your cmd or git-bash terminal and run pwd. Ususally the default location would be :
/c/users/your_current-loggedin_username
Step (4) -> Run the cd .. command twice to exit the current directory and come to C Drive. Then write cd djangostock in your terminal. If you have followed the above steps thoroughly, your terminal will display :
/c/djangostock
Step (5) -> Now we have to install virtual enviroment in this directory to run our django project. If you have Pip installed previously, write the following command:
pip install virtualenv
Step (6) -> Now we have to install django in your virtual enviroment. Firstly, write the following command to go into your virtual enviroment directory:
cd venv
Then write in your terminal:
pip install django
Step (7) -> Now we have everything installed. To run the virtual enviroment on your local host, come out of the venv folder and into the stocks folder and write the following command:
python manage.py runserver
Step (8) -> If the above doesn't work, find the manger.py python file in your folder and run from that directory.
Step (9) -> Go to the browser you use normally and type localhost:8000. Yes it runs on that port.
Step (10) -> To exit / close the localhost / server, go to your termainal and press CTRL + C.
If you encounter or face any issues while installation, please refer to it on Youtube or you can also refer this another channel on Youtube. Irresepective of installation issues, you can refer Codemy.com (youtube channel) for other Django tutorials.





