# 한국수자원공사 댐 시설물 손상검출 SW 개발

## waterinfo instance segmentation GUI

### Installation
* python 3.8.8
* pytorch 1.7.1
* trochvision 0.8.2
* Detectron 2

## 사용 방법
1. detectron 2 가 설치되어 있는 가상환경 생성
2. 제공된 파일이 저장되어 있는 경로로 이동
3. python main.py 파일을 실행
4. 'LOAD'버튼을 눌러 inference 하고자 하는 파일 경로 선택
5. 'INFERENCE' 버튼을 눌러 경로 내의 모든 이미지 파일을 inference
6. 앞서 사용자가 지정한 파일 내에서 inference 파일이 생성됨
7. inference 된 이미지와 엑셀파일은 6번에서 생성된 파일 안에 저장됨
