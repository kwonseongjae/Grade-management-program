# 성적관리프로그램 with Python




students.txt파일로부터 데이터를 읽어서 성적 목록을 만들어 관리하는 성적 관리 프로그램


<br/>

## 파일 구성

학번, 이름, 중간고사 성적, 기말고사 성적


<br/>

## 설명
- LINUX
$ python project.py students.txt 
- WINDOW
C:\> python project.py students.txt
- 파일명을 입력하지 않을 경우, default로 “students.txt”로부터 데이터를 읽는다.
- 파일명이 입력될 경우, 입력된 파일로부터 데이터를 읽는다.
- 파일명에는 공백이 없다고 가정한다. (즉, 공백이 있는 파일명의 입력에 대해서는
고려하지 않는다
- 각 줄은 각 학생의 학번, 이름, 중간고사 점수, 기말고사 점수로 구성되어 있으며 각항목 사이는 tab(\t)으로 구분된다.
- 학생과 학생 사이는 줄 바꿈 문자(\n)으로 구분된다.
Ex. [Student number][\t][Name][\t][Midterm][\t][Final][\n]
- 프로그램을 실행시키면 텍스트 파일로부터 데이터를 읽어 목록을 리스트(list) 자료형 또는 딕셔너리(dict) 자료형을 사용하여 저장하고, 전체 목록을 평균 점수를 기준으로 내림차순으로 정렬한다.
- 평균(Average)항목은 중간고사 점수와 기말고사 점수의 평균을 계산하여 저장한다
- 사용자는 7개의 명령어(show, search, changescore, searchgrade, add, remove, quit)를 사용할 수 있으며, 명령어를 입력하였을 때만 기능이 실행된다. 이 명령어는 사용자가 명령어 입력 시, 대소문자를 구분하지 않고 동일한 명령어의 기능을 수행하도록 작성한다. 예를 들면, show, SHOW, Show, shoW 는 동일한 동작을 수행한다

## 기능
1. 출력
- show, search, SearchGrade 는 조건에 맞는 데이터를 출력해주는 명령어
2. 수정
- add, remove,  changeGrade 는 데이터를 수정해주는 명령어
3. 종료
- quit 은 프로그램을 종료하는 명령어
- 종료하기 전, 파일 저장 여부를 물은 뒤 새로운 파일로 저장


<br/><br/>
