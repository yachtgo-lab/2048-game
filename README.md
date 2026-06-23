# 2048 PWA

## 실행 방법
1. 이 폴더를 웹서버에 올립니다.
2. `index.html`로 접속합니다.
3. 모바일 Chrome/Edge에서 "앱으로 설치" 버튼 또는 브라우저 메뉴의 "홈 화면에 추가"를 사용합니다.

## 주의
PWA 설치와 Service Worker는 보통 `file://` 직접 열기에서는 동작하지 않습니다.
로컬 테스트는 VS Code Live Server, Python 서버, GitHub Pages, Netlify, Vercel 등을 사용하세요.

예:
```bash
python -m http.server 8000
```
접속:
```text
http://localhost:8000
```
