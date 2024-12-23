# Japan_recommenation_chatbot
2024년 2학기, 비타민 14기, 추천시스템 1조 

# 1. 프로젝트명
LLM을 활용한 일본 여행 추천 프로젝트 

# 2. 프로젝트 소개
우리의 프로젝트는 사용자 맞춤형 추천 챗봇입니다.

이 챗봇은 사용자의 숨겨진 취향과 니즈를 파악하여 개인화된 가치를 제공합니다. 이를 통해 사용자의 성향을 분석하고, 맞춤형 추천을 제공하는 것을 목표로 개발하였습니다.

# 3. 알고리즘 흐름도
![image](https://github.com/user-attachments/assets/4b0b5af9-17b0-4453-9e94-50c1b53b7935)

# 4. 세부 알고리즘 소개
① BERT4Rec : 고객 성향 파악 - 사용자의 영화 취향에 숨어있는 성향을 분석해 여행지 추천에 반영하고자 함.

② Auto Encoder : 사용 데이터 선별 - 고객이 기존에 작성한 한국 음식점 리뷰 데이터를 바탕으로 일본 음식점 추천에 사용될 데이터를 선별함. 

![image](https://github.com/user-attachments/assets/1461a6b6-52c3-4887-b6c7-7864ee44a7c2)


③ LLM recommendation : ①, ②에서 추천 받은 영화 및 식당을 기반으로 RAG의 강점을 살려, 챗봇을 이용하여 정보를 제공할 수 있게 함. 

![image](https://github.com/user-attachments/assets/10ad0f81-d399-4fac-be1b-c1c67ed2622b)

![image](https://github.com/user-attachments/assets/d6f0ae2d-5881-4e76-b4f6-b62de89eec6b)


# 5. 시연 영상 
![KakaoTalk_20241223_231344296](https://github.com/user-attachments/assets/906e032d-9565-4329-a2c8-6de526c4b0bb)


---
## 논문 스터디 

## Contributors

| 순번  | 발표날짜      |     이름              | 모델명(노션 발표자료 링크)                                                                                                                                 | 논문명                                                                                                                                 |
|-----|-----------|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
|  1   | 2024.10.10  |김민열       |   [Bert4rec](https://www.notion.so/BERT4Rec-Sequential-Recommendation-with-Bidirectional-Encoder-Representations-from-Transformer-10eab9efd4d48035bd1dc673c7d175a4?pvs=4)       |     BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer    |
|  2   | 2024.10.10  |서준형       |      [VAE for Collaborative Filtering](https://www.notion.so/Variational-Autoencoders-for-Collaborative-Filtering-10eab9efd4d48078ad00df288d474c4a?pvs=4)    |     Variational Autoencoders for Collaborative Filtering  |
|  3   | 2024.10.10  |김선재       |   [Neural Collaborative Filtering](https://www.notion.so/Neural-Collaborative-Filtering-10eab9efd4d480018458fbee7e4947ed?pvs=4)             |  Neural Collaborative Filtering        |
|  4   | 2024.10.10  |김정현       | [Neural Graph Colaborative Filtering](https://www.notion.so/Neural-Graph-Collaborative-Filtering-10eab9efd4d480809c37ff0bef81af50?pvs=4)    | Neural Graph Collaborative Filtering   |
|  5   | 2024.10.10  |양태원       |    [Wide & Deep Learning for Recommender Sysytems](https://www.notion.so/Wide-Deep-Learning-for-Recommender-Systems-10eab9efd4d4802bb144c63620505b42?pvs=4)                 | Wide & Deep Learning for Recommender Systems  |                        
