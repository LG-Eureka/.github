<p align="center">
  <img src="https://img.shields.io/badge/LG%20U+-Eureka-ED0080?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Runnable%20Demos-2f81f7?style=flat-square" />
  <img src="https://img.shields.io/badge/Approach-Rebuilt%20%26%20Documented-8b5cf6?style=flat-square" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-6DB33F?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Swing-Desktop%20UI-007396?style=flat-square&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=flat-square&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docs-Korean-111827?style=flat-square" />
</p>

LG 유플러스 유레카 과정에서 만든 프로젝트를 **지금도 실행되는 형태로 다시 정리해 두는 조직**입니다.

부트캠프 프로젝트는 과정이 끝나면 대개 그대로 멈춰 섭니다. 접속 정보가 빠져 있거나, 예시 데이터의
날짜가 지나 있거나, 당시에 못 고친 버그가 남아 있어서 다시 열어 봐도 화면이 뜨지 않는 경우가 많습니다.

이 조직은 그때의 결과물을 **그대로 복제해 두는 보관소가 아니라**, 다시 실행해 보고 문제를 고쳐서
**언제든 시연할 수 있는 상태로 유지하는 공간**입니다.

## 프로젝트

| 저장소 | 설명 | 기술 |
| --- | --- | --- |
| [**CineSeat**](https://github.com/LG-Eureka/CineSeat) | 날짜 · 회차 · 좌석을 골라 예매하는 영화 좌석 예매 데스크톱 애플리케이션. 좌석 중복 예매 차단, 실제 상영작 데이터 연동(KOBIS)까지 포함합니다. | `Java` `Swing` `MySQL` `JDBC` |

> 과정에서 만든 나머지 프로젝트도 하나씩 옮겨 올 예정입니다.

## 이렇게 정리합니다

원본을 그대로 두고 무엇을 고쳤는지 드러나게 하는 것을 원칙으로 삼습니다.
예를 들어 CineSeat에서는 이런 것들을 찾아 고쳤습니다.

- 상영관을 고를 때 잘못된 키를 넘겨 외래키 제약에 걸리던 문제 — 당시 README에 미해결로 남아 있던 항목입니다.
- 예매할 때 선택한 상영일이 아니라 버튼을 누른 순간의 날짜가 저장되던 문제
- 좌석 중복 확인이 없어 같은 자리를 여러 번 예매할 수 있던 문제

각 저장소 README의 **"정리하면서 고친 것"** 항목에서 전체 목록을 볼 수 있습니다.
