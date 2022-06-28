# car-price-prediction


#create virtual environment
1.open anaconda prompt
https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html
2.conda create -n carprediction python=3.7
3.activate carprediction
4.cd path of the csv files folder
5.dir    [to see directories]
6.jupyter notebook   or spyder
7.complete model by checking above code upto pickle file
8.creating requirements.txt by following command
pip freeze > requirements.txt

9.to see env's
conda info --envs

10.open spyder for same env and create app.py , create index files for FrontEnd & check code in Repository

11. FINALLY open AnaconaPrompt run  the following command
cd path of folder
python app.py


#DEPLOY IN GOOGLE CLOUD

install sdk for gcloud
1.rename app.py to main.py
2.create app.yaml & write below code
runtime: python37
3.open gcloud cmd
gcloud init
new config:write config name
choose A/C
choose proj.ID
4.deploy code
gcloud app deploy app.yaml --project projectId
5.choose region
6.gcloud app browse
7.FINALLY AppEngine---Settings---DisableApplication


#Deplpoy in Heroku
1.create runtime txt file
python-3.7.11
2.create Procfile   {#REMEMBER P shoudld be CAPITAL}
web: gunicorn app:app
create new app
connect to GitHub and Deploy



#GITHUB
install GitBase --- Git-scm
open CMD
1.clone
git clone paste github link
2.intialize git
git init
3.add file to the local respiratory
git add .
4.checking status of files added to which folder
git status
5.commit the file
git commit -m 'your message'
6.setting origin
git remote add origin 'fit repository link'
7.checking the code origin
git remote -v
8.push code to the repository
git push -u origin master
or
git push -f origin master
9.changing branch
git checkout master
10.merge
git merge newFeature
11.History
git log
12.help
git log --help
13.reset
git reset --hard origin/master


