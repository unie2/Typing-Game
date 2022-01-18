## 타이핑 게임

### 실행 화면

| 초기 화면 | 게임 시작 시 | 단어 일치 시(점수 증가) |
|:--------|:--------:|:--------:|
| ![초기 화면](https://user-images.githubusercontent.com/54324782/149871977-0d641a10-4ae2-4747-a559-5f78c8b2b9d1.png) | ![게임 시작](https://user-images.githubusercontent.com/54324782/149872033-336a4bf7-ccf6-427e-92d9-8c24f0849d35.png) | ![점수획득](https://user-images.githubusercontent.com/54324782/149872078-af71ef13-fb95-44f2-968a-c01c33458933.png)

### 시스템 기능

- 게임시작
- 상태 체크 (게임 중인지)
- 단어 불러오기
- 단어 일치 여부 및 획득 점수 증가
- 남은 시간 갱신
- 게임시작 버튼 클릭 시 loading 처리 해제

### 추가

- 랜덤한 단어들을 가져오기 위해 [Random Word API](https://random-word-api.herokuapp.com/home) 사용
- 단어들을 가져와 배열에 넣어주기 위해 [Axios](https://github.com/axios/axios) 사용
