# Django
Django-project

# 1. 클라우드 서비스란?
서비스를 운영하기 위해서는 서버가 필요하다. 그러나 서버를 직접 사기에는 너무 고가이고, 또 배송이 온다고 해서 끝이 아니라 설치를 하는 것도 매우 큰 리소스가 드는 작업! 그래서 이 서버를 빌려서 사용한다. 빌리는 것을 클라우드 서비스라 하고, 이 서비스는 크게 3가지로 나눌 수 있다.

1. **SaaS(Software as a Service)**<br>
가장 사용자 단에 친밀한 서비스이며 네트워크를 통해 애플리케이션 기능을 이용할 수 있는 서비스
2. PaaS(Platform as a Service)<br>
윈도우와 리눅스 같은 운영체제를 제공하고 개발 가능한 플랫폼도 함께 제공되는 클라우드 서비스
3. IaaS(infrastructure as a Service)<br>
인프라를 제공하는 클라우드 서비스 (기업에서 특히 많이 쓰임) AWS!! 

# 2. 구름IDE
설치가 필요없는 클라우드 통합 개발환경(IDE)<br><br>
구름을 사용하는 3가지 이유
1. OS Version, Python Version, Django Version별 에러를 잡는데 시간이 많이 소요된다. 또한 '개발은 배포 환경과 동일하게!'라는 말을 잊지말자. 우리의 리소스를 아껴줄 것이다.
2. 집에 서버와 환경을 구축하는 것은 비용(시간, 금전, 기회 비용)이 상대적으로 크다.
3. 배포를 명령어 한 번으로 진행할 수 있다. 또 구름에서도 서비스를 런칭할 수 있다.

# 3. Django 프로젝트 basic
### https://www.notion.so/MBIT-My-Best-IT-personalities-3d9128d972054b498b98365f1df4e656
### 1. venv 모듈을 통해 가상 환경 생성
- [root@goorm:/workspace/MBIT#] python -m venv [가상환경이름]
- [root@goorm:/workspace/MBIT#] python -m venv venv

### 2. 가상환경 실행
- source venv/bin/activate
- 가상환경이 잘 실행되고 있는지 확인하려면 pip list 명령어로
- python 모듈의 리스트를 보자 글로벌 환경일 때와 가상 환경일 떄의 결과가 다르다.

### 3. django 패키지 설치
- pip install django
- successfully installed 메시지가 뜨면 성공적
- pip list 명령어로 확인해보자.

### django 프로젝트 생성
- django-admin startproject [프로젝트 명] [경로]
- django-admin startproject MBIT . (현재경로)
- manage.py파일 생성

# 4. 
