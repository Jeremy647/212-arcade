# 212-arcade
 Workshop content

to get this project set up you will first need to install a virtual environment,
To do this open cmd prompt and follow instructions below.

--------- FIRST TIME SET UP -------

cd *DRAG PROJECT FOLDER INTO TERMINAL*

---mac
python3 -m venv env
---windows
py -m venv env

pip install flask

set FLASK_APP=run.py
set FLASK_DEBUG=1
py -m flask run

--------- ONCE ITS BEEN SET UP ------

 cd *DRAG PROJECT FOLDER INTO TERMINAL*
 env\Scripts\activate.bat
 set FLASK_APP=run.py
 set FLASK_DEBUG=1
 py -m flask run
