# ajiraSpaceX

# SETUP

python -m pip install virtualenv<br />
virtualenv venv<br />

##### if on windows

venv\Scripts\activate.bat<br />
python -m pip install -r requirements.txt<br />

##### if on linux

source venv/bin/activate <br />
python -m pip install -r requirements.txt<br />

## UNIT TESTS

python -m unittest SpaceX.unit_test<br />

## e2e testing

### 1st terminal

python SpaceX/app.py<br />

### 2nd terminal

python SpaceX/e2e.py<br />

# RUN

python SpaceX/app.py<br />
