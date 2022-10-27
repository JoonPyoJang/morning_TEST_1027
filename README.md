# 10/27 아침퀴즈


### simplejwt로 인증하기
이번 퀴즈는 아래 공식문서를 참고하며 해보세요

https://django-rest-framework-simplejwt.readthedocs.io/en/latest/getting_started.html



1. morningquiz3 라는 폴더를 생성 후 그 안에서 가상환경을 생성/실행해주세요
2. django djangorestframework djangorestframework-simplejwt 설치해주세요
3. morningquiz 라는 이름의 프로젝트를 생성해주세요
4. INSTALLED_APPS 에 rest_framework, rest_framework_simplejwt 등록 후 아래와 같이
DEFAULT_AUTHENTICATION_CLASSES로 rest_framework_simplejwt를 지정해주
세요.
5. python manage.py migrate 로 DB에 migration 해주세요.
6. 아래와 같이 urls.py에 TokenObtainPairView와 TokenRefreshView를 정의해주세요
6. python manage.py createsuperuser 로 admin 계정을 만들어보세요
7. postman으로 5번의 url로 6번에서 만든 admin 계정으로 로그인하는 요청을 보내보세요
8. 아래와 같이 뜬다면 성공입니다.
![image](https://user-images.githubusercontent.com/113072934/198163548-5f4bc8d6-b4cc-4498-999f-04a654fa7139.png)
