# BHC

## How to setup project
```
git clone https://github.com/DorianSzlachcic/BHC.git`
cd BHC/
git submodule init
git submodule update
```

### To run django project
```
cd BHC-django/
python -m venv .env
source .env/bin/activate
pip install -r requirements.txt
python manage.py collectstatic
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

### To run react project
```
cd BHC-react/
npm install
npm run dev
```
