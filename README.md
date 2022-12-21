# Getting started
## Cloning repo and renaming the folder
```bash
git clone https://github.com/vlnko/mydj.git
mv mydj projectname
```

## Setting up the environment

```bash
cd projectname
python3 -m venv env
. env/bin/activate
pip3 install --upgrade pip
pip3 install -r requirements.txt
```

## Migrating DB and starting Django

```bash
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```