# Meteor Korean Doc. project

Meteor 0.6.5.1 한글 번역

## 미리 보기
	cd docs_kr/
	meteor

## 번역 대상 경로

docs_kr/client

## api.html

api.html_split~ 을 ID 별로 분리

### api 분리

sh merge.sh

### api 병합

sh split.sh

### api 작업 방법

api.html_split~ 아래의 api?? 파일들을 수정 후 merge.sh 로 확인

단 api.html 를 병합한 파일은 올리지 않는다.

## concepts.html

api.html 과 동일

## Deploy

meteor krdocs.meteor.com