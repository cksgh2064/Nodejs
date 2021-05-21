# Nodejs

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
