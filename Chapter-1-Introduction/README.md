----------------------------------------
# 1. Group information
----------------------------------------
Sahithi Talasila - sxt34220@ucmo.edu -700713422 
Jyothsna Korada - jxk59660@ucmo.edu - 700725966

---------------------------------------
# 2. Github URL
---------------------------------------

https://github.com/Talasilasahithi/Fall-CIS5755.git

----------------------------------------------------------------------------------
# 3. How your group work together (activities, hours used for each activity etc)?
----------------------------------------------------------------------------------

We have discussed regarding basics of Source Code Management with Github and cloud 9 environments in AWS.


We have followed the instructions available in the Lab activity Source Code Management with Github and completed the group lab project.

1. Firstly we have logged into Github and created the repository.
2. Generated the new token and copied the token in a temporary place.
3. New cloud9 environment is created and the README.md file is deleted.
   Time taken for the above steps --30 minutes.
4. In the cloud9 terminal command git config --global credential.helper store is executed.
5. In the cloud9 terminal to clone the repository Github username and token as a password is entered.
    Time taken for the above steps ----- 35 minutes.
6.  New project directory chapter-1- Introduction is created.
7. Created the python environment using the command: python3 -m venv env
8. Environment is activated using the command: source env/bin/activate
9. New python file named ex1.py is created.
10. While keeping the current terminal window for the project,  open a new terminal for git to manage the source code) 
11. git add --all
12. git status
13. git commit -m "first python code"
14. git push
    Time taken for the above steps ------ 40 minutes.
15. In a similar way ex2.flask.py is created and pushed to the git repository.
    Time taken for the above steps ----- 20 minutes.

Total time is taken for the group project -- 2 hours 30 min

------------------------------ 
# 4. Project introduction
------------------------------

In a project, files are stored in a Cloud9 development environment to some common repository outside this EC2 VM. Like, many developers working on the same project, and each of them may want to add or make changes to files and store them outside of their environment into some commonplace. This is where GitHub.com comes in.
In this group lab project, we integrated the Cloud9 environment and Github by using personal token.
Flask is a web application framework written in Python. We have written a simple program where our names are printed successfully.

--------------------------------------------
# 5. Major Steps
--------------------------------------------

1. We signed in to Github and created a new repository.
2. We generated a new token and created a new cloud9 environment.
3. Cloned remote GitHub repository in the environment.
4. Python flask is created
4. Adding files to local Git repository by using git add --all.
5. Commit staged files to local git repository by using the command: python3 -m venv env "first python code"
6. To push the files to the git repository command: git push is used.

-------------------------
## Basic Flask Code
-------------------------
from flask import Flask
app = Flask(__name__)
@app.route('/')
def login():
   return 'Sahithi Talasila and jyothsna korada'
if __name__ == '__main__':
    app.run(host='0.0.0.0', port=8080, debug = True)



