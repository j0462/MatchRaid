# 프로젝트명: Match&Raid (개발자: 이상헌)


# [목차]


## [1.컨셉](#컨셉)
## [2.관련이미지 & 동영상](#관련-이미지--동영상)
## [3.구성요소](#구성-요소)
## [4.게임시스템디자인](#게임시스템디자인)
## [5.개발 요구사항 & 흐름도](#개발-요구사항--흐름도)
## [6.프로토타입 개발 요구사항](#프로토타입-개발-요구사항)
## [7.프로토타입 개발작업 일정](#프로토타입-개발작업-일정)

# [컨셉]

## Project

### 1. Name
- 영문명 : Match&Raid
- 한글명 : 매치&레이드

### 2. Genre : Puzzle Game

### 3. No. of Players : 1

### 4. Main Target : 40~
- 40대 이상의 중장년 층

## Game Personality
- 게임의 기본적인 진행 방식은 퍼즐이다.
- 제한시간이 있는 타임어택 방식이다.
- 적을 잡느냐로 결과가 나타난다.
- 적을 못 잡아도 입힌 피해량에 비례하여 보상을 준다.
- 플레이 방식이 매우 간단하여 즐기기 편하다.
- 한 판당 60초를 소모한다.
- 한 판 플레이할 때마다 재화를 사용한다.

## Rule Summary
- 플레이어는 퍼즐을 맞춤으로서 적을 공격하여 쓰러트리는 것이 목적이다.
- 한번에 클리어하는게 아닌 여러번 반복하는 게임이다.
- 게임의 결과로 얻은 재화로 플레이어를 강화하여 보다 쉽게 클리어 가능하다.

## User Interface
- 모바일에서 작동하는 게임으로 게임의 우측 상단에 옵션 버튼이 존재하며 이를 통해 음량 조절이 가능하다.
- 기본적인 조작은 손가락 터치픞 사용하며 퍼즐을 맞출때는 슬라이드를 사용한다.
- 화면 좌우로 스테이지를 오갈수 있는 버튼이 존재하며 중앙 하단에 플레이 버튼이 존재한다.
- 좌측 상단에는 입장에 사용하는 재화가 있고 바로 오른쪽에는 골드라는 플레이어를 강화할 때 사용되는 재화가 있다.
- 스테이지 내에서 중앙 상단에 타이머가 존재한다.

## Graphic

### Graphic Concept
- 판타지 세계같은 분위기
- 던전이라는 표현이 어울리도록 인적이 드물어 보이는 배경

### Theme
- 골렘의 사원(메이플스토리)
- motive : 넝쿨로 뒤덮인 사원을 지키는 골렘들
- 무언가를 지키고 있는 것처럼 보이는 골렘들
- 덩쿨, 사원

### Character
- 모험가의 특징이 나타나는 캐릭터
- 캐쥬얼 느낌이 나도록 SD방식을 사용한다.
- 판타지 장르에 나오는 여러 모헌가 직업들을 사용한다.

### Puzzle
- 5가지의 색으로 표현한다.
- 각 색마다 매칭시 효과가 다르다.
- 최대한 많이 매치하는 것이 좋다.

## Sound

### Sound Concept

#### BGM, Game Play : 기본 배경음, 게임 진행중
- 모험에 걸맞는 밝은 분위기
- 가벼운 분위기
- 소리에 공백이 없도록 루프진행

#### Stage Select, Room Select : 스테이지 선택룸
- 캐쥬얼 분위기의 음악
- 소리의 공백이 없도록 루프진행

## 메인컨셉 : 돌파

- 여러 스테이지로 구성되어 있기에 이 스테이지들을 돌파 한다는 컨셉

### 서브 컨셉 1 : 레이드

- 어떤 방식으로 스테이지를 돌파 할 것인가에 대한 것으로 보스를 잡는 레이드 방식을 추가하여


  스테이지 클리어 조건이 보다 명확하게 한다

### 서브 컨셉 2 : 수단

- 보스를 공격할 방법으로 매치3 퍼즐을 풀때마다 대응하는 캐릭터가 공격하는 방식이다

### 서브 컨셉 3 : 성장

- 보다 보스를 쉽게 잡기 위한 방법으로 게임내 재화로 캐릭터의 공격력 등을 강화한다

### 서브 컨셉 4 : 한계

