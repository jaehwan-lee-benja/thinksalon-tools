# webtool — 생각살롱 온라인 툴 (P3)

공식 6종 양식의 인터랙티브 웹툴. 자기완결 정적 HTML(CDN 없음·SVG 자체구현), GitHub Pages 배포.

## 현황 (Wave 1 착수)
- ✅ **my-triangle.html — 마이삼각형** (T1, 키스톤·AI상담사 진단 UI)
  - 나(지·덕·체) · 관계(감정객관화·과제분리·수평) · 일(본업·생업) · 중앙 가치축.
  - 1층(인간계·인본) / 2층(자연계·야생) 층위 토글.
  - **익명 로컬 저장(localStorage)** — 서버 전송 없음. thinksalon_app DB 클라우드 저장은 별도 유저 승인 후(마이그 게이트).

## 로드맵 (docs/PRODUCT-ROADMAP.md §P3)
- Wave1: T1 마이삼각형 → T2 라이프밸런스그래프
- Wave2: T4 돈물흐름 → T3 시간땅 / Wave3: T5 목표데일리 → T6 생각정리함

## 배포
- 공개 repo `jaehwan-lee-benja/thinksalon-tools` → https://jaehwan-lee-benja.github.io/thinksalon-tools/
- 배포 = `scripts/deploy-tools.sh` (정본=archive `webtool/`, 자기완결본 복사).

## 개념 정합 (계약)
- 개념 정의는 `concept/`(정독 루프 소유) read-only 인용. 도식은 `book/assets/concept/` 정본 1벌(P2 전자책과 공유).
- 개념→도구 매핑은 P4 AI상담사 도구추천의 소스(중복정의 금지).
