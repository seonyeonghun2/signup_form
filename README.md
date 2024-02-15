# 스마트 IoT 융합 플랫폼 개발자 양성과정 성취도 평가

## 평가정보
- 교과목명 : 화면설계 및 구현
- 평가일시 : 2024.02.15
- 평가시간 : 09:20 ~ 13:20
- 평가유형 : 포트폴리오 (결과물 제작 및 제출, 확인용URL 제출)
  
## 샘플 데이터 클론하기
git clone https://github.com/seonyeonghun2/signup_form.git [새폴더명]

## json-server 모듈 설치하기
위 단계에서 샘플데이터 클론 후 터미널을 이용해 복제한 [새폴더명] 내부에 있는 server로 이동하고 이어서 npm install 명령을 실행하면, node_modules/ 라는 폴더가 생성됩니다.

터미널을 이용해 npm run server 명령을 입력하면, json-server 모듈이 4434 포트를 이용해 사용자 정보 샘플 데이터를 제공하는데, 이때 End-Point는 http://localhost:4434/users 이므로, AJAX 통신할때 이곳으로 GET, POST
등의 요청을 보내면 되겠습니다.

json-server 모듈은 GET 요청이 오면 db.json에 정의된 사용자 정보를 JSON 형태로 응답하고, POST 요청이 오면
db.json에 사용자 정보를 추가하여 업데이트된 사용자 정보를 JSON 형태로 응답합니다.

세부 사용방법은 json-server 모듈에 대해서 검색하거나 관련 블로그등을 찾아서 확인하시기 바랍니다.