- 스테이지에 제한 시간을 만들어 스테이지 간의 한계를 재현함으로


  한계의 허들을 낮추는 방안이 위에서 언급한 성장이다

### 서브 컨셉 5 : 기회

- 무한정의 도전은 지루하게 만들기 때문에 도전할 기회를 제한한다


  스테이지 도전시 고유재화 1개 소모 재충전에 5분 최대 5개 보유가능하다

<br><br>

# [관련 이미지 & 동영상]


- 동영상  


  1) ![image](https://user-images.githubusercontent.com/70842040/191636596-23273401-e18c-49fd-a3cc-a780525bfcab.png)

      https://youtu.be/5o6VAGX0tcg
  
  2) ![image](https://user-images.githubusercontent.com/70842040/191636639-5c74a618-89cc-422f-a55a-cd3a9b308950.png)

      https://youtu.be/sFbjnJoPRPs

<br><br>

# [대표 이미지]

![image](https://user-images.githubusercontent.com/70842040/191635332-1f2a38d0-6a5a-4987-9d04-28a445d5925b.png)

<br><br>

# [컨셉 & 대표이미지 기반 작품묘사]

> ### 대표이미지 기반 : 캐릭터들이 보스를 잡는 매치3 퍼즐 게임

> ### 컨셉 기반: 스테이지 돌파로 자신의 한계에 도전하는 매치3 퍼즐 게임

<br><br>

# [구성 요소]

<br>

## 1. 메커니즘

[도전 과제]

1) 보스를 잡는다.

2) 제한 시간 내에 보스를 잡는다. 

3) 몇 번의 공격 내에 보스를 잡는다.

4) 일정 스테이지까지 도달한다.

[재미 요소]

1) 플레이어가 퍼즐을 품으로서 캐릭터가 공격한다.

2) 스테이지가 넘어 갈 수록 보스의 체력이 높아진다.

3) 보다 강한 공격을 하기 위해 3x3등을 이용한다.

<br>

## 2. 이야기

[만들게 된 배경]  


경험을 기반으로 주변 지인들 중 특히 30대가 넘어가는 경우


최근에 출시되는 게임을 적응하기 어려워하며 반사신경이 점차 떨어지면서


실시간 경쟁게임은 부적합하다 느끼고 방치형, 시뮬레이션 게임에는 재미를 못 느끼시기에 


반사신경과는 무관한 매치3퍼즐 방식을 채택한 게임을 제작하였다. 

[카메라 관점]  
2d 게임으로 진행 상황을 한눈에 잘 보이도록


카메라의 하단 부분에 퍼즐, 상단 부분에는 캐릭터와 보스가 배치되어있다.

<br>

## 3. 미적요소

[디자인][컬러]  


보스레이드의 캐릭터는 sd형태로 제작하며


캐릭터 아이콘과 고유색깔을 배치하여 퍼즐과의 관계를 보다 직관적으로 한다.


보스는 골렘의 형태이기에 주 배경은 유적지나 숲으로 한다.


색맹의 경우에도 플레이의 지장이 없도록 퍼즐의 색깔에 따라 디자인을 다르게 한다.





[음향]  


너무 다채로운 음향은 귀에 부담이 가기 때문에


배경음은 어느 정도 활발하되 보스레이드의 타격음이 지나치지 않도록 한다.


메뉴에서 옵션으로 음량 조절 기능을 만들어 배경음, 효과음, 타격음 3가지로 분리후


각기 음량을 조절 할 수 있도록 한다.
<br>


## 4. 기술

Unity를 기반으로 모바일 플랫폼으로 개발하며


매칭3퍼즐 코드를 보스레이드와 연동하여


퍼즐을 맞출 시 보스레이드에 영향을 주는 식으로 개발할 것이다.






# [게임시스템디자인]

## a. 게임 오브젝트

