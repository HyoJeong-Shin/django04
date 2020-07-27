# six import error

## 해결:  module six가 Django 3.0을 지원하지 않아서 생기는 문제

### Django==2.2 다운그레이드 

    $ pip install django==2.2

### six 설치 https://pypi.org/project/six/#history
    $ pip install six

## static 폴더 없음: settings.py static 부분 주석 처리