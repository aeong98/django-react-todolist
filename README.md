## React-Django-Restapi

***django rest framework, react로 구현된 to-do-list 앱입니다.***
rest api 자동 명세화를 위해 `swagger`를 사용하였습니다.

## 시작하는법

### 01. django 설치
1. `python -m venv myvenv` (가상환경 설치)
2. `source myvenv/Scripts/activate`
3. `pip install django`

### 02. dependencies 설치
1. `pip install -r requirements.txt`
2. `cd frontend`
3. `npm i`

### 03. django migration
1. `python manage.py makemigrations`
2. `python manage.py migrate`


### 04. 서버 실행시키는 법
1. Backend : `python manage.py runserver`
2. Frontend : `npm start` (frontend 폴더에서)

### 05. server port 정보
```
1. localhost:8000           // Django
2. localhost:8000/swagger   // Django swagger
3. localhost:3000           //React 
```
