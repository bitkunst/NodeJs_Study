Node.js는 chrome V8 JavaScript 엔진으로 빌드된 JavaScript 런타임 입니다.
V8 엔진을 가지고 여러가지 파일을 이용해 만들어진 JavaScript 런타임(코드 실행기)이다.

브라우저와 Node.js는 자바스크립트를 실행하는 공간이 다르다.
Node.js는 브라우저가 자바스크립트를 실행해주는 것이 아니라 내 컴퓨터가 자바스크립트를 실행해준다. 

CLI : Comand Line Interface
컴퓨터를 명령어를 이용해 한줄 한줄 작성하여 조작하는 것

OS : Operating System (운영체제)
window, Linux 같은 운영체제,,
단순하게 말해서, OS를 사용하는 이유는 컴퓨터를 실행시키기 위해서이다. 
하드웨어는 메인보드, 램, 마우스, 키보드 등등 컴퓨터 안에 있는 부품들을 일컫는 말이고 소프트웨어는 컴퓨터 안에서 프로그래밍적으로 돌아가는 것들을 일컫는다.
OS가 하는 역할은 무엇일까? OS는 하드웨어가 실행가능하게끔 해준다. 하드웨어에 입력을 주었을 때 결과물이 출력되게 해주는 게 OS가 하는 역할이다.
ex) 마우스를 통해 하드웨어에 입력을 해주면 OS가 그 입력을 받아서 모니터에 출력을 해준다.
하드웨어를 통해 입력을 받으면 그 입력을 받아서 출력해 주는 게 OS가 해주는 역할이다. (입력과 출력을 연결)

OS의 종류 : Window, Mackintosh, Linux, Unix, IOS, Android 
Window -> 컴퓨터를 조작하는 방식이 그래픽 요소를 활용해 조작하는 방식 : GUI (Graphic User Interface)
Linux, Unix -> GUI 형태가 아닌 CLI 형태로 컴퓨터를 조작한다. 그래픽 요소가 아닌 텍스트를 통해서 입력과 출력을 조작한다. 

내가 입력한 것을 컴퓨터가 받아서 내가 원하는 결과물을 출력하게 하는 것이 프로그램이다. 
Unix를 기반으로 해서 만든 것이 애플의 OS인 Makintosh
Linux도 Unix를 기반으로 만들어졌다. 무료이다 보니 많은 버젼이 존재한다. 우툰투, 센트OS, 페도라, 레드햇 등등..

Node.js : 자바스크립트 언어로 command 명령어를 만드는게 Node.js이다. 
자바스크립트 문법을 통해 컴퓨터의 입력과 출력을 받아서 프로그램을 만들 수 있게 하는 것이 Node.js의 역할이다.
프로그램을 만든다는 것은 간단하게 말하면, 명령어를 입력하면 출력되는 것을 만드는 것이다.


VM : Virtual Machine (가상머신)
WSL : Windows Subsystem for Linux
하나의 컴퓨터 안에 있는 여러 자원들을 쪼개서 컴퓨터 한 대에 OS를 두개 설치할 수 있다. 컴퓨터의 자원을 나눠서 OS를 따로 설치하는 것.
이 경우, 컴퓨터의 성능이 반으로 줄어들게 되어 비효율적이다. 
WSL 이란 Window 안에서 Linux를 설치할 수 있게끔 하는 것이다. Window 안에서 Linux가 돌아가는 것이기 때문에 자원이 공유된다. VM과는 다소 다른 개념이다. 
(VM은 자원을 분배하는 개념이라면 WSL은 자원을 공유하는 개념)
Window 에서 뭔가를 설치하면 Linux 안에서도 사용할 수 있다. 

WSL2가 출시되고 난 후 Window에서 Docker를 사용하기가 수월해졌다. 





