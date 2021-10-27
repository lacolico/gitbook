---
description: ATS_WEB 환경 설정
---

# ATS\_WEB 내려받기

#### 1. "Visual Studio Code" 검색 후 실행 &#x20;

![](../.gitbook/assets/exs\_01.png)

#### 2. "파일(F)" --> "폴더 열기" 클릭&#x20;

![](../.gitbook/assets/exs\_02.png)

#### 3. "로컬 디스크(C:)" 폴더에서 "ats\_project-main" 선택 후 "폴더 선택" 버튼 클릭&#x20;

![](../.gitbook/assets/exs\_03.png)

#### 4. 체크박스 체크 후 "예, 작성자를 신뢰합니다." 버튼 클릭 &#x20;

![](../.gitbook/assets/gd\_00.png)

#### 5. "터미널(T)" --> "새 터미널" 클릭&#x20;

![](../.gitbook/assets/gc2\_01.png)

#### 6. 터미널에 "git clone -b develop http://gitlab.ats.com:9000/root/ats\_web.git" 명령어 실행 &#x20;

```
git clone -b develop http://gitlab.ats.com:9000/root/ats_web.git
```

![](../.gitbook/assets/gc2\_02.png)

#### 7. 가입한 아이디(or Username) 및 비밀번호 입력

![](../.gitbook/assets/gd\_03.png)

#### 8. "ats\_web" 폴더와 파일이 생성 되었는지 확인, 모든 설치가 끝났는지 확인 &#x20;

![](../.gitbook/assets/gc2\_03.png)

#### 9. 터미널에 "cd ats\_web" -> "npm install" 명령어 실행 &#x20;

```
cd ats_web
npm install
```

![](../.gitbook/assets/gc2\_04.png)

#### 10. "node\_modules" 폴더와 파일이 생성 되었는지 확인, 모든 설치가 끝났는지 확인 &#x20;

![](../.gitbook/assets/gc2\_05.png)

#### 11. "파일(F)" --> "파일에서 작업 영역 열기..." 클릭&#x20;

![](../.gitbook/assets/gc2\_06.png)

#### 12. "내 PC/로컬 디스크 (C:)/ats\_project-main/" 폴더의 "ATS\_PROJECT.code-workspace" 열기&#x20;

![](../.gitbook/assets/gc2\_07.png)

#### 13. "파일(F)" --> "작업 영역에 폴더 추가..." 클릭 &#x20;

![](../.gitbook/assets/gc2\_08.png)

#### 14. "내 PC/로컬 디스크 (C:)/ats\_project-main/" 폴더의 "ats\_web" 폴더 선택 후 "추가(A)" 버튼 클릭&#x20;

![](../.gitbook/assets/gc2\_09.png)

#### 15. "ATS\_PROJECT(작업 영역)" 확인&#x20;

![](../.gitbook/assets/gc2\_10.png)

#### 16. 상단의 "..." 버튼 클릭 --> "Npm 스크립트" 클릭&#x20;

![](../.gitbook/assets/gc2\_11.png)

#### 17. 하단의 NPM 스크립트 start 실행 버튼 클릭&#x20;

![](../.gitbook/assets/gc2\_12.png)

#### 18. "http://localhost:3000" 웹 화면 확인&#x20;

![](../.gitbook/assets/gc2\_13.png)

#### 19. 터미널의 종료 버튼(휴지통 모양) 클릭해서 서버 종료&#x20;

![](../.gitbook/assets/gc2\_14.png)

