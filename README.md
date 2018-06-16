# BALLS
BALLS는 마우스를 이용하여 공을 피하는 웹게임 입니다.
https://balls-testnet.herokuapp.com/ 에서 플레이가 가능합니다.<br/><br/>


## 사용법
BALLS를 위해서는 Chrome의 확장어플리케이션인 MetaMask를 설치하고, account에 로그인 되어 있어야 합니다.
> https://metamask.io/
현재는 Ropsten Test Net 에서만 사용이 가능합니다.<br/><br/>


## 앞으로의 방향
처음 업로드에서는 앱에서 contract 의 비중이 작습니다. 하지만 대략적인 흐름이 완성되었으니, 앞으로 앱에서 contract가 차지하는 부분의 비중을 키워갈 예정입니다.<br/>
그리고, 앞으로 변경될 세부 사항들은 아래와 같습니다.<br/>
- 현재 item을 얻기위해 얻어오는 랜덤값은 timestamp정보의 해시값을 얻어와서 만들게 됩니다. 이는 임시적인 랜덤값 생성방식이기에 수정할 예정입니다.
- item을 표기하는 방식을 시각적으로 보기좋게 수정할 예정입니다. 예를들어 'Ball Speed x 0.5' 는 'Ball Speed : Slow' 로, 'Ball Size x 2' 는 'Ball Size : Big' 으로 수정될 수 있습니다.
- 게임을 하는 유저의 정보를 계정단위로 저장시킬 예정입니다.
	- 계정의 정보에는 닉네임과 점수정보가 포함됩니다.
	- 그리고 이를 토대로 랭킹 시스템을 만들어 갈 것입니다.