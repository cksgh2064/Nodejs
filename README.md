# Node.js

Node.js는 Chrome V8 JavaScript 엔진으로 빌드된 `JavaScript 런타임`

<hr />

> <u>Chrome V8 JavaScript 엔진</u>  
>  자바스크립트의 문법을 해석하고 실제로 동작시켜주는 엔진

> <u>JavaScript 런타임</u>  
>  프로그래밍 언어가 동작하는 환경

JavaScript 동작할수 있는 환경 2가지

- 컴퓨터
  - 웹 페이지를 효율적인 개발을 위해 컴퓨터에서 개발해야 해야 한다.
- 웹 브라우저
  - html, css, js로만으로도 동작은 하지만 저 3가지로만 개발한다면 비효율적이다.

```planetext
 개발을 하는 컴퓨터에 모듈들을 설치하여 도움을 받아가며 개발을 해야한다. 하지만 그 모듈들은 직접적으로 웹브라우저에서 동작을 할수 없기 때문에 대표적으로 node.js 환경에서 도움을 받은 내용들을 HTML CSS JS로 변환을 해줘야한다.
  그 변환작업은 그냥 일어나는게 아니기에, 컴퓨터에게 그 변환작업에 대한 명령이 필요하고 그 명령이 돌아가는 환경이 필요하다. 그래서 nodejs환경에서 javascript 프로그래밍 언어로 그러한 변환을 만들어 줄수 있어야 하고, 그 변환된 결과를 HTML,CSS,JS로 만들어서 웹브라우저에 동작을 시켜준다.
```

<hr/>
## - NVM 설치

```plaintext
    - Mac 설치법
        - curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

    - Windows 설치법
        - https://github.com/coreybutler/nvm-windows/releases -> nvm-setup.zip

        설치후 버전확인 : nvm --version
```

## - NVM 사용법

```bash
  nvm ls : 설치된 nodejs 버전 확인
  nvm install xx.xx.xx : 버전 설치
  nvm uninstall xx.xx.xx : 버전 삭제
  nvm use xx.xx.xx : 버전 사용
  node --version : 현재 사용 버전 확인
```

## - NPM 사용법

```plaintext
  1. npm init -y : 파일 생성

    - node_modules : 생성된 모듈들이 있는 폴더
    - package-lock.json : 패키지 내의 자세한 패키지들을 관리하는 파일
    - package.json : 패키지 내역들을 보여준다

  2. npm install XXX : 일반 의존성 패키지 설치
    - npm install -D XXX :개발용 의존성 패키지 설치
```
