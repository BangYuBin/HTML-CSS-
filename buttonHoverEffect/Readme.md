# Button Hover Effect

## 프로젝트 소개
버튼 hover 시 테두리가 차례대로 채워지는 효과 구현

## 사용언어
- HTML
- CSS

## 구현 방법
- button : a 태그
- 테두리 : a태그 안에 4개의 span태그로 각 변을 구성
- span 태그마다 높이는 0으로 초기화하여 보이지 않게함<br> 
(방향에 따라 높이는 height이나 width)
- hover시 높이가 테두리 길이 만큼의 크기를 가지도록 구현
- trasition-delay를 사용하여 앞의 span태그들이 transition을 완료할때까지 기다림
- 첫번째 span태그부터 차례대로 transition하도록 구현

## 완성본
<img src="./완성본.gif">