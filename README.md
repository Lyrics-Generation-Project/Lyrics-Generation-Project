# Idol Song Lyrics Generator

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xNO25-Knl2bR6HorrH7IhJRrCuKgDa6y?usp=sharing) 

👆 가사 생성 실행 코드(Open in Colab)

## ❗ 프로젝트 소개
- 목적: 세대별 아이돌 그룹 노래 가사 생성하기
- 기간: 2021.02.18 ~ 2021.03.11
- 팀원: 금지헌, 성유지, 이지현, 최정윤 <br>
<br>

## ❕ 사용 데이터셋
- 아이돌 그룹 음악 가사 <br>
- 출처: https://github.com/BLUENCE/M5_Idol_lyrics/tree/master/Data
<br>

## ❕ 프로젝트 진행 일정  

|   주차   |   일정   |   내용   |   과제 및 논의   |   코드   |
|:----------------------------|:----------------------------:|:--------------------:|:-------------------:|:-----------------:|
|  1주차  | 2021.02.22 | 데이터 전처리 | 토큰화, 벡터화 방식 고민 | |
|  2주차  | 2021.02.25 | 어텐션, 트렌스포머 모델 적용 | 훈련 시간 대비 성능이 좋지 않음, <br> 어떤 pre-trained 모델을 적용해볼 것인지 | |
|  3주차  | 2021.03.01 | GPT 모델 공부 및 적용 | 줄바꿈, special token의 문제 | | 
|  4주차  | 2021.03.04 | 세대별로 GPT fine-tuning, <br> 첫 소절 넣어서 가사 생성하기 | LDA, TF-IDF 방식을 이용한 세대별 키워드 도출 | |
|  5주차  | 2021.03.11 | 최종발표 | | [PPT](https://github.com/Lyrics-Generation-Project/Song-Lyrics-Generator/blob/433a7e94e832ce998744ed380b685f1c20fa6200/3.%20Slides/%E1%84%89%E1%85%A6%E1%84%83%E1%85%A2%E1%84%87%E1%85%A7%E1%86%AF_KPOP_%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1_%E1%84%89%E1%85%A2%E1%86%BC%E1%84%89%E1%85%A5%E1%86%BC_%E1%84%91%E1%85%B3%E1%84%85%E1%85%A9%E1%84%8C%E1%85%A6%E1%86%A8%E1%84%90%E1%85%B3_PPT.pdf) | 

## ❕ 가사 생성 예시 

![1세대](https://user-images.githubusercontent.com/71932401/146671973-a4cb1162-ea6e-4653-bcec-e0c12df7b23f.jpg)

![2세대](https://user-images.githubusercontent.com/71932401/146671993-848c0e97-c2ec-496d-b54b-a843590e50c8.jpg)

![3세대](https://user-images.githubusercontent.com/71932401/146672014-29b03012-62aa-4718-a481-58b70e117475.jpg)
