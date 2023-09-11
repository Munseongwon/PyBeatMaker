# PyBeatMaker
### Let's Breakout the block!!!
<img src="start.png" alt="Intro Screen" width="200px" height="400px"><img src="playing.png" alt="game playing" width="200px" height="400px"><img src="game_over.png" alt="Game_Over Screen" width="200px" height="400px">

## 프로젝트 요약
![Langauge:Python](https://img.shields.io/badge/Language-Python-purple) ![platform:PyGame](https://img.shields.io/badge/Platform-PyGame-pink)
> 2022.01.03 - 2022.01.08 
 
> **Python 팀 프로젝트(게임 화면 디자인1 게임 개발1)**
* 브레이크 아웃 게임을 하면서 벽돌을 깨는 요소가 핀볼 뿐만 아니라 미사일로 설정하면 어떨까 하는 생각에 개발
* PyGame Package를 활용하여 제작
* 게임 화면창의 크기는 1280 * 720으로 설정
* 벽돌 상하좌우 양 사이드 표면, 게임 객체, 세팅 요소로 구성
<br>

> **게임 로직 설명**
* 처음 게임 시작하면 플레이어 벽돌, 핀볼은 정중앙에 위치
* 핀볼은 지그재그, 직선 방향으로 랜덤하게 이동하여 벽돌을 맞춤
* 벽돌을 깰 때마다 아래로 등장하는 아이템의 종류에 따라 요소 달라짐
  * 미사일 아이템: 미사일 개수 1 증가
  * 하트 아이템: 목숨 개수 1 증가
  * 사각형 아이템: 바 길이 증가
* 공을 한 개씩 놓치게 되면 하트 개수 1 감소
* 만일 하트의 개수가 0이 되면 그 즉시 게임 종료
<br>

## 시연영상
https://youtu.be/hp4EnCOG29w

