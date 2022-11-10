# django_zero_to_instagram

장고를 이용한 인스타그램 클론 코딩입니다.

강의 유튜브를 기반으로 합니다.

유튜브 : https://youtu.be/M8UPyeF5DfM  
관련 blog : https://cholol.tistory.com/547

---

## 실행

python 3.7 이상 버전 설치 후

```
# 가상환경 생성 
python -m venv venv

# 가상환경 실행
source ./venv/Scripts/activate

# 필요 package 설치
pip install -r requirements.txt

# migrate 명령어로 DB 생성
python manage.py makemigrations
python manage.py migrate

# 서버 실행
python manage.py runserver

# 브라우져로 접속
http://127.0.0.1:8000/main/
```
