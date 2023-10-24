# graphQL-MovieAPI


<img src="https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white"/> <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>


- [소윤's 레포지토리 바로가기](https://github.com/soyoonJ/graphQL)
- [상봉's 레포지토리 바로가기](https://github.com/In-Self-Improvement/graphQL-movieAPI)     

## 🍀 목표
- GraphQL을 활용한 영화 정보 API 구축
- 클라이언트와 서버 간의 효율적인 데이터 통신 구현


## ❗️ Key Point
- GraphQL 스키마 설계
- 영화 데이터를 가져오는 외부 API 연동
- 클라이언트 측에서 원하는 데이터만 선택적으로 가져올 수 있음

## 💻 실행방법
```
npm install

//server 실행
node server.js

//localhost 주소로 이동
http://localhost:4000/
```

## 📝 주요기능
- 영화 목록 조회
- 특정 영화의 상세 정보 조회
- 사용자의 리뷰 및 평점 조회

## 💡 회고
### 소윤
- REST API를 그동안 사용해오면서 가끔 필요한 데이터를 얻기 위해 두가지 API를 호출하거나 새로 API를 만드는 등의 비효율적인 상황이 아쉬웠다.
GraphQL을 사용한다면 딱 필요한 데이터만 가져올 수 있다는 것이 신선했고, api 주소만 알면 모든 데이터를 불러올 수 있는 REST API가 사용 시에는 좀 더 편리하겠지만 대용량 데이터를 활용해야 할 때 GraphQL을 한번쯤 적용해보고 싶었다.

### 상봉
- GraphQL의 효율성과 유연성을 직접 경험할 수 있었음
- restAPI의 장단점(직관적이면서 사용성이 좋지만, 불필요한 호출을 할 수 있다)을 알게되었고, 왜 GraphQL이 탄생하게 되었는지 알게됨.
- GraphQL이 restAPI의 단점을 보완하기 위해서 나왔지만, 스키마를 프론트 / 백엔드 모두 써야한다는 부분을 보완 해야 한다는 것을 알게됨. 

## 🕵🏻‍♂️ 참고
- [GraphQL 공식 문서](https://graphql.org/)
- [강의 영상](https://nomadcoders.co/graphql-for-beginners)
