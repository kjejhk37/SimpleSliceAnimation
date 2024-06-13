<h1>자바스크립트를 이용한 슬라이드 애니메이션</h1>

![슬라이드 예시](https://github.com/kjejhk37/SimpleSliceAnimation/assets/118964808/683ea3db-ff09-47f5-91d8-4400ff893c63)

<hr/>

<br/>

<h2>CreateSliceBox(widthLenght, heightLenght, mainDiv, autoMoveTime)</h2>

슬라이드 박스를 생성합니다. 
슬라이드 박스는 5개이상 만들 수 없도록 하였지만 CreateSliceBox의 if(sliceNum >=5)의 숫자를 늘리면 더 많이 만들수 있습니다.

<br/>

<b>widthLenght</b> : 슬라이드 박스를 포함하는 전체 박스의 가로크기 (px)단위, 실제 컨텐츠 박스의 크기는 이보다 작습니다.
<br/>
<b>heightLength</b> : 슬라이드 박스를 포함하는 전체 박스의 세로크기 (px)단위, 실제 컨텐츠 박스의 크기는 이보다 작습니다.
<br/>
<b>mainDiv</b> : 해당 슬라이드 박스를 포함하는 구간의 id입니다.
<br/>
<b>autoMoveTime</b> : 슬라이드 버튼을 클릭하지 않아도 자동으로 오른쪽으로 페이지를 넘기는 시간입니다. 입력하지 않으면 자동으로 페이지를 넘기지 않습니다.


<hr/>

<h2>AddSlice(BoxidNum)</h2>

컨텐츠 슬라이드의 페이지를 추가합니다.

<b>BoxidNum</b> : 원하는 슬라이드 박스의 idNum입니다. 처음으로 생성한 슬라이드에 추가하려면 0, 두번째는 1 ...방식으로 입력됩니다.
<br/>

<hr/>

<h2>RightMove(BoxidNum) / LeftMove(BoxidNum)</h2>

선택한 슬라이드의 컨텐츠 슬라이드를 오른쪽 또는 왼쪽으로 이동합니다.

<b>BoxidNum</b> : 원하는 슬라이드 박스의 idNum입니다. 처음으로 생성한 슬라이드에 추가하려면 0, 두번째는 1 ...방식으로 입력됩니다.
<br/>

<hr/>

<h2>SelectSliceMove(BoxidNum, SelectNum)</h2>

선택한 슬라이드의 컨텐츠 슬라이드를 보이도록 컨텐츠 슬라이드 위치를 조정합니다.

<b>BoxidNum</b> : 원하는 슬라이드 박스의 idNum입니다. 처음으로 생성한 슬라이드에 추가하려면 0, 두번째는 1 ...방식으로 입력됩니다.\
<br/>
<b>SelectNum</b> : 원하는 슬라이드 박스의 원하는 컨텐츠 번호를 입력합니다. 0번 슬라이드의 3번째 컨텐츠를 보고 싶다면 BoxidNum = 0, SelectNum = 2를 입력합니다.
<br/>

<hr/>

<h2>UpdateSelectSliceIconColor(BoxidNum)</h2>

선택한 슬라이드의 원형 버튼의 색을 업데이트 하는 기능

<b>BoxidNum</b> : 원하는 슬라이드 박스의 idNum입니다. 처음으로 생성한 슬라이드에 추가하려면 0, 두번째는 1 ...방식으로 입력됩니다.\
<br/>


