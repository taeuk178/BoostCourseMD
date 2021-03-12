# 5. Box Offiece
부스트코스에서 제공하는 API를 이용하여 영화정보를 나타내는 앱만들기


# 사용된 기술
- Swift5
- 영화 상세정보는 `Multiple Cell`로 구분하여 정보를 나타냄
- JSON형식의 API를 `URLSession`을 사용하여 `GET`, `POST` 구현
- `NotificationCenter`을 사용하여 RequestAPI와 송수신
- UI 작업은 `DispatchQueue`로 메인 스레드에서 동작
- `Alert`를 사용하여 알림기능 구현
- 닉네임작성후 리뷰작성시 `UserDefault`로 저장하여 다시 적을필요 없게 구현
