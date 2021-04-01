# 뒤집히는 Project Cards

## 프로젝트 소개
프로젝트를 간단하게 소개하는 프로젝트 카드 <br>
앞면에는 대표 이미지와 title을, 뒷면에는 간략한 설명을 작성한 카드로 <br>
Hover시 앞면에서 뒷면으로 뒤집히는 효과를 가짐

## 사용언어
- HTML
- CSS

## 구현 방법
- 앞면과 뒷면을 같은 위치에 놓는다.
- 처음 앞면은 rotateY(0deg) = 기본 상태로 위치시킨다.
- 뒷면은  rotateY(180deg) = 뒤집힌 상태로 위치시킨다.
- backface-visibility: hidden을 설정하여 뒤집히면 보이지 않도록한다.
- Hover시 뒷면과 앞면의 rotateY를 반대로 위치시킨다.
- transition과 perspective을 통해 자연스럽게 뒤집히도록 한다.

## 이미지 출처
- <a href="https://pixabay.com/ko/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=594090">Pixabay</a>로부터 입수된 <a href="https://pixabay.com/ko/users/startupstockphotos-690514/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=594090">StartupStockPhotos</a>님의 이미지 입니다.
- <a href="https://pixabay.com/ko/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2682641">Pixabay</a>로부터 입수된 <a href="https://pixabay.com/ko/users/pisauikan-4552082/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2682641">pisauikan</a>님의 이미지 입니다.
- <a href="https://pixabay.com/ko/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=793043">Pixabay</a>로부터 입수된 <a href="https://pixabay.com/ko/users/firmbee-663163/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=793043">Firmbee</a>님의 이미지 입니다.

## 완성본