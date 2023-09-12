# 프로젝트명

실시간 응급실 API를 이용한 응급실 정보 웹 사이트 구축

## 팀원 소개

- 전소향: 데이터 파이프라인 구축, 대시보드 시각화 (airflow, tableau) 
- 임찬우: 데이터 파이프라인 구축, 대시보드 시각화 (kafka, tableau)
- 이원진: 백엔드, 프론트엔드 개발 (django, react)

## 프로젝트 설명

### 목표
- 전국 단위의 응급의료정보망을 이용해 실시간으로 이송가능한 병원을 확인하여 효율적인 이송체계가 확립되는 것을 목표로 합니다.

### 필요성
- [인프라 구축의 부족](http://www.whosaeng.com/144454)
- [전국 단위 응급정보망 필요](https://medigatenews.com/news/3802606837)

### 활용 데이터
- [실시간 응급실 API](https://www.data.go.kr/data/15000563/openapi.do)

### 데이터 아키텍처
<img width="857" alt="스크린샷 2023-09-05 오전 12 33 02" src="https://github.com/119-monitoring-project/data-pipeline/assets/103482118/f8c4d325-59bc-4127-9c2f-03b239f13eb2">

### 주요기능

- 의료기관 검색 (지역, 병원명, …)
- 필터링 (병원분류, 특정 시술 가능 여부, …)
- 응급시설 정보 확인
- 정보 수정 제안

### 시연영상
https://github.com/119-monitoring-project/data-pipeline/assets/103482118/5c4c183f-e280-4508-b8ab-7e5f139f1d2f
