# ionic

## links

* [제10-2회 웹프레임워크 코드랩 - IONIC을 통한 하이브리드 앱 개발하기](http://onoffmix.com/event/83653)
* repo
    - codelab
        + [https://github.com/zard21/codelab-my-movies](https://github.com/zard21/codelab-my-movies)
            * angular
            * ionic component
            * infinite scroll
            * refresher
        + [https://github.com/zard21/codelab-my-todos](https://github.com/zard21/codelab-my-todos)
            * CRUD
            * route
            * swipe
            * localStorage
        + codelab
            * [https://github.com/t1t1/ionic-movie-app](https://github.com/t1t1/ionic-movie-app)
* docs
    - css
        + like bootstrap
            * [http://ionicframework.com/docs/components/](http://ionicframework.com/docs/components/)
    - javascript
        + [http://ionicframework.com/docs/api/directive/ionInfiniteScroll/](http://ionicframework.com/docs/api/directive/ionInfiniteScroll/)
        + [http://ionicframework.com/docs/api/directive/ionRefresher/](http://ionicframework.com/docs/api/directive/ionRefresher/)
    - icon
        + [http://ionicons.com/](http://ionicons.com/)
    - publish
        + [http://ionicframework.com/docs/guide/publishing.html](http://ionicframework.com/docs/guide/publishing.html)
    - ref
        + [[Ionic2] 기본 설치 및 사용법](http://mobicon.tistory.com/488)
        + [Ionic, Cordova 기반 하이브리드 안드로이드 애플리케이션 개발 사례 공유](https://readme.skplanet.com/?p=11698)

## index

* Ionic Framework 이해하기
* Ionic Framework 개발환경 설치
* Movie List 앱 만들기
* To-Do List 앱 만들기
* 앱 배포하기
* Ionic 하이브리드 앱 개발 시 참고사항

## Ionic Framework 이해하기

* ...

## Ionic Framework 개발환경 설치

* ...
* start app [template]
    - blank
        + add component
    - version
        + default 1
        + --v2 option
            * angular 2
            * component plus
* serve
    - --lab
* ios
    - platform add ios
    - build ios
    - emulate ios
        + [--target="iPhone-6"]
            * 
        + [-livereload]
            * 자동 새로고침
* android
    - ionic box
        + lightweight 
* plugin
    - cordova
        + geolocation
        + 
    - plugin add ...


## Movie List 앱 만들기

* api
    - json
        + [http://52.78.168.126:8080/api/movie/list/0](http://52.78.168.126:8080/api/movie/list/0)
* 구현 내용
    - ...
    - 무한스크롤
* angular
    - app.js
    - index.html
    - Conttroller
        + .controller('MoviewCtrl', function($scope) {
            * $scope.moview = [
            * {
                - title: '괴물'
            * }
            * ]
        + })
* CROS
    - chrome
        + plugin
    - ionic
        + localhost 개발환경
        + proxy 제공
            * path
            * proxyUrl
            * 실제환경, emulator 시 제거 필요
* angular
    - ...
* ion-infinite-scroll
    - ...
* ion-refresher
    - twitter
    - ...
* emulrator
    - update url
        + delete proxies
    - ios
        + ...
    - android
        + ...
        + phone debugging
            * ionic run android

## To-Do List 앱 만들기

* ...
* angular ui router
    - .config
        + $stateProvider
        + $urlRouterProvider
    - nav-var
    - ...
* ...
* angular factory
    - TodoData
* window.localStorage
* delete
    - swipe
* ...
* reorder

## 앱 배포하기

* config.xml
    - cordova에서 제공
    - 이름
    - id
    - version
* image
    - icon
    - splash
    - 각각 이미지 생성
        + 기본이미지 보다 작은 이미지를 사용하면 일부 이미지 생성 불가
* ref
    - [http://ionicframework.com/docs/guide/publishing.html](http://ionicframework.com/docs/guide/publishing.html)
* 심사
    - ios
        + 하이브리드
            * ionic 어필, 재심사 요청

## Ionic 하이브리드 앱 개발 시 참고사항

* 레이아웃
    - 구형 단말기 테스트 필요
* 성능
    - ios
        + 스크립트 기능 좋음
    - android
        + 구형 단말기(4.0~4.3)에서 성능 저하
* 푸시
    - phonegap-plugin-push
        + 등록
        + 노티
        + 에러
    - ios 인증서 필요. 처리
* OAuth
    - ngCordovaOauth
        + web 인증
* SNS Sharing
    - ngCordova socialSharing
* kakaotalk Sharing
    - org.apache.cordova.engine.SystemWebViewClient 의 커스터마이징 필요