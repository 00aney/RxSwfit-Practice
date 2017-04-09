Observables and Subjects Practice
================================= 
non Rx code 에서 Rx 코드 적용해보기 

정리
---
- 이미지가 추가될 때마다 preview.image 변경
- 이미지가 추가될 때마다 UI 업데이트
- add(+) 버튼을 눌렀을 때, delegate protocol 을 쓰지말고, Observable 사용해서 메세지 주고 받기
- 포토 라이브러리 뷰 컨트롤러에서 subject 로 next 이벤트로 이미지 넘기기
- 메인 뷰 컨트롤러에서 subscribe 하여 이미지 추가
- 메인 뷰 컨트롤러는 현재 release 안되므로 dispose bag 도 release 안한다.
- 일반 함수를 Rx에서 쓰기 위해 wrapping 하여 Custom Observable 생성 



TODO
----
- viewDidLoad() 에 있는 observable 을 빼내서, MVVM 으로 바꿔 보기 



LICENSE
-------
<b>Right</b>

All rights property of raywenderlich.com/Razeware LLC.
