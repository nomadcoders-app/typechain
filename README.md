# Typechain

Learning Typescript by making a Blockchain with it.

>Typescript = Javascript + Types

Typescript는 Type annotation을 통해 함수나 변수에 타입을 명시할 수 있다. 변수나 배열에 값을 담거나 함수를 호출할 때 의도되지 않은 다른 값이 들어가는 것을 방지한다.

인터페이스가 추가되었고 클래스를 사용할 때 `public`, `private` 등을 명시해서 OOP의 의미를 더욱 명확히 할 수 있다.

## [tsconfig.json](https://typescript-kr.github.io/pages/tsconfig.json.html)

Typescript가 Javascipt로 변환될 때의 규칙을 정의한다.

`yarn start` 명령어를 통해 컴파일한다.

## 블록체인

>데이터 분산  처리 기술

블록체인에서 "블록"은 개인과 개인의 거래(P2P)의 데이터가 기록되는 장부다. 이런 블록들은 형성된 후 시간의 흐름에 따라 순차적으로 연결된 "사슬(Chain)"의 구조를 가지게 된다.

기존 거래 방식은 은행이 모든 거래 내역을 가지고 있었다. 하지만 블록체인은 여러 명이 나워서 저장한다. 한 네트워크에 10명이 참여하고 있다면 두 사람의 거래 내역으로 10개의 블록을 생성해 10명 모두에게 전송 및 저장한다. 나중에 거래 내역을 확인할 때는 블록을 나눠 저장한 데이터를 연결해 확인한다.

### 블록체인의 특징

기존 거래 방식은 은행의 중앙 서버를 공격하여 데이터를 위/변조할 수 있었다. 그러나 블록체인에서는 여러 명이 데이터를 저장하고 있기 때문에 위/변조가 사실상 불가능하다.

---

블록체인을 사용하게 되면 중앙기관의 역할이 필요 없어지기 때문에 중앙은행이 없어도 화폐 발행이 가능해진다. 이를 통해 등장한 것이 가상화폐이다. 블록체인을 기반으로 만들어진 온라인 암호화폐인 비트코인의 경우, 이를 발행하는 기관도 통제하는 곳도 없다. 비트코인을 원하는 사람들이 '채굴'을 통해 '발행'할 수 있다. 높은 신뢰성과 보안성을 지닌 블록체인 기술은 산업 전 분야에 확산될 것으로 보인다.

[출처: 블록체인 개념 완벽 정리 @ Banksalad](https://banksalad.com/contents/%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%EA%B0%9C%EB%85%90-%EC%99%84%EB%B2%BD-%EC%A0%95%EB%A6%AC-dh1do)