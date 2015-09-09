## Yeoman
- http://webframeworks.kr/getstarted/yeoman/
- 빠른 프로토타이핑을 위한 웹앱 자동화 툴
- node.js 기반으로 주요 기능으로는 아래와 같습니다.
   - 스케폴딩으로 인한 빠른 프로젝트 템플릿 구성
   - LiveReload를 이용한 라이브 코딩
   - 이미지 optimization
   - Compass, CoffeeScript 자동 컴파일링
   - JS 라이브러리의 의존성 체크 및 업데이트 관리
   - 정적검사 및 유닛 테스트
   - JS/CSS merge 및 minimize 그리고 dist 배포

- 기본적으로 git, node.js, npm이설치

# Yo
- 새로운 개발환경을 스케폴딩, 개발환경설정을 책임
```
$> npm install -g yo  //설치치
```
ex) Angular
```
$> npm install -g generator-angular
$> mkdir angularApp
$> cd angularApp
$> yo angular angularApp
```

# Bower
- 프론트앤드 웹패키지 매니저, 스크립트 라이브러리의 버전관리. Maven과유사
- bower.json : 해당프로젝트의 전반적인 정보와 프로젝트 의존하고있는 라이브러리 목록등을 작성
- .bowerrc : 내려받은 라이브러리들이 위치하게될될디렉터리 경로를 설정정
```
$> npm install -g bower  //설치
```

```
$> bower search <dep> - search for a dependency in the Bower registry
$> bower install <dep>..<depN> - install one or more dependencies
$> bower list - list out the dependencies you have installed for a project
$> bower update <dep> - update a dependency to the latest version available
```

# Grunt
- 자바스크립트 테스트러너 빌드, 미리보기, 단위테스트를 담당. Ant와 유사
- Gruntfile.js : 환경파일, ant와 같은 수행 Task 정의
- package.json : Node.js위에 구동되므로 package.json에 Grunt contributor 라이브러리 정의
```
$> npm install -g grunt-cli  //설치
```

```
$> grunt test  - 테스트하기. run the unit tests for an app  
$> grunt server - 브라우져에서 보기. 변경사항 실시간 반영됨. preview an app you have generated (with Livereload)
$> grunt - 배포본 빌드하기.  build an optimized, production-ready version of your app  (warning 무시 옵션 --force 사용가능)

```
