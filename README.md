# Unittest-Github-Actions-Anton-Assignment
Unit test
Tried unit testing using Github Actions. seems it is not working because there are issues with installing dependencies.
We created requirements.txt file in terminal by using:
pip freeze > requirements.txt
Then it will creates our file with name requirements.txtwith all dependencies.
Then Github actions uses this requirements.txt to install them in the virtual server or container which Actions is going to create.
But i am facing errors with installing depenencies. It means i have issues with either my yaml file or requiremnts file, because unittest is working, when i run the program in cmd/terminal 
with: 
python3 tests.py

It is working.
