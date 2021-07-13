
# Roombling


서비스명 : Roombling
팀명 : 화상회이조 
개발기간 : 2021.07


서비스 개요 : 코로나 19로 인해 최근 비대면 

주요 기능 :

회원가입/로그인 기능

방 생성 및 리스트

화상미팅 기능

게임 기능
a. 라이어 게임(그림판)
b. 카드게임(도둑잡기)

### ✔ Code Style
| FrontEnd   | BackEnd |
| ------ | ---- |
| 1. 폴더명: 첫글자 대문자<br/>→ ex) Feed/Add.vue <br/><br/>2. 파일명: 첫글자 대문자 <br/> → ex) Add.vue <br/><br/>3. 경로명: 소문자 → ex) /add | 1. 클래스명:  첫글자 대문자 + camel case <br/> ex) MainController.java <br/><br/> 2. 함수, 변수: 첫글자 소문자 + camel case <br/> ex) public void setUserName(); |
- ☑ 프론트앤드 규칙
    - 플러그인 : Vuetify 사용
    - css는 import해서 사용 -> style.css에서 공통속성 사용
    - 공통파일 수정 시 팀채널에 공유하기 
    - http파일 import해서 사용하기 
- ☑ 백앤드 명명규칙 
    - [참고](https://velog.io/@aidenshin/Java-%EC%9E%90%EB%B0%94-%EC%BD%94%EB%94%A9-%EA%B7%9C%EC%B9%99-Java-Code-Conventions#%EB%AA%85%EB%AA%85naming-%EA%B7%9C%EC%B9%99)

- if문
    - 한줄 일 때, Block 처리하기
    - else if / else /중괄호는 조건문 바로 옆에 붙이기
    ```java
    if(condition){
     statement;
    } else if(condition2){
     statement2;
    } else{
     statement3;
    }
    ```
-for

단순 반복문은 iterator를 i,j,k,...,z순으로 명명하기
-주석 상대방이 이해할 수 있도록 달기

/**/ 설명 여러줄 필요할 때 코드 위에 작성
// 간단한 주석 코드 옆에 작성

메인화면

![image](https://user-images.githubusercontent.com/65216835/125381674-4b89f580-e3cf-11eb-91a4-4a10633bd938.png)

게임목록

![image](https://user-images.githubusercontent.com/65216835/125382490-b556cf00-e3d0-11eb-8508-58da7fd8ebc3.png)












