# M7-Smart-Scheduler
This algorithm automate the process of scheduling nurses instead of relying on paper or spreadsheet methods which takes days.


## Run application via docker-compose 

```bash
git clone https://github.com/TakanoriTanifuji/nurse_scheduling.git

docker-compose build 

docker-compose up -d 
```

## Run the application via virtual environment

```bash

python3 -m venv venv

. venv/bin/activate

pip install -r requirements.txt
 
python3 app/app.py
```
## After installing new dependencies

```bash

pip freeze > requirements.txt

```