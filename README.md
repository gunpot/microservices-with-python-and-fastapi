# microservices-with-python-and-fastapi
This is a new repository for Python Devops Workshop

1. Create a Python Virtual Environment 'python3 -m venv ~/.venv' or 'virtualenv ~/.venv'

2. To use the Vitual Environment over and over again, creating lots of shells, we are going to source the virtual environment inside of my bash configuration file 'vim ~/.bashrc' 

3. add # Sourcing Python vitual environment 'source ~/.venv/bin/activate' esc ':wq' enter

4. Create empty files:
# to create files
'touch requirements.txt' 
'touch Makefile' 
'touch Dockerfile' 
# to create directory if logic is involved in the code
'mkdir mylib'
'touch mylib/logic.py'
# this file tells python it can import this directory
'touch mylib/__init__.py' 
# microservice build out
'touch main.py'

5. Populate 'Makefile'

6. To see what files I have changed:  'git status'  To update files:  'git add *'


