# Python Library Research

Python으로 Library를 만들기 위한 정략적인 체계 사전 조사

***
## 윤성 조사 내용 (진행중, 조사 방향 맞는지 확인 필요)

자주 사용되는 로직을 재사용하기 편리하도록 정리한 일련의 코드 집합 즉, 라이브러리를 만들기 위해 모듈과 패키지 만드는 방법을 알아야 한다. 변수, 함수, 클래스 등을 모아 놓은 스크립트 파일인 모듈을 여러 개로 묶어 패키지로 만들고, 이를 이용하여 라이브러리를 구성하도록 한다.<br><br>

## Python Module
- 모든 모듈은 .py 확장자 파일로 관리된다.
- 모듈 속에 함수, 클래스, 변수가 포함될 수 있다.
- 여러 모듈을 패키지로 묶을 수 있다.
- 모듈은 ‘현재 폴더 - Python PATH (환경변수) - 파이썬 설치 경로’ 순으로 검색하여 사용할 수 있다.<br><br>

## Python PATH 환경변수 확인 방법
<img width="860" alt="sys path" src="https://user-images.githubusercontent.com/52089296/82018664-b99a3600-96c0-11ea-9317-6d6d0304c312.png"><br><br>

## Module을 불러와 사용하는 방법
- import 모듈명
- import 모듈명1, 모듈명2, 모듈명3
- import 모듈명 as 모듈  // 함수 사용시 모듈.함수명(파라미터)
- from 모듈명 import 함수명  // 함수 사용시 함수명(파라미터)
- from 모듈명 import 함수명 as 함수
- from 모듈명 import *  // 모듈 내 모든 내용 포함<br><br>

<img width="856" alt="import" src="https://user-images.githubusercontent.com/52089296/82019440-32e65880-96c2-11ea-8a4a-93d68480b7a5.png"><br><br>

## Python Library
- 파이썬 라이브러리에는 일상적인 프로그래밍에서 발생하는 많은 문제에 대한 표준적인 해결책을 제공하는 모듈 뿐만 아니라, 파일 I/O와 같은 시스템 기능을 액세스하는 (C로 작성된) 내장 모듈들이 포함된다. 이 모듈들이 없으면 파이썬 프로그래머가 액세스할 방법은 없으며, 이 모듈 중 일부는 플랫폼 관련 사항을 플랫폼 중립적인 API로 추상화시킴으로써 프로그램의 이식성을 권장하고 개선하도록 명시적으로 설계되었다.

- 윈도우용 파이썬 프로그램은 일반적으로 전체 표준 라이브러리를 포함하며 종종 추가 구성 요소도 포함한다. 유닉스와 같은 운영체제의 경우 파이썬이 일반적으로 패키지 모음으로 제공되기 때문에 운영체제와 함께 제공되는 패키지 도구를 사용하여 선택적 구성 요소 일부 또는 전체를 구해야 될 수도 있다.

- 표준 라이브러리 외에도 수천가지 컴포넌트(개별 프로그램과 모듈부터 패키지 및 전체 응용 프로그램 개발 프레임워크)가 늘어나도 있는데 파이썬 패키지 색인에서 이를 얻을 수 있다.<br><br>

**Documentation TBA**

## Reference

1. 모듈과 라이브러리 : https://blue-shadow.tistory.com/101
2. 파이썬 모듈 사용법 & 모듈 만들기 : https://withcoding.com/83
3. 모듈과 패키지 만들기 : https://dojang.io/mod/page/view.php?id=2447
4. Python 표준 라이브러리 : https://docs.python.org/ko/3/library/index.html
