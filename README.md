# ocr 
This is a repository for implementing image/text value transfer through get/post method between Android studio and flask server using python.

### How to run?
+ In cmd..
  1) ngrok 사이트 로그인 후 ngrok zip 파일 받아 압축해제
  2) open cmd 
  3) cd 압축해제된 파일 폴더명
  4) ngrok config add-authtoken 2HnBIcpGUbZ1pdR5RaTNTlBURmO_4npSCfYrDTJu1PQ83YC5w
  5) ngrok http {port 주소}
+ In pycharm..
  1) pull ocr git repository
  2) enter "flask run" in terminal
  3) forwarding 뒤에 있는 서버 주소 코드 ctrl+c
+ In android studio..
  1) TestActivity.kt 109 line에서 val postUrl = "{복사한 서버 주소}/getpost" 중괄호 안에 주소 ctrl+v
  2) run android studio!
