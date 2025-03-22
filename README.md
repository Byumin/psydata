# psydata
심리검사의 개발 과정에서 수집된 데이터를 기반으로,  
문항 수준과 검사 전체의 타당성과 신뢰성을 체계적으로 분석·검토하여, 검사 도구로서의 적절성과 활용 가능성을 검증하는 데 목적

### 표집설계
---
표집된 데이터를 기반으로 검사를 개발하기 때문에 표집설계 역시 매우 중요하다.  
1. 목표 모집단 설정
> 검사가 적용될 대상 집단 (ex 중학생, 특정 진단을 받은 성인, 일반 성인 등)
2. 표본 추출 방식
> 단순 무작위, 층화, 군집 등 다양하지만 대부분 층화+할당표집이 혼합되어 사용
3. 층화 변수
> 층화를 어떻게 설정하냐에 따라서 규준 집단 최소 기준이 달라지기 때문에 신중하게 설정
4. 표본의 크기
> 크기에 따라 분석 결과부터 검정력까지 다방면으로 영향을 줄 수 있음  
>> 규준화 : 각 하위 집단에서 일정 수 이상 확보  
>> 요인분석 : 문항 수 x 5~10배  
>> IRT 모델링 : 최송 500명 이상

### 표본 검증 검토(Sample Date Validation)  
---
실제 수집된 표본이 계획한 표집 설계와 일치하는지 점검  
1. 층화 변수와 수집 데이터 비교
> 실제 수집된 표본이 층화 설정과 맞는지 확인 (설계 : 성별과 만나이 / 실제 : 성별과 연령대)  
>> 층화가 맞지 않다면 저자측과 논의가 필요  
> 설계된 층화 비율과 맞는지 확인 (설계 : 남성 100명 / 실제 : 68명)  
>> 표집된 수가 적어도 대표성을 가지고 있을 수 있기 때문에 추후 검토가 필요함
2. 결측값 확인 및 처리 방안
> 무응답 및 결측치 확인
> 원인 파악 (단순 누락, 시스템 오류 등)
> 어떠한 방법을 활용해 결측치를 대치할지 검토가 필요함
3. 중복 응답 확인
> 동일 ID, 이름, 생년월일 등 중복 응답자가 존재하는지 확인
4. 응답 논리 오류
> 연령이 5세인데 학력이 대학졸업인 비논리적 오류 확인
5. 극단값 및 비정상 응답 확인
> 같은 응답 반복, 무작위 응답 등 확인
6. 데이터 타입 및 범주 확인
> 예를 들어 DATE 타입(생년월일)에 다른 타입이 있는지 확인

