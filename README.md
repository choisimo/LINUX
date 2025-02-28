# LINUX 명령어 등 공부용으로 만듦


```txt
1️⃣ 프로세스와 서브쉘 (Subshell)
( command ) vs { command; }
&&, ||, ;, & 연산자 동작 차이
프로세스 ID ($$, $!, $?)와 종료 상태

2️⃣ 입출력 리디렉션 (I/O Redirection)
>, >>, <, 2>, 2>&1
| (파이프)와 tee 명령어
/dev/null과 표준 입력/출력 흐름 제어
>
3️⃣ 배경 실행 및 잡 컨트롤 (Job Control)
&로 백그라운드 실행
jobs, fg, bg, kill 명령어
nohup과 disown의 차이

4️⃣ 쉘 변수와 환경 변수
export VAR=value와 env
$PATH, $HOME, $SHELL, $USER 등 기본 변수
set, unset, readonly 명령어

5️⃣ 조건문과 루프
[ ]와 [[ ]] 차이 (조건문)
if-else, case 문법
for, while, until 반복문

6️⃣ 쉘 스크립트 작성
함수 정의 및 호출 (function my_func { })
source와 실행 (./script.sh vs source script.sh)
trap을 이용한 인터럽트 핸들링 (Ctrl+C 방지)

7️⃣ 고급 명령어 활용
find, xargs, awk, sed 활용
grep과 cut로 데이터 추출
cron과 systemd를 활용한 자동 실행
```
