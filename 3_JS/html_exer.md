자손 선택자
div span { }
//공백으로만 구분하면 됨
//모든 자손이 바뀜
=============================
자식 선택자
div > span { }
//자식만 바뀜
=============================
인접 형제 선택자
div + span { }
=============================
가상 클래스
: 미리 정의해놓은 상황에 적용이 되도록 약속되어있는 보이지 않는 클래스
//앞에다가 콜론을 넣으면 됨

=============================
문서 구조와 관련된 가상 클래스
	:first-child : 첫 번째 자식 요소 선택
	:last-child : 마지막 자식 요소 선택
//가상의 클래스가 들어간다고 생각하면 됨
=============================
링크 관련된 가상 클래스
	:link : 하이퍼링크이면서 아직 방문하지 않은 앵커
	:visited : 이미 방문한 하이퍼링크를 의미

사용자 동작 관련 가상 클래스
	:focus : 현재 입력 포커스를 갖고 있는 요소에 적용
//tab키를 눌러서 사용
	:hover : 마우스 포인터가 위치해 있는 요소에 적용
	:active : 사용자 입력에 의해 활성화된 요소에 적용
=============================
가상 요소
: 미리 정의해놓은 위치에 삽입이 되도록 약속되어있는 보이지 않는 요소
	:before : 가장 앞에 요소를 삽입
	:after : 가장 뒤에 요소를 삽입
	:first-line : 요소의 첫 번째 줄에 있는 텍스트
	:first-letter : 블록 레벨 요소의 첫 번째 문자
=============================
상속
	박스 모델 관련 속성들은 상속되지 않는다.
	상속된 값은 아무런 구체성을 가지지 않으며, 심지어 0,0,0,0도 아니다.
=============================
캐스케이드 규칙
1.	중요도(!important) & 출처
2.	구체성
3.	선언순서
