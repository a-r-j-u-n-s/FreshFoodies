# FreshFoodies

## Setup Guide
1. Clone the repo

2. Set up virtual environment
```
py -m venv venv

./venv/Scripts/activate

pip install -r requirements.txt
```

3. (IGNORE THIS STEP FOR NOW) Add FLASK_APP environment variable
```
(Windows) New-Item .flaskenv
(Mac) touch .flaskenv

echo SECRET_KEY=TEST-KEY > .flaskenv
```

3. Run development server

```
flask run
```