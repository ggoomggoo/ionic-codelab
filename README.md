# ionic

## links

* repo
    - [https://github.com/zard21/codelab-my-movies](https://github.com/zard21/codelab-my-movies)
    - [https://github.com/zard21/codelab-my-todos](https://github.com/zard21/codelab-my-todos)
* docs
    - css
        + like bootstrap
            * [http://ionicframework.com/docs/components/](http://ionicframework.com/docs/components/)
    - javascript
        + [http://ionicframework.com/docs/api/directive/ionInfiniteScroll/](http://ionicframework.com/docs/api/directive/ionInfiniteScroll/)
        + [http://ionicframework.com/docs/api/directive/ionRefresher/](http://ionicframework.com/docs/api/directive/ionRefresher/)

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


## 앱 배포하기


## Ionic 하이브리드 앱 개발 시 참고사항