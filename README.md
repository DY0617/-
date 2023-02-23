# Gomduri-Chart

1.	프로젝트 주제\
곰두리 차트는 뮤직 플레이리스트 성격을 띄는 서비스이다. 곰두리 차트는 다음과 같은 기능들을 제공한다.\
 -현재 곰두리 차트에 저장되어 있는 음악의 목록을 확인하는 기능.\
 -곰두리 차트에 원하는 음악을 추가하는 기능.\
 -현재 곰두리 차트에 저장되어 있는 음악 중 원하는 음악을 검색하는 기능.\
 -멜론, 지니, 벅스 차트로 이동해 음악을 들을 수 있는 기능.


2.	개발 내용 설명

![image](https://user-images.githubusercontent.com/79496557/220836453-1c30662f-92df-40b6-b6ca-16d539e7b8bb.png)
 
-곰두리 차트 home
위 화면은 곰두리 차트의 home 화면이다. 곰두리 밑의 곰두리 차트 하이퍼링크를 누르면 곰두리 차트 home으로 돌아온다. 음악목록 버튼을 클릭하면 현재 곰두리 차트에 저장 되어있는 음악의 목록을 출력한다. 음악추가 버튼을 클릭하면 곰두리 차트에 원하는 음악을 추가할 수 있다. 음악검색 버튼은 현재 곰두리 차트에 저장되어 있는 음악 중 원하는 음악을 검색할 수 있다. 또 멜론 차트 바로가기, 지니 차트 바로가기, 벅스 차트 바로가기 하이퍼링크를 누르면 각 사이트의 실시간 차트로 바로 이동할 수 있다.

![image](https://user-images.githubusercontent.com/79496557/220836483-89b78866-7c0b-4e76-a608-a3b5986b0e71.png)


곰두리 차트의 home에서 음악목록 버튼을 누를 경우 위의 화면으로 이동할 수 있다. 위 화면에서는 현재 저장 되어있는 음악 목록을 출력하는데, 각 노래의 id, 노래의 이름, 가수의 이름, 그리고 노래 장르 정보를 제공한다.

![image](https://user-images.githubusercontent.com/79496557/220836503-cffd02da-52b4-4491-baa4-5a0fd89c4f97.png)
 

곰두리 차트의 home에서 음악추가 버튼을 누를 경우 위의 화면으로 이동할 수 있다. 위 화면에서 노래 제목과, 가수, 장르를 입력한 후 추가 버튼을 누르면 입력 정보가 곰두리 차트의 목록에 추가되고, 취소를 누르면 현재 텍스트박스에 입력한 텍스트를 모두 지우는 기능을 가지고 있다.

 ![image](https://user-images.githubusercontent.com/79496557/220836635-d2e08366-d420-48c3-a705-4510e44f9e40.png)

 
노래 제목에는 분홍신, 가수에는 아이유, 장르에는 dance를 적어서 노래를 곰두리 차트 목록에 추가할 때의 화면이다. 정보를 입력한 후 추가 버튼을 누르면 음악 목록에서 아래와 같은 결과를 얻을 수 있게 된다.
 
![image](https://user-images.githubusercontent.com/79496557/220836656-02af2663-92a2-4f4c-8ea2-a65070572614.png)


위에 입력한 정보대로 새로운 음악이 곰두리 차트 목록에 추가된 것을 확인할 수 있다.

 ![image](https://user-images.githubusercontent.com/79496557/220836676-17d4e1b8-e8fc-4dba-891b-e89dc6d3d2e6.png)

 
곰두리 차트의 home에서 음악검색 버튼을 누르면 위 화면으로 이동할 수 있다. 위 화면에서 노래 제목이나, 가수나, 장르 중에서 찾고 싶은 정보를 입력하고 검색 버튼을 누르면 곰두리 차트의 음악 목록 중에서 해당 정보에 부합하는 음악을 출력한다. 노래 제목과 가수와 장르 중에서 복수 검색도 가능하다.
 
 ![image](https://user-images.githubusercontent.com/79496557/220836700-5ab2d8d7-37fc-4d9c-b986-10ad8c23de55.png)

 
위와 같이 곰두리 차트 목록 중에서 dance 장르만 검색하고 싶다면 위와 같이 장르에 dance를 입력 후 검색 버튼을 누르면 된다. 그러면 %dance% 장르에 맞는 음악들을 검색해 준다.
 
 ![image](https://user-images.githubusercontent.com/79496557/220836720-f273e20f-d8e6-49e9-8856-978a6c8f2b2e.png)


Home 화면에서 맨 밑의 멜론, 지니, 벅스 차트 하이퍼링크는 클릭하면 해당 사이트의 실시간 차트로 이동할 수 있다.
