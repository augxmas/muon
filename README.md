# 무온 (MUON) — 웹사이트

신축 아파트 사전점검 기록을 블록체인으로 봉인하고, 하자담보기간 10년 동안 관리하는 서비스의 웹사이트입니다.

- 정적 HTML 6페이지 + 공용 CSS (`assets/styles.css`) — 빌드 없이 그대로 배포
- `index.html` 홈 · `about.html` 회사소개 · `technology.html` 기술 · `careers.html` 채용 · `terms.html` 이용약관 · `privacy.html` 개인정보처리방침
- 디자인 토큰: 딥그린 `#0E3B2E` · 민트 `#2FD3A0` · 페이퍼 `#F6F6F1`
- 반응형 (데스크톱 / 태블릿 / 모바일)

## 로컬에서 보기

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## 배포

### GitHub Pages
1. 저장소 `augxmas/muon` → Settings → Pages
2. Source: `Deploy from a branch` → Branch: `main` / `/ (root)`
3. 공개 주소: `https://augxmas.github.io/muon/`

`.nojekyll` 파일이 포함되어 있어 `_` 로 시작하는 경로도 그대로 서빙됩니다.

### Cloudflare Pages / Netlify
저장소를 연결하거나, 폴더를 그대로 드래그해 배포합니다. 빌드 명령 없음, 출력 디렉터리는 루트.

## 수정이 필요한 값

대괄호로 표시된 항목은 실제 정보로 교체해야 합니다. 확정 전까지는 초안 상태로 공개하지 않는 것을 권합니다.

| 값 | 위치 |
|---|---|
| `[이메일 주소]` | 전 페이지 푸터, about, careers, technology, terms, privacy |
| `[등록 후 기재]` | 전 페이지 푸터 (사업자등록번호) |
| `[사업장 주소]` | 전 페이지 푸터, about, terms, privacy |
| `[2027. 1. 1.]` / `[개정일]` | terms, privacy 시행일 |
| `[책임자 성명]` 등 | privacy 개인정보 보호책임자 |
| `[클라우드 사업자]` / `[결제대행사]` | privacy 위탁 업체 |

## 라이선스

© 2026 MUON Inc. All rights reserved.
