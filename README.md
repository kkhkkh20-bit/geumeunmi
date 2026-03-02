# 금은미 시뮬레이터

소잇 금은미 이벤트 가격 시뮬레이터입니다.

## 기능
- 14K 주얼리 무게 입력 → 소잇 판매가, 금 소매가, 50%P 적용 현금 자동 계산
- 금시세 자동 조회 (국제 금시세 + 환율 기반)
- 시중 금은방 대비 절약 금액 표시
- 페이백 10% 자동 적용

## 금시세 API
- 1차: [freegoldapi.com](https://freegoldapi.com) (무료, API키 불필요, CORS 지원)
- 환율: [open.er-api.com](https://open.er-api.com) (무료)
- 폴백: URL 파라미터 `?don=1040000` 으로 수동 설정

## 사용법
- 기본: `index.html` 열기
- 제품별 링크: `?g=1.07` (그램수 자동 입력)
- 금시세 수동: `?don=1100000` (24K 1돈 살때 가격)
- 조합: `?g=1.07&don=1100000`

## 배포
GitHub Pages에서 자동 호스팅됩니다.
Settings → Pages → Source: main branch 선택
