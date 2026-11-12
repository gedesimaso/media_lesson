# K-PRINCESS 1차 테스트 숲 에셋

2026-11-11 1차 송출 테스트의 `build_test.py`에서 실제 사용된 `forest flythrough stylized gradient` 로직을 기준으로 재구성했습니다.

- `forest_base.svg`: 기본 숲 배경
- `forest_full_t10_0.svg`, `forest_full_t11_5.svg`: 실제 테스트 렌더 로직 기준 숲 정지 프레임
- `trees_sprite.svg`: 90개 나무를 `tree-01` ~ `tree-90` 개별 SVG symbol로 보존
- `manifest.json`: 각 나무의 원본 생성 파라미터

개별 사용 예:
`<svg viewBox="0 0 121 320"><use href="trees_sprite.svg#tree-01"/></svg>`

주의: 과거 대화에서 별도로 생성했을 수 있는 AI 나무 PNG 원본은 현재 파일 라이브러리에서 복구되지 않았습니다. 이 에셋은 실제 1차 테스트 영상에 사용된 렌더 코드를 기준으로 재구성한 것입니다.
