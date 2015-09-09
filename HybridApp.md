# Hybrid Application
- OS위에서 작동하는 웹브라우저 위에서 동작
- 표준을 지킨다. -> HTML5
- HTML5 API를 사용하여 OS가 제공하는 API를 대체하여 Application을 대체 -> **브라우저가 OS역할을 함** / One Source Multi Platform
- 문제가생김! MS, Google, Apple같은 회사들은 싫어함 :
   - 그런데 Apple은 돈을 더 벌고있다.
   - MS는 브라우러시장을 잃어버림 / Chrome, FireFox
- One Source Multi Platform
   - 1.좋아보이나 문제가 있다. 현제는 키켓이후로 성늠문제가 개선됨
      - **안드로이드는 느리다..**
      - 그럼에도 불구하고 컨텐츠기반의 앱은 효과가 있다.(어차피 서버에서 가져오니까)
      - 키켓(웹브라우저 / 그래픽 속도문제를 거의 해결) -> 롤리팝 -> 마쉬멜로우
   - 2.HTML5 1차표준이 완료
   - boom! Hybrid앱

---
- **Mobile Web** : 웹서버에서 -> 모바일 / 웹 각각의 레이아웃으로
- **Web App** : 1. 모바일에서 앱 껍데기에다가 웹을 넣어서 / 2. 웹상에서 애플리케이션형태로
   - OS상관없이
- 웹은 앱보다 화면의 장면전환이 부자연스럽다. 항상 웹서버에서 가져와야하기 때문에.
   - Ajax : 화면은 단말에 있고, 데이터만 서버에서 가져오기
   - 컨텐츠기반의 서비스는 모두 서버에서 가져오기도한다.
- **Hybrid App** : 공지사항과 같은 알림이 필요한경우
   - OS에 따른 push기능이 다름.. : 가장 근본적인 **문제 각각의 OS별로 따로만들어야한다**, 그럼에도 불구하고 만든다. 최소화하면된다.
   - 자바스크립트에서 Native App의 함수호출
   - HTML5가 더 파워풀해지면서 이 구성방식이 바뀌게 된다.

#### 하이브리드, 네이티브, 웹 비교 아키텍처
![하이브리드, 네이티브, 웹 비교](http://drive.google.com/uc?export=view&id=0B0CgSzgDruzieUEwblJjczJVOUk)
#### 하이브리드 아키텍처
![하이브리드 아키텍처](http://drive.google.com/uc?export=view&id=0B0CgSzgDruziT3pILVNqbllUWkk)


---

## 개발환경( Native App + Web)
- iOS앱 : Xcode
- Android앱 : 안드로이드 스튜디오
- 웹 : 이클립스

1. 웹서버 & 웹페이지 제작
2. Android App에서 WebView에서 url지정
