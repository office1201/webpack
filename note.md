- node -v

- npm init

- npm init -y

- npm install jquery

- npm install jquery-ui

- npm install gulp

- npm uninstall gulp

- sudo npm install gulp --global

  - /usr/local/lib/node_modules
  - 시스템 레벨 라이브러리에서 제공하는 CLI등 활용 위해 시스템 레벨(전역)으로 설치하는 것

- 배포용 라이브러리(dependencies)와 개발용 라이브러리(devDependencies) 차이

  - 배포용 라이브러리(dependencies)
    - 어플리케이션 로직과 관련, 화면 DOM 조작 도와주는 부가 라이브러리, 전부 어플리케이션 로직 구현시 연관, 화면의 로직과 직접적 연관.
    - 예. "react", "angular", "vue", "chart", "jquery"
    - 개발용 라이브러리 설치: `npm i jquery`
  - 개발용 라이브러리(devDependencies)
    - 개발을 할 때 도와주는 보조 라이브러리, (예. "webpack", "js-compression", "sass")
