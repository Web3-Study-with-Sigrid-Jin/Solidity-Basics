# Day 1

## 학습 목표

* Solidity의 기초 문법에 익숙해진다.
* Solidity를 활용하는 Ethereum Virtual Machine 기반 개발 환경을 이해한다.
* Remix IDE 사용을 통해 기초적인 컨트랙트 배포 과정을 이해한다.

## 학습 자료

* 저장소에 상기한 pdf 파일을 참고하도록 한다.
* 노션 링크도 참고한다. [바로 가기](https://www.notion.so/jypthemiracle/7b173c3376a7492c97545ed31d09e4d3)

## 구현 과제

* 간단한 Counter Example을 구현한다. 배포 환경은 JavaScript VM이어야 한다.
* `counter` 변수를 설정하고, 해당 변수는 정수 타입이어야 한다.
* `incrementCounter()` 함수를 구현하여, 해당 함수에 요청을 보낼 때 `counter` 변수를 1씩 올리도록 한다.
* `decrementCounter()` 함수를 구현하여, 해당 함수에 요청을 보낼 때 `counter` 변수를 1씩 내리도록 한다.
* `getCount()` 함수를 구현하여, 해당 함수에 요청을 보내 `counter` 변수의 값을 반환하도록 한다.
* Remix IDE에서 구현한 함수를 실행하고, 함수 실행결과를 캡처하여 스크린샷으로 첨부하여 코드와 함께 Pull Request를 보낸다.

## 도전 과제: 프론트엔드 개발 가능자

* 구현 과제의 컨트랙트를 호출할 수 있는 프론트엔드 정적 페이지를 제작한다.
* 해당 페이지에서 button을 `onClick()` 시 컨트랙트 호출 함수를 실행하고자 한다. 어떻게 구현할 수 있을까?
* 학습 키워드: `web3.js`, `ethers.js`

## 생각해보기

* 간단한 Counter Example을 스마트 컨트랙트로 구현해보며, 컨트랙트 배포 과정이 어떤 단계로 구성되어 있는지 본인만의 언어로 설명해보자.
