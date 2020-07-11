#Covid 19 Dashboard
 A simple Dashboard built on Python Jupyter Notebook which pre-process the data from the 
https://api.covid19india.org/data.json
https://api.covid19india.org/state_district_wise.json

This app is deployed on a Heroku web server whose address is

https://covid19data-analysis.herokuapp.com/

This app show Daily statistics on Number of cases confirmed and active and Death.
It also show top five States and districts with maximum number of cases in India.

Through graphical representation it covers various trend in number of increasing cases in India. 




# voila-simple-app

A simple web app build with Volia, a Python package to convert Jupyter notebooks into standalone web apps

## To replicate this deployment

### Create a new GitHub repo and connect the remote repo to the local folder

Create a new repo on GitHub.com, then link it to local folder

```text
mkdir voila-simple-app
cd voila-simple-app
git init
git remote add origin https://github.com/<UserName>/<RepoName>.git
git pull origin master
```

### Set up Python virtual env and install Jupyter and Voila

```text
python -m venv venv
source venv/bin/activate
pip install voila jupyter matplotlib numpy
```

### Create the Jupyter notebook that will be deployed with Voila

### Run Voila Locally

```text
voila app.ipynb
```

```[Ctrl-c]``` to exit

