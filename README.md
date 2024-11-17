# 🌷 타이타닉 데이터분석

#### 📌 프로젝트 기간: 2024.11.17

## 프로젝트 설명
타이타닉 생존율에 영향을 미치는 요인을 분석하고 해당 요인과 생존율 간의 상관관계 분석을 통해 어떤 의미가 있는지 분석한다.

## 분석 목적
1) 생존율과 관련된 요인 분석
2) 생존율과 관련된 해당 요인의 상관계수를 도출하여 데이터 시각화

## 기술 스택
- 개발 환경
1) 터미널
2) 주피터노트북

## 터미널 명령어
1) cd project
2) cd assignment
3) source .venv/bin/activate
4) jupyternotebook


## 데이터 분석 내용(생존율과 생존율에 영향을 끼치는 요인들을 중심으로 분석 진행)
- 전처리 후 데이터 시각화
![image](https://github.com/user-attachments/assets/b55561d6-5ddf-4854-be6f-37125b45995e)
- Pclass와 Fare에 대한 생존여부를 봤을 때 공통적으로 등급과 요금이 높을 경우, 사망자가 현저히 낮게 나타나며이를 통해 사회적 계급 간에 발생한 불균형에 대한 문제를 파악할 수 있음

![image](https://github.com/user-attachments/assets/6a9d71ad-b2a9-4286-a2cf-63fbb56d56f9)
- 성별에 따른 생존율은 여성이 높게 나타난다.

![image](https://github.com/user-attachments/assets/84d033bd-ccb9-4064-a4ca-e56780521bb9)
- 10-20대에서 생존율이 높게 나타난다. 이는 나이가 어릴수록 우선적으로 구조가 되었거나 상대적으로 신체적으로 유리한 20대의 경우 자신의 보호할 수 있는 능력이 고령자보다는 높기에 생존율이 높게 나타난다.
30대에서 높은 사망자가 발생하는데 이는 구조 참여로 인해 발생했을 가능성이 높다.
중장년층부터는 신체적 능력이 떨어지기에 나이가 높아질수록 사망자비율이 증가하는 것을 볼 수 있다.

![image](https://github.com/user-attachments/assets/add3dcde-ea35-40ac-a0c4-d0151526bc60)
-부모
: 부모와 자녀가 함께 승선을 하였을 경우 생존율이 높다. 이는 위험 상황에 대해 성인인 부모가 대처를 하며 구조에 적극적으로 활동하기에 생존율이 높게 나타난다. 또한 어린이와 여성이 있어 우선적으로 구조가 되었을 가능성이 크다.

형제자매
: 형제와 자매 수가 많을수록 생존율이 낮다. 이는 위험 상황에 대한 대처에 한계가 존재하며 한정된 구명보트로 인해 사망자 수가 높은 것을 볼 수 있다.

- 상관분석을 통한 히트맵으로 시각화
![image](https://github.com/user-attachments/assets/55eb51b1-7221-40b1-ba67-b34e78e4d157)
- 요인들 중 강한 양의 상관관계와 음의 상관관계를 가진 요인들 정리
- Fare와 Survived(양의 상관관계): 요금이 높을수록 생존율이 증가한다는 것을 의미한다.
- Pclass와 Survived(음의 상관관계): 1등석일 경우 생존 확률이 높지만 등급이 낮아질수록 사망자가 늘어난다.
  

