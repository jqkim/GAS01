## Welcome to GAS#01

# 01.개요

# 02.현황 (영업전략부/브랜드전략부)
  - 광고채널/캠페인별 유효값을 알 수 없음 (업무현황 확인필요)
  - 광고대행업체(엠포스) 의존도가 높음. (대행업체 Report수집필요)
  - 효율적인 광고측정을 통한 광고비 집행이 필요함(비용/효과 수치화)
  - 실제 기여도가 높은 채널과 비용을 정확히 알고싶음.
  
# 03.방안
  - 온라인채널 광고 전환비용 측정 필요
    a. 끊어진 프로세스Flow를 연결해보자.
    b. 프로세스 구간별 Sub-KPI/비용을 측정해보자.
  - 온라인채널 기여도 모델생성
    a. 알고리즘 선택필요

# 04.이슈
  - 데이터연결을 위한 매핑키
    a. 내부-GA360 데이터를 연동하여 분석 하는데 상당한 시간이 소요될 것 같음
    b. 신청서접수번호 등 매핑을 위한 Key가 GA에 없을 수 있다.
  - AS-IS대비 차별성 부족
    a. 기존에 당사 데이터만으로도 분석 가능한 주제인 것 같아서 GA과의 맵핑 및 효율화 방안이 구체적으로 필요해 보임
    b. Attribution model을 만드는 것은 약간 다른 문제인 것 같습니다. 각 journey touch point별로 세분화해서 볼 데이터가 많을 것 같습니다.
    c. 광고별 비교 추가필요
    d. 테이블화를 시킨다는 부분에 대한 구체적 설명이 필요할듯합니다~
    
# 05.예상결과
  - 향후 활용 방안. 고객의 흔적을 찾아서 붙이는거 너무 좋은 아이디어
  - 활용 가능성 및 수익 개선 가능성이 돋보입니다.
		
# 06.To-do
## step1.분석: 비즈니스이해
    자료수집1: KPI (발급/전환/예산)
    자료수집2: 광고정산/레포트(엠포스)
    자료수집3: 광고정산/레포트(GDN)
    자료수집4: 메타데이터(CRM)
    자료수집5: 메타데이터(GA)

## step2.설계: 요건정의 및 명세
    설계1: 프로세스흐름
    설계2: 데이터흐름
    설계3: 데이터셋 스키마
    설계4: 분석환경세팅 및 UI기획
    설계5: 가설/검증/요구사항 시나리오
    
## step3.분석
    전처리: RAW생성
    전처리2: Merge
    전처리3: Mart
    분석1: EDA
    분석2: Metric생성
    분석3: Demension생성
    분석4: Report (Dashboard)
    분석5: Report (Notebook)
    분석6: Google ML/DL

## step4.검증
    단위테스트 (vs설계)
    가설검증
    A/B Test

## step5. 종료
  보고서 생성
  발표자료 생성
  Demo 생성

