Local Setup process:

# Process 1 ---->>

## Step1:

clone the repo
<br>
cd Online-Market

## step2:

Activate the envoirnment:

Try any of these below - 
<br>
i)  source xenon\Scripts\activate
<br>
ii)  .xenon\Scripts\activated
<br>
iii)  .xenon\Scripts\python
<br>

step3:
python manage.py runserver


# Process 2 ---->>

## Step1:

clone the repo

## step2:

create a virtual envoirnment in python:
NOTE: if your envoirnment not creating by below code it means you dont have venv , so intall that - 
<br>
create venv - python -m venv myenv

## step3:

Activate the envoirnment:
Try any of these below - 
<br>
i)  .myenv\Scripts\activated
<br>
ii)  .myenv\Scripts\python
<br>
iii)  source myenv\Scripts\activate

## step4:

cd Online-Fish-Market-Website
<br>
pip install -r requirements.txt
<br>
python manage.py runserver