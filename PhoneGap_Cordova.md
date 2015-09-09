## PhoneGap - Cordova

- 각각의 OS별 껍데기를 만들어 놓아서 제공해준다. 웹페이지나 JS만 만들면 됨.
- 라이트하게 개발하려면 위에 처럼 하는 경우도 많이 있다.
- 대표적으로 많이 쓰는 기능을 만들어 놓았다.(push등. )

http://147.46.109.80:9090/board/board-read.do?boardId=general&boardNo=143945046486300&command=READ&t=1441780313574

! node.js를 미리설치 !
```
$> npm install -g phonegap
$> npm install -g cordova

$> phonegap create my-app  
$> phonegap install android (cd my-app에서)

$> cordova create my-app
$> cordova platform add android  (cd my-app에서)

-> .../my-app/platforms/android 를 import

http://docs.phonegap.com/plugin-apis/
# cordova plugin add cordova-plugin-geolocation   // 위치 정보
# cordova plugin add cordova-plugin-camera // 카메라 사용
# cordova plugin add cordova-plugin-media-capture  // 이미지 캡쳐
# cordova plugin add cordova-plugin-device-orientation  // 디바이스의 방향 감지
# cordova plugin add cordova-plugin-device  // 디바이스 정보
# cordova plugin add cordova-plugin-dialogs  // 디바이스에 알림 메시지
# cordova plugin add cordova-plugin-vibration // 지정된 시간 동안 디바이스 진동
```
