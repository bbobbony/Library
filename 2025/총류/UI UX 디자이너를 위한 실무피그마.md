# ⌈UI/UX 디자이너를 위한 실무피그마⌋ 클레어정
## "IT업계에 관심이 있다면 개발자, 디자이너, 기획자 상관없이 모두가 읽어야할 필독서!!!"

### Figma란?
#### Figma는 쉽게 말해 UI 도구 모음 웹이다. 얼핏보면 디자이너에게 국한되어보이지만 <br> 팀원연동기능, 프레임 코드변환기능, 동적인 상호작용 발표등 외에 수많은 기능이 내재되어 있다.

<br>

### ✅왜 피그마일까?
- 스케치 사용자가 작성한 스케치파일을 업로드하여 바로 작업가능
- 파일을 따로 저장할 필요없이 웹에서 즉시 디자인 가능
- 웹 기반이기에 어도비XD에 비래 업드이트가 빠름
- 다양한 협업기능 내재

<br>

### 🤔디자인하기 전 알아야하는 UI기술지식?
|용어|설명|
|--|--|
|스크린사이즈(Screen Size)|화면의 대각선 길이, 단위는 인치|
|해상도(resolution)|화면의 총 픽셀 수|
|ppi(pixels per inch)|화소밀도, 디스플레이에서 인치당 픽셀 수|   
|dpi(dots per inch)|픽셀밀도, 화면의 실제 영역 내에 있는 필셀 수|
|dp(density-independent pixels)|안드로이드 사이즈 단위, 화면 크기와 해상도가 달라도 레이아웃을 <br> 동일한 비율로 보여주기 위해 안드로이드에서 정의한 단위|
|sp(scale-independent pixels)|안드로이드 텍스트에서만 사용하는 단위, dp와 동일한 비율|
|pt(point)|iOS 사이즈 단위, dp와 같은 역할

<br>

-----------------------------------------------------------------------------------------------------------------------

<br>

### 1. 해상도와 화소밀도(PPi)
-> 화소밀도는 디스플레이에서 1인치에 들어가는 픽셀 수 이며 ppi로 나타낸다.
따라서 해상도와 ppi가 높을수록 이미지가 선명해진다.
![해상도에 따른 화소밀도](https://github.com/bbobbony/Images/blob/main/%EB%8F%84%EC%84%9C/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202025-06-04%20123233.png)

<br>

### 2. 픽셀밀도(DPi)
-> 픽셀밀도는 화면의 실제 영역 내에 있는 픽셀 수이며 dpi로 나타냅니다. 이 밀도는 화면상의 총 픽셀 수인 해상도와 다른 개념입니다.
다양한 디바이스에 디자인이 같은 비율로 보이도록 1x을 기본으로 디자인

<br>

### 3. 픽셀단위(DP, SP, PT)
-> 안드로이드와 iOS는 디자인 요소가 여러 디스플레이에서 같은 비율로 보일 수 있도록 독립된 단위를 사용합니다. <br>
단위를 px로 지정하면 디스플레이의 물리적 픽셀로 인식하며 화면별로 사이즈가 달라집니다. 이를 방지하기 위해서 <br>
논리적 픽셀단위인 dp를 사용합니다.


dp: 안드로이드 기본사이즈 단위 <br>
sp: 안드로이드 텍스트에서 사용하는 단위 <br>
pt: iOS 사이즈 단위로 dp와 동일 <br>
💫 iOS는 단위를 pt로 통일해서 사용, 모든 기기에서 디자인이 동일하게 보이는 1x사이즈에서 시작해서 2x 3x로 늘려서 대응 <br>
일러스트레이션 or 아이콘 같은 경우엔 벡터인 svg파일을 사용하여 적용시 어떤화면이든 깨지지않고 깨끗하게 출력 <br>

<br>

### 4. 8px그리드
디자인 에셋의 사이즈, 간격 및 모든 수치를 8단위로 맞추면 모든 디바이스에서 픽셀이 깨지지 않고 개발 친화적인 디자인 가능
8의 배수로 결정하는 것이 적합 단, 8의 배수로만 지다인하면 단위가 너무 크기 때문에 4, 2 단위도 사용

만약 5px 그리드라면 1배율일때는 문제 없지만 1.5배율이 되는 경우 끝이 깨지면서 흐릿한 현상이 발생
그러나 4px 그리드는 여전히 선명하다! 이것이 바로 디자인계에서 짝수 법칙

<br>

### 5. 마진과 패딩
마진: 한 컴포넌트의 외곽선을 기준으로 선과 다른 UI요소 사이의 간격
패딩: 컴포넌트 내에서 글자 혹은 아이콘끼리의 간격
> [!TIP]
> 크롬에 접속해 F12버튼을 눌러 '크롬 개발자 도구'를 확인해보자

<br>
<br>

#### F12 -> Element -> 스크롤

![개발자도구 Element 이미지](https://github.com/bbobbony/Images/blob/main/%EB%8F%84%EC%84%9C/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202025-06-04%20210856.png)

<br>
<br>



