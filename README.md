# stater-kit

✿ Overview

빠른 웹사이트 제작을 위한 Front-End 개발 도구 입니다. 기본적으로 Node, NPM, Gulp, Sass, Babel을 사용합니다.

v1.x: node, npm, gulp, babel, sass, browserify / jQuery, angular1.x
✿ Features

Feacture	Summary
실시간 웹 서버 테스트 환경	HTML, SASS, JS 변경 내용을 실시간으로 감지하고 빌드합니다.
웹 개발 패키지 관리	npm또는 bower을 하나의 패키지로 통일을 하여 사용하고 싶지만 아직까지 npm이 프론트엔드 라이브러리로써 버전관리가 제대로 안되는 부분이 있어 bower을 일부 사용합니다.
CSS 프리프로세싱	효과적인 유지보수를 위해 Sass를 사용합니다.
Front-End 환경에서의 모듈화	프런트 환경에서도 모듈관리를 할 수 있습니다.
구조적은 폴더 구조를 설계함으로써 유지보수의 힘을 실어 줍니다.
이미지 최적화	JPG, GIF, PNG 파일 크기를 최적화 합니다.
이미지 스프라이트 생성	브라우저에서 Request 수 를 줄이기 위해 이미지를 스프라이트 할 수 있습니다.
옵션을 통해 sprite.png, sprite.scss 파일을 자동으로 생성합니다.
문법 검사	Sass, JS 문법 검사를 하여 개발의 편리성을 제공합니다.
파일 압축	웹사이트 최적화를 위해 코드 압축을 도와줍니다.
폰트 아이콘 생성	선택적으로 SVG 파일을 폰트로 자동 생성합니다.
ES2015(ES6)	최신 자바스크립트 버전인 ES2015를 지원합니다.
웹 앱	모바일 웹 앱을 지원합니다.
웹브라우저 파일 캐쉬	파일 캐쉬를 통하여 웹사이트 속도 개선합니다.
✿ Dependent Modules

유틸리티(Utillities)
del - 폴더 및 파일 제거
gulp - 스트리밍 업무별 빌드 시스템
gulp-cache - 임시 파일 기반 캐싱 프록시 작업
gulp-concat - 파일 병합
gulp-filter - 파일 확장자로 필터링
gulp-if - 조건에 따른 업무 처리
gulp-load-plugins - package.json 파일을 읽어 Gulp 관련 플러그인 호출
gulp-print - 파일의 이름을 출력
gulp-size - 업무 처리 결과 파일 크기를 출력
gulp-sourcemaps - 개발용 소스맵(Sourcemap) 생성
gulp-util - Gulp 유틸리티
lodash.assign - 모듈화, 성능 등을 제공하는 자바스크립트 유틸리티 라이브러리
merge-stream - 다중 스트림을 하나의 스트림으로 변환
run-sequence - 정해진 순서에 따라 업무 실행
sw-precache - 특정 자원을 사전 캐쉬 처리
sw-toolbox - Service Worker 컬렉션
vinyl-buffer - 버퍼를 스트리밍 파일로 변환
vinyl-source-stream - 기존 텍스트를 스트림으로 변환
watchify - browserify에 대한 감시 모드
웹 서버(Web Server)
browser-sync - 디바이스 별 실시간 웹 테스트
프리프로세싱(Preprocessing) & 컴파일(Compile)
babel-core - Babel 기본 컴파일 도구
babel-preset-es2015 - 바벨에 대한 ES2015 플러그인
babelify - babel 변환을 위한 browserify
browserify - 클라이언트 환경에서의 모듈화 제공
gulp-sass - Sass -> CSS 변환
CSS 브라우저 벤더 프리픽스(Browser Vendor Prefix)
gulp-autoprefixer - Prefix CSS
문법 검사(Validation Syntax)
jshint - 자바스크립트 코드 문법 검사
jshint-stylish - JSHint를 위한 세련된 스타일 제공
gulp-jscs - 자바스크립트 코드 스타일 확인 (Google, Airbnb, jQuery, ...)
gulp-jshint - Gulp를 위한 JSHint 플러그인
gulp-sass-lint - Sass 문법 검사
압축(Compress)
gulp-htmlmin - HTML 압축
gulp-uglify - JS 압축
문서화(Documentation)
sassdoc - Sass 문서화
이미지 최적화(Optimization)
gulp-imagemin - PNG, JPEG, GIF 및 SVG 이미지를 압축
imagemin-pngquant - imagemin을 위한 최적화 플러그인
이미지 스프라이트(Sprites) 및 아이콘폰트(Iconfont)
gulp-iconfont - 여러 SVG 아이콘을 이용하여 아이콘 글꼴 생성
gulp-iconfont-css - iconfont로 글꼴을 만들 때 Sass/SCSS 또는 CSS를 만들어 주는 플러그인
gulp.spritesmith - 스프라이트 이미지 및 CSS 변수를 생성
gulp-svg-sprite - SVG 스프라이트
gulp-svg2ttf - SVG 글꼴에서 TTF 글꼴 만들기
gulp-svgicons2svgfont - 하나의 글꼴에 여러 SVG를 번들(Bundle)
gulp-ttf2eot - TTF 글꼴에서 EOF 글꼴 만들기
gulp-ttf2woff - TTF 글꼴에서 WOFF 글꼴 만들기
gulp-ttf2woff2 - TTF 글꼴에서 WOFF2 글꼴 만들기
✿ Installation

※ OSX 사용자는 설치 관리자 권한이 필요하므로 sudo를 맨 앞에 붙여줄 것.

  node -version  # Nodejs 설치 및 버전 확인
  npm -version  # NPM 버전 확인
  npm install -g gulp  # Gulp Global 설치
  npm install  # package.json 모듈 설치
✿ Requirements

Node >=4.4.3
NPM >=2.15.1
Sass >= 3.4.2
✿ Quick Start

  gulp  # Gulp의 모든 업무를 수행
  gulp serve  # 기본적인 업무를 포함하여 웹서버 및 감시모드 실행을 통해 개발 시작
✿ Gulp Tasks

기본 업무
  gulp  # Gulp의 모든 업무를 수행 (clean 제외)
삭제 업무
  gulp clean  # 빌드(build)를 통해 생성되어지는 'dist'폴더를 삭제 합니다.
복사 업무
  gulp copy  # 빌드 과정이 필요없는 파일들을 배포 폴더로 복사합니다.
  gulp copy:font  # 폰트 파일을 배포 폴더로 복사합니다.
  gulp copy:sw-scripts  # Service-Worker 관련 파일들을 배포 폴더로 복사합니다.
서버 및 감시 업무
  gulp serve  # 웹 서버 가동 및 HTML, SASS, JS 파일들을 관찰하여 자동 반영합니다.
뷰 업무
  gulp views  # HTML파일들을 옵션을 통해 이동 및 압축을 합니다.
스타일 업무
  gulp styles  # Sass 빌드
  gulp styles:lint  # Sass 문법 검사
스크립트 업무
  gulp scripts  # JS 빌드
  gulp scripts:lint  # JS 문법 검사
이미지 업무
  gulp images  # 이미지 최적화
이미지 스프라이트 업무
  gulp sprite  # 이미지 스프라이트
아이콘 폰트 생성 업무
  gulp iconfont  # SVG 아이콘을 폰트화
파일 캐쉬 및 오프라인 설정 업무
  gulp generate-service-worker  # 파일 캐쉬
✿ Browser Support

Chrome
Edge
Firefox
Safari
Opera
Internet Explorer 10+ (※ include Angularjs1.x)
