# Y_Cup

인하대학교 여의주배 축구대회 공개 페이지입니다.

## 배포

- GitHub Pages 기준으로 `index.html`과 `assets/` 폴더를 루트에 둡니다.
- 저장소 이름 추천: `Y_Cup`
- Pages 설정: `Deploy from a branch` -> `main` branch -> `/root`

## 운영

- 경기 제출 응답은 Google Sheet `Y_Cup`의 `제출_응답` 탭에서 확인합니다.
- 운영자는 한 경기당 최대 5개 제출을 비교한 뒤 `확정_결과` 탭에 최종 결과를 입력합니다.
- 확정 결과를 바탕으로 `index.html`의 `DATA.matches`와 `DATA.scorers`를 업데이트하면 공개 페이지의 순위, 브래킷, 득점자 현황이 갱신됩니다.

득점자 입력 예: `7, 10x2, 11`
