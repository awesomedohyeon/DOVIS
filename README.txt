DOVIS v0.0.0 (베타) — PWA 배포 파일

[파일]
index.html            앱 본체
manifest.webmanifest  앱 이름·아이콘·색 (설치용)
sw.js                 오프라인·설치용 서비스 워커
icons/                앱 아이콘 (C1 로고)

[GitHub Pages로 출시하기]
1. github.com 가입 → 오른쪽 위 + → New repository → 이름: dovis → Public → Create
2. 저장소 화면에서 "uploading an existing file" → 이 폴더 안의 파일·icons 폴더를 통째로 끌어다 놓기 → Commit changes
3. Settings → Pages → Branch: main, 폴더: / (root) → Save
4. 1~2분 뒤 https://<내아이디>.github.io/dovis/ 로 접속
5. 갤럭시 크롬에서 열기 → 메뉴(⋮) → "앱 설치" (또는 "홈 화면에 추가")

[기존 일정 옮기기]
claude.ai의 DOVIS → 설정 → 데이터 → "백업 복사"
설치한 앱 → 설정 → 데이터 → "백업 붙여넣기"

[v0.0.0 베타에서 아직 안 되는 것]
- 폰 ↔ 패드 동기화 (기기마다 따로 저장)
- DOVIS AI 대화 (규칙 기반 대화는 됨)
- 구글 캘린더 가져오기
→ v0.1에서 Supabase · AI 키 · 구글 로그인 연결 예정
