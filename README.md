# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)


# step3 - 자동차 경주 게임
## 기능 정의
* 자동차
    * 자동차 전진
      * 조건 : 0~9 랜덤 값을 구한 후 4 이상인 경우
    * 전진 횟수 누적
* 서비스
    * 자동차별 전진
* 화면
    * 자동차 대수, 반복 횟수 입력받음
    * 자동차 상태를 출력

# step4 - 자동차 경주 게임(우승자)
## 기능 정의
* 자동차
  - [x] 자동차의 이름을 설정
  - [x] 이름의 길이는 최대 5자로 제한
* 화면
  - [x] 자동차의 상태 출력 시 자동차의 이름도 함께 출력
  - [x] 자동차의 이름을 입력 받을 때 쉼표(,)로 구분
  - [x] 게임 완료 후(반복횟수 만큼 전진 후) 우승자(1명이상) 출력
## 피드백
  * 자동차 이름 검증 시 if 조건에 스트림 사용 지양(가독성 저하)
    - [x] 자동차 이름 검증 유틸 생성
    - [x] 자동차 이름 예외 클래스 생성
    - [x] 자동차 이름 검증 시 검증 유틸 사용
  * 특정 클래스의 책임 분리
    - [x] 우승자 선정 기능 분리
