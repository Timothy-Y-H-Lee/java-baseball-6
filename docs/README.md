# 기능목록

1. '.gitignore' 내용 수정
> - '[작년 프리코스 1주 차] 웹 백엔드 피드백' 반영 : "git을 통해 관리할 자원에 대해서도 고려한다"

2. TDD 작성 처럼, 먼저 테스트를 통과하도록 임시 코드 작성
> - '게임종료_후_재시작' Test case @Disabled 시키기
> - '예외_테스트' Test case 통과시키기

3. 상수 정의
> - 문제에 포함된 '게임종료_후_재시작' Test case에 있는 문자열을 포함한 출력용 문자열 상수들 작성

4. MVC 형태로 코드 작성
> - 4.1. Repository 관련 코드 작성
>> - 야구 게임에 사용될 랜덤 숫자 3개를 생성
>> - 야구 게임에 사용될 랜덤 숫자 3개를 Repository에 저장
>> - 3개의 숫자를 저장할 때, Set을 이용하여 중복된 숫자가 저장되지 않도록 처리
> - 4.2. 나머지 Service, Controller 작성

5. 입력
> - 게임 참여자의 숫자 입력을 요청하는 문구 출력
> - 게임 참여자로부터 숫자 3개를 입력받아서 유효성 검증
> - '예외_테스트' Test case 제대로 통과시키기
> - 게임 참여자가 입력한 숫자 3개를 저장

6. 게임 진행 처리
> - 게임 참여자가 입력한 값과 컴퓨터가 랜덤하게 생성한 값을 서로 비교
> - 게임 결과를 출력
> - 게임 재시작 또는 종료