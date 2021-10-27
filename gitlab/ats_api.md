---
description: ATS_API 환경 설정
---

# ATS\_API 내려받기

#### 1. "Visual Studio Code" 검색 후 실행&#x20;

![](../.gitbook/assets/exs\_01.png)

#### 2. "파일(F)" --> "폴더 열기" 클릭&#x20;

![](../.gitbook/assets/exs\_02.png)

#### 3. "로컬 디스크(C:)" 폴더에서 "ats\_project-main" 선택 후 "폴더 선택" 버튼 클릭&#x20;

![](../.gitbook/assets/exs\_03.png)

#### 4. 체크박스 체크 후 "예, 작성자를 신뢰합니다." 버튼 클릭 &#x20;

![](../.gitbook/assets/gd\_00.png)

#### 5. "터미널(T)" --> "새 터미널" 클릭&#x20;

![](../.gitbook/assets/gd\_01.png)

#### 6. 터미널에 "git clone -b develop http://gitlab.ats.com:9000/root/ats\_api.git" 명령어 실행&#x20;

```
git clone -b develop http://gitlab.ats.com:9000/root/ats_api.git
```

![](../.gitbook/assets/gd\_02.png)

#### 7. 가입한 아이디(or Username) 및 비밀번호 입력

![](../.gitbook/assets/gd\_03.png)

#### 8. "ats\_api" 폴더와 파일이 생성 되었는지 확인, 모든 설치가 끝났는지 확인 &#x20;

![](../.gitbook/assets/gd\_04.png)

#### 9. 터미널에 "cd ats\_api" -> "npm install" 명령어 실행&#x20;

```
cd ats_api
npm install
```

![](../.gitbook/assets/gd\_05.png)

#### 10. "node\_modules" 폴더와 파일이 생성 되었는지 확인, 모든 설치가 끝났는지 확인 &#x20;

![](../.gitbook/assets/gd\_06.png)

#### 11. "파일(F)" --> "파일에서 작업 영역 열기..." 클릭&#x20;

![](../.gitbook/assets/gd\_07.png)

#### 12. "내 PC/로컬 디스크 (C:)/ats\_project-main/" 폴더의 "ATS\_PROJECT.code-workspace" 열기&#x20;

![](../.gitbook/assets/gd\_08.png)

#### 13. "파일(F)" --> "작업 영역에 폴더 추가..." 클릭 &#x20;

![](../.gitbook/assets/gd\_09.png)

#### 14. "내 PC/로컬 디스크 (C:)/ats\_project-main/" 폴더의 "ats\_api" 폴더 선택 후 "추가(A)" 버튼 클릭&#x20;

![](../.gitbook/assets/gd\_10.png)

#### 15. "ATS\_PROJECT(작업 영역)" 확인&#x20;

![](../.gitbook/assets/gd\_11.png)

#### 16. 상단의 "..." 버튼 클릭 --> "Npm 스크립트" 클릭&#x20;

![](../.gitbook/assets/gd\_12.png)

#### 17. 하단의 NPM 스크립트 start 실행 버튼 클릭&#x20;

![](../.gitbook/assets/gd\_13.png)

#### 18. 터미널에 started 메세지 확인&#x20;

![](../.gitbook/assets/gd\_14.png)

#### 19. 웹 브라우저에 "http://localhost:3001" 입력 후 접속 확인 &#x20;

![](../.gitbook/assets/gd\_15.png)

#### 20. 터미널의 종료 버튼(휴지통 모양) 클릭해서 서버 종료 &#x20;

![](../.gitbook/assets/gd\_16.png)
