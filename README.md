# helloBabel
Babel 기초 사용법 연습

repository를 실행하는 방법

1. Babel을 사용하기 위해 nodeJS, npm(또는 yarn)을 설치한다.
2. npm init 명령어를 실행하여 package.json을 만들어준다.
(잘 모르겠으면 명령어를 실행한 이후 계속 엔터만 누르다 보면 완료 메세지가 뜨고 파일이 만들어 진다. default설정으로 만들어진다.)
3. npm install babel-cli babel-core bable-preset-env --save-dev 명령어를 사용해서 babel을 실행하기 위한 패키지 들을 다운받는다.
4. npm install babel-cli babel-preset-env -g 명령어를 사용하여 로컬 컴퓨터 어디서든지 명령어를 사용할 수 있게 한다.
(3번과 다른 과정이다. 이 방법이 싫다면 node_modules 하위에 있는 babel 디렉토리를 찾아서 node 명령어로 실행 시켜주면 된다.)
(babel-preset-env는 작성안해도 될 것 같은데 테스트를 안해봄)
5. babel --version 명령어를 실행하여 바벨 버전이 정상적으로 출력되는걸 확인한다.
6. babel src -d build 명령어를 실행한다.
7. build 하위에 transpile이된 스크립트 파일을 확인한다.

요약하자면 ..
1. nodeJS,npm 설치
----------------------
여기서부턴 무조건 프로젝트 root디렉토리에서 한다.

2. npm init 실행 후 엔터를 계속 누름
3. npm install babel-cli babel-core bable-preset-env --save-dev 명령어 실행
4. npm install babel-cli babel-preset-env -g 명령어 실행
5. babel src -d build 실행
6. build 디렉토리 하위에 결과물 확인


