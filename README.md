# Into-The-Emerald-Dream

HSdeck schema 1 카드 API입니다. 최초 추가 날짜의 스펙은 `data/<카드ID>.json`의 `card`에 적고, 이후 패치는 `card.patches`에 **변경한 필드만** 저장했습니다. 날짜는 한국 시간(Asia/Seoul)입니다.

- `cards.json`: 현재 카드 스펙 및 기존 원화 URL
- `render.json`: 현재 스펙 + 과거 날짜별 차이값
- `history.json`: 구버전 플러그인 호환
- `release-policy.json`: 본 세트, 미니세트, 선행 배포 카드 날짜

최초 값 중 공식 패치로 확인하지 못한 내용은 `card.initialSpecStatus`를 통해 잠정으로 표시합니다. **기존 art/golden 원화 및 황금 애니메이션은 그대로 보존했습니다.**
