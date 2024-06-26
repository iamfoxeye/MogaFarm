# 농사 프로젝트



## 1. 프로젝트 구성 방법

- 디렉토리와 프로그램을 혼용하는 형태
- 디렉토리는 문서와 파일을 관리하고, 프로그램은 재배 작업의 데이터를 응용하는 프로그램을 관리한다.
- 디렉토리에서 직접 만든 작업 파일을, 프로그램에서 수용(임포트) 가능한 형태로 만들어 양쪽의 호환성을 유지한다.
- 업무, 과제, 일정, 기록 등의 기본 자료를 바탕으로 자동 분석하여 구성하는 응용프로그램 개발.



## 2. 디렉토리 구성

### 00. 자료함

  자료의 분류 전 대기 장소. 임시 자료

- 문서
- 사진: 
- 동영상: 



### 10. 농장

 농장의 기본 정보와 자주 빠르게 접근해야 하는 문서 및 기타 자료를 우선적으로 보관.

- 기본정보: 농장명, 설명, 대표사진, 인터넷 정보(전화, 이메일, 홈페이지, 블로그, 유튜브 등)
- 대표문서: 자산현황(토지, 시설, 주소), 지적도 등
- 조직: 직원
- 조직: 교육
- 조직: 인증
- 조직: 건강
- 조직: 안전
- 조직: 근무일정
- 조직: 성과
- 조직: 복지



### 20. 재정

- 예산
- 수입지출
- 투자
- 보조금(대출)



### 30. 자원

- 자산: 토지 및 시설 등의 자산 현황
- 토지: 토양 및 수질 관리
- 물리적 자원: 시설, 농자재, 농기구, 농기계 등
- 비료 및 화학제품
- 종자 관리

- 기계장비: 유지 보수 기록
- 기계장비: 구매 및 임대
- 기계장비: 사용 일지
- 기계장비: 안전 점검



### 40. 생산

- 작물: 생산을 준비하는 작물에 대한 정보
- 재배: 준비-육묘-파종-정식-성장-수확-마무리
- 방제: 재배 전체 단계에 걸친 방제 작업에 대한 정보
- 양분: 재배 전체 단계에 걸친 영양분 공급에 대한 정보



### 50. 판매

- 계획: 시장 조사, 판매 전략, 광고
- 고객: 플랫폼별 고객 관리(온-오프라인 판매처별 고객)
- 상품: 생산물을 포장 및 가공하여 소비자에게 전달할 상품의 정보
- 배송
- 보관



### 60. 연구(개발)

- 신기술
- 품종
- 실험
- 연구 목적별 디렉토리: ex). 지속가능농법
- 교육: 교육 프로그램
- 교육: 온라인 자료
- 교육: 워크숍 및 세미나
- 교육: 인증 및 라이센스



### 70. 안전(위험관리)

- 보험
- 재난재해
- 비상계획
- 위험평가
- 환경: 에너지, 위험물, 폐기물



### 80. 보고(기록)

- 활동보고
- 연간보고
- 감사(검사): 특정 과제에 대한 전 과정 검사



### 90. 보관

- 휴지통: 삭제 대상 자료
- [이전 년도 자료]
- 참고





## 3. 프로그램 구성

### 3.1. 작업 단계 구성

 4~5 단계로 작물의 생산 주기를(1년) 나누고, 필요한 경우 각 단계를 'Set' 용어로 그룹지어 구성(선택적).

 작업이란 용어는 모든 수준의 단계에 공통적으로 사용하는 단어로 사용('작업'이란 용어를 특정 단계에 독립적인 특별한 용어로 사용할 수 없음). 가능하면 표준 용어에 '작업'이란 단어는 사용하지 말것. 설명에는 사용 가능

하위 단계를 나타내는 'Sub' 접두사는 최하위 작업 단계에만 사용한다(Subtask). 다른 단계에 사용하지 않는다. 예를들면, SubActivity, SubProcess, SubProject 등은 사용하지 않고, 단계내 모든 그룹 단위는 'Set' 용어를 이용한다.



**1) Subtask(하위 과제)** :  기본 단위 작업으로 상세한 작업 내용에 해당하며, 간략한 문장으로 표현
 예시: 고추나무 지지대 작업(그룹이 필요한 경우 Set을 이용)

- Subtask Set 1: 지지대 준비

    - Subtask 1: 25밀리 파이프 1.5미터 절단
    - Subtask 2: 25밀리 인발 파이프 1미터 구입

- Subtask Set 2: 지지대 세우기

    - Subtask 3: 25밀리 인발 파이프 50센티 박기
    - Subtask 4: 25밀리 1.5미터 파이프 끼우기
    - Subtask 5: 인발 파이프와 1.5미터 파이프 연결 부위 피스 체결

    

**2) Task(과제)** :  일반적 작업 단위(작업자들이 대화에서 사용하는 흔한 작업 단위로 1~2 단어로 표현)
 예시: 고추 모종 정식

- Task Set 1:모종 준비

    - Task 1: 침종(미생물 침종액에 모종 침종)
    - Task 2: 모종 대기(모종 그늘에 작업 단위 잘라서 보관)

- Task Set 2: 모종 정식

    - Task 3: 배치(준비된 모종 두둑별 식재 자리에 배치)
    - Task 4: 식재(모종 심기)
    - Task 5: 관수(물 주기)

    

**3) Activity(활동)** :  
 예시: 작물 재배를 위한 포괄적 활동

- Activity Set 1: 준비 활동
    - Activity 1: 농장 운영 및 관리 활동
    - Activity 2: 생산 계획 수립 및 관리 활동
- Activity Set 2: 작물 관리 및 마무리 활동
    - Activity 3: 작물 관리 및 감시 활동
    - Activity 4: 수확 및 후속 처리 활동



**4) Process(과정)** : 재배 작물의 생애 주기 각 단계를 대표하는 핵심 작업 그룹
예시: 단호박 육묘, 단호박 정식, 단호박 성장, 단호박 수확, 단호박 정리

- 단호박 성장 Set 1: 순 작업이 완료된 이후의 성장에 대한 작업

    - 줄기 유인
    - 착과

    

**5) Project(프로젝트)** : 재배 작물을 대표하는 작물명을 이용하되, 품종이나 기타 표현을 덧붙여 문장 형식으로 표현.
 예시: 다분지 고추 비가림 재배



### 3.2. 일정 관리

 작업 단계에서 생성한 작업을 토대로 일정 수립. 일간 일정을 제외하고 날짜를 지정하지 않는 경우, 해당 기간 안에 처리할 일정임
작업 단계에 존재하지 않는 일정은, 작업 외 일정으로 취급(개인적 일정으로 간주)



#### 1) 분기 일정

#### 2) 월간 일정

#### 3) 주간 일정

#### 4) 일간 일정