|번호|명칭|이미지|
|----|----|-----|
|1|메인메뉴|![image](https://user-images.githubusercontent.com/70842040/196700671-132c43e5-0c3f-460f-b8a7-d3e4eec93572.png)|
|2|스테이지 락, 언락|![image](https://user-images.githubusercontent.com/70842040/196700719-f007d476-14b4-4e43-bbdc-538bab2478ad.png)|
|3|스테이지 시작|![image](https://user-images.githubusercontent.com/70842040/196700762-442a56b9-ccb7-456a-bbff-993cd0c153bc.png)|
|4|흑마법사-헥센|![image](https://user-images.githubusercontent.com/70842040/196698679-d9680360-7920-41fc-b14e-2475102a66e9.png)|
|5|흑마법|![image](https://user-images.githubusercontent.com/70842040/196698735-a8c09c5a-4356-4392-b19f-3d4f86c1da26.png)|
|6|마법사-마기|![image](https://user-images.githubusercontent.com/70842040/196698812-92102857-3234-4802-97b5-18f1ce83ff9a.png)|
|7|마법|![image](https://user-images.githubusercontent.com/70842040/196698872-129a4f0b-4f2f-4e83-9c76-9b7ec862c3ad.png)|
|8|기사-크리거|![image](https://user-images.githubusercontent.com/70842040/196698931-70fdecae-71d2-4104-98b2-54c76206677e.png)|
|9|레이피어|![image](https://user-images.githubusercontent.com/70842040/196698983-56d702e4-c77e-42af-82bc-d5119f6297f4.png)|
|10|궁수-보겐|![image](https://user-images.githubusercontent.com/70842040/196699042-6d6e83b3-614a-41d7-bf53-b8583e14a137.png)|
|11|화살|![image](https://user-images.githubusercontent.com/70842040/196699113-bfa34412-ed6f-4508-8d75-df8b4c806198.png)|
|12|골렘|![image](https://user-images.githubusercontent.com/70842040/196699163-f9028ec5-0130-4dcd-a646-51d9c34054c7.png)|
|13|골렘의 hp|![image](https://user-images.githubusercontent.com/70842040/196699216-b93aeab9-b122-499b-b2ea-36c1feadb977.png)|
|14|타이머|![image](https://user-images.githubusercontent.com/70842040/196699276-ed51c8ef-0c6b-43f0-ba58-bc44ff201c1a.png)|
|15|클리어|![image](https://user-images.githubusercontent.com/70842040/196699326-c46250e8-eaec-418d-aa92-5129d939bc0b.png)|
|16|나가기, 다시하기, 다음스테이지|![image](https://user-images.githubusercontent.com/70842040/196699401-2168a9c4-ad4c-46ab-861d-a94c240bfbac.png)|
|17|실패|![image](https://user-images.githubusercontent.com/70842040/196699447-ac9acc16-9ccf-424d-b1a9-81ac37840eef.png)|
|18|배경-숲속|![image](https://user-images.githubusercontent.com/70842040/196699502-103888aa-e247-48c2-9d6c-6ad246b6f8f5.png)|
|19|배경-동굴|![image](https://user-images.githubusercontent.com/70842040/196699547-f1a9a5ec-38be-404f-935b-2d0c1a63e547.png)|
|20|재화-골드|![image](https://user-images.githubusercontent.com/70842040/196699605-24439d1f-bd0b-4ff9-818a-2736d68e950c.png)|
|21|퍼즐-토큰|![image](https://user-images.githubusercontent.com/70842040/196699664-6a0b57c0-3627-4df6-a1dd-f6cc35daccd4.png)|
|22|토큰1|![image](https://user-images.githubusercontent.com/70842040/196699708-528dcec1-67e3-456d-8f7e-647483e41b1f.png)|
|23|토큰2|![image](https://user-images.githubusercontent.com/70842040/196699775-a4858064-45ca-4a41-a738-ce402bdd1328.png)|
|24|토큰3|![image](https://user-images.githubusercontent.com/70842040/196699814-aaf0a86c-6313-44fb-8836-945a86e7927b.png)|
|25|토큰4|![image](https://user-images.githubusercontent.com/70842040/196699843-2a3fab06-63c5-42a5-b8ce-fcdc739a0a4d.png)|
|26|토큰5|![image](https://user-images.githubusercontent.com/70842040/196699887-ab1db890-0541-4a52-b907-76170eacb0a2.png)|
|27|플레이기회-|![image](https://user-images.githubusercontent.com/70842040/196699917-c822b533-87a4-4c40-ac4c-07f1db632303.png)|



## b. 파라미터(속성)
1) Hero

|속성|영문명칭|설명|비고|
|-------|-----|-----|----|
|공격력|Hero_dmg|각 영웅들의 고유 공격력|직업 간 차이가 존재|
|상태|Hero_status|각 영웅들이 조건에 따른 대기-공격 상태를 오간다| |
|치명타확률|Hero_critper|각 영웅들이 가지고 있는 공격시 추가 데미지가 발생할 고유 확률|직업 간 차이가 존재|
|치명타데미지|Hero_critdmg|각 영웅들의 치명타가 발생 했을시 추가 되는 데미지|직업 간 차이가 존재|
|업그레이드비용|Hero_upgradecost|각 영웅들의 공격력, 치명타확률, 치명타데미지의 수리를 올릴 수 있다|직업 간 차이가 존재|


2) Golem

|속성|영문명칭|설명|비고|
|-------|-----|-----|----|
|체력|Hp|오브젝트가 가지고 있는 고유체력|스테이지 별 체력 차이가 존재|
|체력바|Hp_bar|오브젝트의 체력을 구체적인 수치가 아닌 추상적인 수치로 표시한다| |


3) 메뉴

|속성|영문명칭|설명|비고|
|-------|-----|-----|----|
|잠시멈춤|Option_Pause|게임도중 일시적으로 멈춤||
|나가기|Option_Exit|게임도중 게임을 포기하고 나감|플레이 기회 소진|
|음량조절|Option_Sound|게임도중 Bgm이나 효과음을 조절||
|계속하기|Option_Continue|계속 게임을 이어나감||

4) 배경

|속성|영문명칭|설명|비고|
|-------|-----|-----|----|
|1번 배경|Background1|첫 번째 배경으로 숲속이다|밝고 평온함|
|2번 배경|Background2|두 번째 배경으로 동굴 속이다|어둡고 고요함|

## c.행동

1) 영웅

|행동|영문명칭|설명|
|-------|-----|-----|
|대기|Wait|평상시 상태|
|공격|Attack|조건을 만족할시 공격을 함|
|클리어 포즈|Clear_pose|클리어시 화면 중앙으로 나란히 정렬함|
|실패 포즈|Fail_pose|실패시 뒤로 넘어지며 사라짐|

2) 퍼즐토큰

|행동|영문명칭|설명|
|-------|-----|-----|
|위로 이동|Up|오브젝트를 손으로 위로 슬라이드시 위로 이동|
|아래로 이동|Down|오브젝트를 손으로 아래로 슬라이드시 아래로 이동|
|왼쪽으로 이동|Left|오브젝트를 손으로 왼쪽으로 슬라이드시 왼쪽으로 이동|
|오른쪽으로 이동|Right|오브젝트를 손으로 오른쪽으로 슬라이드시 오른쪽으로 이동|
|매칭되어 소멸|Match_clear|오브젝트가 조건을 만족할시 소멸함|
|재소환|Respawn|오브젝트가 소멸되어 빈공간이 발생시 위에서부터 차례대로 채운다|
|재배치|Replace|오브젝트가 조건을 만족할 수 없는 상태라 판단되면 오브젝트가 재배치 된다|

## d. 상태

1) 영웅

|현상태|전이상태|전이조건|
|-------|-----|-----|
|대기|공격|퍼즐토큰 소멸시|
|공격|대기|공격완료시|
|대기|클리어 포즈|골렘의 체력이 0이 될시|
|대기|실패 포즈|타이머의 시간이 0이 될시|

2) 퍼즐토큰

|현상태|전이상태|전이조건|
|-------|-----|-----|
|대기|위로 이동|손으로 위로 슬라이드시|
|대기|왼쪽으로 이동|손으로 왼쪽으로 슬라이드시|
|대기|오른쪽으로 이동|손으로 오른쪽으로 슬라이드시|
|대기|아래로 이동|손으로 아래로 슬라이드시|
|대기|소멸|퍼즐의 배열이 조건에 만족시|
|대기|재소환|퍼즐토큰이 소멸할시|
|대기|재배치|더 이상의 조건 만족을 위한 퍼즐의 배열이 없을시|


## e. 플레이어 캐릭터 속성(파라미터)

|속성|영문명칭|설명|비고|
|-------|-----|-----|----|
|흑마법사-헥센|Hexen|자색 복장의 어두운 느낌을 풍기는 남성으로 흑마법을 이용한 공격을 사용한다|공격력:1 치명타확률:5% 치명타데미지:300%|
|마법사-마기|Magi|청색 복장의 밝은 분위기를 띄우는 여성으로 일반마법을 이용한 공격을 사용한다|공격력:4 치명타확률:10% 치명타데미지200%|
|기사-크리거|Keurigeo|붉은 복장의 진중한 기사 느낌의 남성으로 한손장비인 레이피어를 주무기로 사용한다|공격력:2 치명타확률:20% 치명타데미지:150%|
|궁수-보겐|Bogen|녹색 복장을 한 소심해 보이는 엘프 여성으로 활을 이용한 원거리 공격을 한다|공격력:3 치명타확률:30% 치명타데미지:100%|


## f. 게임의 규칙

### 1) 핵심 규칙

같은 모양의 퍼즐을 일정한 모양으로 배치시 해당 오브젝트가

소멸하고 해당 오브젝트가 가지고 있는 기믹이 발생한다.

예시)

토큰을 ㅁ,ㄴ,ㅇ 이라 가정

ㅁㅁㅇ       ▶         ㅁㄴㅇ        ▶        ㅁㄴㅇ

ㅁㄴㅁ&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ㅁㅁㅁ        

각 퍼즐토큰의 색은 영웅의 색이랑 매칭되며

해당 토큰이 소멸할 경우 토큰의 색에 해당하는 영웅이 공격하는 기믹이

발생한다. 이때 영웅은 한번 공격하며 데미지는 아래의 데미지공식을 따른다.


### 2) 보조 규칙

영웅들이 골렘을 공격하여 제한시간 이내에

토벌을 하면 클리어이다. 골렘은 공격하지 않고 가만히 존재하며

HP가 존재한다. 제한시간내에 모든 HP를 깍아내면 승리다.

## g. 게임에서 사용될 공식

데미지 공식

퍼즐계수 * 공격력 = 최종데미지

치명타 발생시

퍼즐계수*(공격력(1+치명타데미지/100)) = 최종데미지

치명타데미지의 기본값은 100%이고

퍼즐계수는 고유 값으로

매칭모양에 따라 정해진다.

예시)   

1번

ㅁㅁ                                       

ㅁㅁ = 2*2 = 4  

2번

ㅁㅁㅁ = 1*3 =3 


## 개발 요구사항 & 흐름도

### a. 요구사항
1. 시작화면, 스테이지선택 화면, 게임화면 총 3개 존재한다.
2. 시작화면에는 스테이지선택과 영웅강화, 옵션 총 3개의 버튼이 있다.
3. 스테이지선택 버튼 클릭시 스테이지선택 화면으로 이동한다.
4. 영웅강화 버튼을 누를시 영웅강화 UI가 올라온다.
5. 스테이지 선택 화면에는 시작하기와 나가기 버튼 2개 존재한다.
6. 게임화면 상단 우측에는 톱니 모양의 옵션 버튼이 존재한다.
7. 옵션 버튼에서는 음량조절이 가능하다.
8. 게임 플레이 기회를 상징하는 하트는 상단 왼쪽에 위치한다.
9. 하트는 5분에 하나씩 재생되며 최대 5개 저장이 가능하다.
10. 게임화면에서 퍼즐부분은 하단에 플레이어와 골렘은 상단에 위치한다.
11. 플레이어 캐릭터는 왼쪽, 골렘은 오른쪽에 위치한다.
12. 스테이지는 진행도에 따라 자물쇠표시를 이용하여 제한 표시를 한다.
13. 게임의 종료 조건은 골렘의 체력이 0이 되거나 타이머가 0이 될 경우다.
14. 타이머는 상단 중앙에 존재한다.
15. 게임화면에 실패든 클리어든 Ui가 중앙에 등장한다.
16. 클리어시 UI창에 클리어가 표시되고 다시하기, 나가기 2개의 버튼이 나온다.
17. 실패시 UI창에 실패가 표시되고 다시하기, 나가기 2개의 버튼이 나온다.
18. 스테이지 도중에 앱을 나갈시 하트는 소진되고 스테이지에서 나가진다.
19. 스테이지 진행 및 클리어시 얻게 되는 재화는 골드이며 상단 왼쪽, 하트 오른쪽에 보유량이 표기된다.
20. 퍼즐의 로직은 매치3를 따라간다.
21. 영웅의 행동이 퍼즐로직하고 연동된다.
22. 영웅 강화 UI에 업그레이드를 구현한다.

### b. 이벤트 흐름도
![image](https://user-images.githubusercontent.com/70842040/196438700-6bdb7bdf-ebd2-4c47-8e14-a60458290054.png)


# 프로토타입 개발 요구사항


## 1주차 - 게임의 전체적인 화면과 화면전환 구현

~~시작화면, 스테이지선택 화면, 게임화면 총 3개 존재한다.~~

~~시작화면에는 스테이지선택과 영웅강화, 옵션 총 3개의 버튼이 있다.~~

~~스테이지선택 버튼 클릭시 스테이지선택 화면으로 이동한다.~~

## 2주차 - 옵션 및 일부 버튼 UI구현

~~영웅강화 버튼을 누를시 영웅강화 UI가 올라온다.~~

~~게임화면 상단 우측에는 톱니 모양의 옵션 버튼이 존재한다.~~

~~옵션 버튼에서는 음량조절이 가능하다.~~

## 3주차 - 퍼즐 로직 구현, 게임플레이 화면의 구체적 구현

~~퍼즐의 로직은 매치3를 따라간다.~~

~~게임화면에서 퍼즐부분은 하단에 플레이어와 골렘은 상단에 위치한다.~~

~~플레이어 캐릭터는 왼쪽, 골렘은 오른쪽에 위치한다.~~

~~게임의 종료 조건은 골렘의 체력이 0이 되거나 타이머가 0이 될 경우다.~~

~~타이머는 상단 중앙에 존재한다.~~


## 4주차 - 추가적인 버튼, 스테이지 언락 시스템 구현

~~스테이지 선택 화면에는 시작하기와 나가기 버튼 2개 존재한다.~~

~~스테이지는 진행도에 따라 자물쇠표시를 이용하여 제한 표시를 한다.~~

## 5주차 - 영웅과 퍼즐의 연동 구현, 게임화면 결과창 UI 구현

~~영웅의 행동이 퍼즐로직하고 연동된다.~~

영웅 강화 UI에 업그레이드를 구현한다.

~~게임화면에 실패든 클리어든 Ui가 중앙에 등장한다.~~

~~클리어시 UI창에 클리어가 표시되고 다시하기, 나가기 2개의 버튼이 나온다.~~

~~실패시 UI창에 실패가 표시되고 다시하기, 나가기 2개의 버튼이 나온다.~~

## 6주차 - 재화 제작

~~스테이지 도중에 앱을 나갈시 하트는 소진되고 스테이지에서 나가진다.~~

~~스테이지 진행 및 클리어시 얻게 되는 재화는 골드이며 상단 왼쪽, 하트 오른쪽에 보유량이 표기된다.~~

~~게임 플레이 기회를 상징하는 하트는 상단 왼쪽에 위치한다.~~

~~하트는 5분에 하나씩 재생되며 최대 5개 저장이 가능하다.~~


# 프로토타입 개발작업 일정


## 1주차

~~타이틀, 스테이지, 게임화면 제작~~



## 2주차

~~영웅강화와 관령된 UI 및 옵션 창 제작~~

~~옵션창에서 음량조절 기능 제작~~

1 & 2주차 결과

<video width="50%" height="50%" controls="controls">
  <source src="./images/week/20221102_233838_Trim.mp4" type="video/mp4">
</video>


## 3주차

실제 플레이에서 사용될 게임의 로직 제작 -80%

~~타이머UI 제작~~

~~영웅, 적 유닛 배치~~


<video width="50%" height="50%" controls="controls">
  <source src="./images/week/20221109_222611.mp4" type="video/mp4">
</video>

## 4주차

~~스테이지 선택기능 구현~~

~~스테이지 언락시스템 구현~~

스크립트 로직 보완 -20%

<video width="50%" height="50%" controls="controls">
  <source src="./images/week/20221116_233058.mp4" type="video/mp4">
</video>

## 5주차

~~영웅 행동 매커니즘 제작~~

~~클리어UI, 실패UI제작~~

~~스크립트 로직보완, 버그수정~~

영웅 업그레이드 구현 - 0%

<video width="50%" height="50%" controls="controls">
  <source src="./images/week/20221123_234501.mp4" type="video/mp4">
</video>


## 6주차

골드 재화 제작 - 70%

~~플레이기회 재화 제작~~

영웅 업그레이드 구현 - 0%
