# DonTouch-FE

## Git Convention

양식: ``Commit Type: 간단한 코드 설명 #number``
``ex) git commit -m “Feat: 회원가입 페이지 #12” ``

- feat : 새로운 기능 추가
- fix : 버그 수정
- docs : 문서 수정
- style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- refactor : 코드 리펙토링
- test : 테스트 코드, 리펙토링 테스트 코드 추가
- chore : 빌드 업무 수정, 패키지 매니저 수정


## Branch Convention (GitHub Flow)

- main: 배포 가능한 브랜치, 항상 배포 가능한 상태를 유지
- feature/이슈번호_기능설명: 새로운 기능을 개발하는 브랜치
  + 예: ``feature/#20_login``

## Flow
1. 새로운 이슈 생성.
2. main 브랜치에서 새로운 브랜치를 생성.
3. 작업을 완료하고 커밋 메시지에 맞게 커밋.
4. Pull Request를 생성 / 팀원들의 리뷰.
5. 리뷰가 완료되면 develop 브랜치로 병합.
6. 병합 후, 필요시 배포.


## 새로운 기능 개발
``git checkout -b feature/#20_login``

## 작업 완료 후, 본인 브랜치로 push
``git add .``

``git commit -m "Feat: 로그인 페이지 #20"``

``git push origin feature/#20_login``

## push 후, pull request & 코드리뷰 요청
