# 무온 (MUON) — 홈페이지

신축 아파트 사전점검 기록을 블록체인으로 봉인하고, 하자담보기간 10년 동안 관리하는 서비스의 랜딩 페이지입니다.

- 단일 HTML 파일 (`index.html`) — 외부 빌드 없이 그대로 배포 가능
- 디자인 토큰: 딥그린 `#0E3B2E` · 민트 `#2FD3A0` · 페이퍼 `#F6F6F1`
- 반응형 (데스크톱 / 태블릿 / 모바일)

## 로컬에서 보기

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## 배포

### GitHub Pages
1. Settings → Pages
2. Source: `Deploy from a branch` → Branch: `main` / root
3. 공개 주소: `https://<아이디>.github.io/muon-home/`
   (비공개 저장소는 GitHub Pro 이상에서만 Pages 사용 가능)

### Cloudflare Pages / Netlify
저장소를 연결하거나, 폴더를 그대로 드래그해 배포합니다. 빌드 명령 없음, 출력 디렉터리는 루트.

## 수정이 필요한 값

`index.html` 하단 푸터의 대괄호 항목을 실제 정보로 바꿔 주세요.

- `[이메일 주소]`
- `[등록 후 기재]` — 사업자등록번호
- `[사업장 주소]`

## 라이선스

© 2026 MUON Inc. All rights reserved.
