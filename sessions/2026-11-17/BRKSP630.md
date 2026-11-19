# BRKSP630 · Azure·NVIDIA 가속 컴퓨팅과 GPU SQL

**에이전트의 긴 문맥과 반복 호출, SQL 동시성 부하를 서로 다른 워크로드로 다뤘다.**

2026-11-17 · 공식 녹화·제품 문서 · GPU·추론·비용

## 핵심 내용

- 장기 실행 에이전트는 문맥·턴·도구 호출이 늘어나므로 KV 캐시 재사용이 중요하다고 설명했다.
- Fabric SQL 시연은 활성 사용자 250명·쿼리 1,000건에서 기준 구성 682.4초, GPU 가속 구성 11.4초를 표시했다. 이는 특정 시연의 완료 시간이다.
- Vera Rubin NVL72 Confidential Bare Metal은 Technology Preview, Fabric Data Warehouse 가속은 Limited Public Preview로 소개됐다.

## 확인 범위

GPU 기종·수량·단가, 캐시 초기 상태와 반복 측정 조건은 미확인이다. SQL 시연의 시간 비율을 추론 성능이나 비용 절감률로 바꾸지 않는다. 다른 슬라이드의 전력·비용 비교도 별개다.

## 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787854985876001tT18-1791588339892001ChGq)
- [Microsoft Events 공식 영상](https://www.youtube.com/watch?v=g2wSshatJ90)
- [행사 개별 녹화: 23:15–25:15 SQL 시연](https://medius.microsoft.com/Embed/video-nc/266c0933-b786-4fac-b5cb-38d6d6be2502)
- [Fabric 기능 문서](https://learn.microsoft.com/en-us/fabric/data-warehouse/query-acceleration)

[전체 세션 목록](../../README.md)
