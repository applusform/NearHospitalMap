# NearHospitalMap (가까운 병원)
공공데이터 Open API 를 사용한 가까운 병원 위치 검색 (주변 병원 모두 지도에 표시)

Screen shot :
![Screen shot](http://applusform.github.io/NearHospitalMap/screenshot1.png)

### 인증키 발급
https://www.data.go.kr 에서 오픈API - 전국 병‧의원 찾기 서비스의 [SERVICE KEY]를 발급 받아야 합니다. 


#### MOML Application Viewer로 바로 실행
1. MOML Application Viewer를 설치한 후 실행합니다. ( [Google Play Store](https://play.google.com/store/apps/details?id=org.mospi.momlappviewer), [Xcode Project](https://github.com/applusform/MOMLAppViewer_iOS), [Android Studio Project](https://github.com/applusform/MOMLAppViewer_Android_Studio) )
2. 주소 입력창에 **applusform.github.io/NearHospitalMap** 를 입력합니다.

#### 온라인 앱 자동 빌드( .apk)
1. http://apps.yooic.com 사이트 가입후 로그인합니다.
2. **[프로젝트 생성]** 메뉴에서 앱타입으로 **[인스턴트 앱]**을 선택하고 **[다음]**을 누릅니다.
3. **[MOML 어플리케이션 URL]**에 **applusform.github.io/NearHospitalMap/applicationInfo.xml**를 입력한 후 **[완료]**를 누릅니다.
4. **[내 프로젝트 관리]** 메뉴에서 APK **[생성]** 버튼을 누릅니다.

#### 직접 빌드 ( .apk, .ipa )
1. http://ApplusForm.com 사이트의 **[Get Agate]** 메뉴에서 **MOML API Demo Peoject** 를 다운로드 받습니다.
2. **moml** 폴더의 모든 파일들을 이 프로젝트의 파일로 교체합니다.
3. 빌드하고 실행합니다.
