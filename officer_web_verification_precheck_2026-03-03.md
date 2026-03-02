# 장수 웹 검증 1차 자동 판정 (ko.wikipedia)
- 생성일: 2026-03-03
- 입력: `/Volumes/Storage/StudioProjects/threekingdom/docs/officer_web_verification_queue_2026-03-03.csv`
- 출력 CSV: `/Volumes/Storage/StudioProjects/threekingdom/docs/officer_web_verification_queue_precheck_2026-03-03.csv`
- 전체 큐: 931명
- 이번 배치: 인덱스 840~930 (91명)
- 누적 처리(출력 CSV 행): 931명
- 이번 배치 KEEP_CANDIDATE: 87명
- 이번 배치 REMOVE_CANDIDATE: 4명
- 이번 배치 REVIEW: 0명
- 이번 배치 ERROR: 0명
- 누적 KEEP_CANDIDATE: 729명
- 누적 REMOVE_CANDIDATE: 198명
- 누적 REVIEW: 4명
- 누적 ERROR: 0명

## 주의
- 이 파일은 자동 1차 판정이며 최종 삭제 기준이 아닙니다.
- 동명이인/표기 차이 때문에 `REVIEW`를 수동 검증해야 합니다.

## 샘플 30건
| ID | 이름 | 1차판정 | 근거 | 출처 |
|---:|---|---|---|---|
| 8 | 유표 | KEEP_CANDIDATE | contains keywords: 후한 | [링크](https://ko.wikipedia.org/wiki/%EC%9C%A0%ED%91%9C) |
| 9 | 유장 | KEEP_CANDIDATE | contains keywords: 후한, 조조, 유비, 손권 | [링크](https://ko.wikipedia.org/wiki/%EC%9C%A0%EC%9E%A5%20%28%EC%82%BC%EA%B5%AD%EC%A7%80%29) |
| 10 | 마등 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 11 | 공손찬 | KEEP_CANDIDATE | contains keywords: 후한 | [링크](https://ko.wikipedia.org/wiki/%EA%B3%B5%EC%86%90%EC%B0%AC) |
| 13 | 장로 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 14 | 여포 | KEEP_CANDIDATE | contains keywords: 후한, 조조, 유비 | [링크](https://ko.wikipedia.org/wiki/%EC%97%AC%ED%8F%AC) |
| 16 | 한수 | KEEP_CANDIDATE | contains keywords: 삼국 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80%20%EC%9D%B8%EB%AC%BC%20%EB%AA%A9%EB%A1%9D) |
| 19 | 마초 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 촉한 | [링크](https://ko.wikipedia.org/wiki/%EB%A7%88%EC%B4%88%20%28%EC%B4%89%ED%95%9C%29) |
| 20 | 유종 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 21 | 하진 | KEEP_CANDIDATE | contains keywords: 삼국 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80%20%EC%9D%B8%EB%AC%BC%20%EB%AA%A9%EB%A1%9D) |
| 25 | 가비능 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 26 | 주창 | KEEP_CANDIDATE | contains keywords: 삼국 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80%EC%97%B0%EC%9D%98) |
| 27 | 저족수령 | REMOVE_CANDIDATE | no key Three Kingdoms keywords in intro | [링크](https://ko.wikipedia.org/wiki/%EC%A0%80%EC%A1%B1) |
| 28 | 강족수령 | REMOVE_CANDIDATE | no key Three Kingdoms keywords in intro | [링크](https://ko.wikipedia.org/wiki/%EC%A1%B0%EC%84%A0%EB%AF%BC%EC%A3%BC%EC%A3%BC%EC%9D%98%EC%9D%B8%EB%AF%BC%EA%B3%B5%ED%99%94%EA%B5%AD) |
| 29 | 흉노선우 | REMOVE_CANDIDATE | no key Three Kingdoms keywords in intro | [링크](https://ko.wikipedia.org/wiki/%EB%8C%80%EA%B5%B0%20%28%ED%96%89%EC%A0%95%20%EA%B5%AC%EC%97%AD%29) |
| 33 | 조인 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 36 | 전위 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 37 | 장료 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 손권 | [링크](https://ko.wikipedia.org/wiki/%EC%9E%A5%EB%A3%8C) |
| 41 | 곽가 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 50 | 조장 | KEEP_CANDIDATE | contains keywords: 삼국 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80%20%28%EB%B9%84%EB%94%94%EC%98%A4%20%EA%B2%8C%EC%9E%84%20%EC%8B%9C%EB%A6%AC%EC%A6%88%29) |
| 53 | 왕랑 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 58 | 조진 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 61 | 방덕 | KEEP_CANDIDATE | contains keywords: 후한, 조조 | [링크](https://ko.wikipedia.org/wiki/%EB%B0%A9%EB%8D%95) |
| 65 | 종요 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 67 | 두습 | KEEP_CANDIDATE | contains keywords: 후한 | [링크](https://ko.wikipedia.org/wiki/%EB%91%90%EC%8A%B5) |
| 72 | 유방 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 73 | 손자 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 80 | 방통 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 유비 | [링크](https://ko.wikipedia.org/wiki/%EB%B0%A9%ED%86%B5) |
| 90 | 이엄 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
| 92 | 미축 | KEEP_CANDIDATE | contains keywords: 삼국, 후한, 조조, 유비, 위나라 | [링크](https://ko.wikipedia.org/wiki/%EC%82%BC%EA%B5%AD%EC%A7%80) |
