# 우리 반 AI 게임 제작실

초등학교 태블릿 수업용 단일 HTML 웹앱입니다.

## 기능
- 과일 받기, 미로 탈출, 점프 모험, 벽돌 깨기 4가지 기본 게임
- 터치 버튼 조작
- ChatGPT 요청문과 HTML 코드 복사
- HTML 코드 편집, 격리된 iframe 실행, 브라우저 저장/불러오기
- 학생 작품 HTML 다운로드

## GitHub Pages 배포
1. GitHub에서 **공개(Public)** 저장소를 만듭니다.
2. 이 폴더의 `index.html`을 저장소 최상위에 업로드합니다.
3. Settings → Pages → Build and deployment → Deploy from a branch를 선택합니다.
4. `main` / `/(root)`를 선택하고 저장합니다.
5. 배포가 완료되면 표시되는 `https://사용자명.github.io/저장소명/` 주소를 학생에게 공유합니다.

## 주의
- 학생 작품은 기기 브라우저의 localStorage에 저장되며 기기 변경/브라우저 데이터 삭제 시 사라질 수 있습니다. HTML 다운로드로 백업하세요.
- 학생이 실행하는 임의 HTML 코드는 sandbox iframe에 격리되지만, 외부 통신을 완전히 차단하는 것은 아닙니다. 교사의 지도 아래 사용하세요.
- HTML 실행 사이트에서 붙여 넣은 코드는 교사가 검토하도록 안내하세요.
- GitHub Pages 공개 사이트에 학생 개인정보나 학생 작품 원본을 무단 공개하지 마세요.
