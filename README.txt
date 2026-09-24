금융 상담용 1페이지 홈페이지 — 사용법

1) index.html을 메모장이나 VS Code로 엽니다.
2) 파일 맨 아래의 아래 부분을 찾습니다.

const SITE = {
  companyName: "상담센터",
  telegramUrl: "https://t.me/CHANGE_ME"
};

3) companyName을 실제 표시할 이름으로 변경합니다.
4) telegramUrl을 실제 텔레그램 주소로 변경합니다.
   예: https://t.me/your_username

5) 아래 회사정보도 실제 정보가 있다면 수정하세요.
   - 운영 주체
   - 사업자등록번호
   - 대표자
   - 주소

6) 파일을 저장한 뒤 index.html을 더블클릭하면 PC에서 바로 미리보기 가능합니다.

무료 공개 방법(GitHub Pages)
- GitHub 계정 생성
- 새 Repository 생성
- index.html 업로드
- Settings > Pages
- Deploy from a branch 선택
- main / root 선택
- 잠시 기다리면 https://아이디.github.io/저장소명/ 형태 주소가 생성됩니다.

구글 검색 등록
- 사이트가 공개된 뒤 Google Search Console에 사이트를 등록
- 소유권 확인
- URL 검사에서 홈페이지 색인 요청
- 실제 도메인을 구매하면 index.html 안의 example.com 부분을 실제 도메인으로 변경

주의
- 현재 canonical/OG/구조화 데이터의 URL은 example.com으로 되어 있습니다.
- 실제 도메인을 정하면 해당 부분을 모두 실제 주소로 바꾸는 것이 좋습니다.
- 금융/은행 관련 표현은 실제 사업 관계와 법적 지위에 맞게 사용하세요.
