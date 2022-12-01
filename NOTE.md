# Compose Camp 2022 

> 과정 중 코드 랩에서 정리하고 싶은, 기억 하고 싶은 내용을 메모 합니다.

## [Compose의 기본 레이아웃](https://developer.android.com/codelabs/jetpack-compose-layouts?continue=https%3A%2F%2Fdeveloper.android.com%2Fcourses%2Fpathways%2Fjetpack-compose-for-android-developers-1%23codelab-https%3A%2F%2Fdeveloper.android.com%2Fcodelabs%2Fjetpack-compose-layouts#0)

- 컴포저블을 작성할 때는 수정자를 사용하여 다음을 합니다.
  - 컴포저블의 크기, 레이아웃, 동작, 모양 변경
  - 접근성 라벨과 같은 정보 추가
  - 사용자 입력 처리
  - 요소를 클릭 가능, 스크롤 가능, 드래그 가능 또는 확대/축소 가능하게 만드는 것과 같은 높은 수준의 상호작용 추가

- LazyRow의 하위 요소는 컴포저블이 아닙니다
  - 대신~! 컴포저블을 목록 항목으로 내보내는 item 및 items 와 같은 메서드를 제공하는 Lazy 목록 DSL을 사용합니다. 
    - DSL: Domain Spacific Language, 도메인 특화 언어
