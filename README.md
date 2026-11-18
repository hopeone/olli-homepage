# OLLI 홈페이지

정적 HTML/CSS/JavaScript로 만든 개인 개발 프로젝트 소개 사이트입니다.

## GitHub Pages 배포

1. `olli-homepage` 같은 Public 저장소를 생성합니다.
2. 이 폴더 안의 파일과 폴더를 저장소 루트에 업로드합니다.
3. Settings → Pages → Build and deployment에서 `Deploy from a branch`, `main`, `/(root)`를 선택합니다.
4. Pages의 Custom domain에 `olli.co.kr`을 입력합니다.
5. DNS 제공업체에 GitHub Pages 공식 문서에 안내된 A 레코드 4개를 설정하고, DNS 확인 후 HTTPS를 활성화합니다.

APK 다운로드 링크는 공개 배포용 파일을 점검한 후 `apps/timora.html`, `apps/ledger.html`에 추가하세요.

## 공개 전 확인

- APK에 개인 데이터, 비밀키, 테스트용 계정 정보가 포함되지 않았는지 확인
- Timora Google OAuth 공개 범위 및 신규 사용자 로그인 검증
- 실제 데이터 처리 방식에 맞는 개인정보처리방침 작성
- GitHub Pages 저장소는 공개되므로 민감한 파일을 넣지 않기
