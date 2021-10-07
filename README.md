# MLOPS DVC DEMO
## MLOPS DVC with ML

create env

>conda create -n wineq python==3.7 -y

activate env

>conda activate wineq

create a requirement file

install the requirements file

>pip install -r requirements.txt

create a template python file

download the data from
>https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5

>git init

>dvc init

>dvc add data_given/winequality.csv

>git add .

>git commit -m "first commit"

one line update for readme
>git add . && git commit -m "update Readme.md"

>git remote add origin https://github.com/rvjh/MLOPS_DVC_demo.git

>git branch -M main

>git push -u origin main

