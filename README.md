# 부동산 실거래가 예측 프로젝트

<div>
  <h2> <strong>프로젝트 표지</strong> </h2>
</div>

![SQL 프로젝트 표지](SQL_표지.png)

<br>

<div>
  <h2><strong>발표자료</strong></h2>
</div>

<ul>
  <li><a href="SQL프로젝트.pdf">부동산 실거래가 예측 프로젝트 자료</a></li>
</ul>


<br>

<div>
  <h2><strong>프로젝트 개요</strong></h2>
  부동산 실거래가 예측을 주제로 한 프로젝트입니다.<br>
  SQL에서 조인, 정규식 함수, 회귀분석 등을 활용하여 데이터 분석을 진행하였습니다.<br>
</div>

<br>

<div>
  <h2><strong>🛠 사용 기술 스택</strong></h2>
  <ul>
    <li><strong>언어</strong> : SQL </li>
    <li><strong>테이블 구성 및 전처리</strong> : </li>
      <ul>
        <li>update</li>
        <li>regexp_substr</li>
        <li>join</li>
        <li>comment on column</li>
        <li>primary key</li>
      </ul>
    <li><strong>머신러닝 </strong>: 
      <ul>  
        <li>DBMS_DATA_MINING.REGRESSION</li>
      </ul>
  </li>
  </ul>
</div>

<br>

<div>
  <h2><strong>프로젝트 내용</strong></h2>
  <ul>
    <li><strong>1.주제 선정</strong>
      <ul>
        <li>서울시의 부동산 실거래가에 가장 큰 영향을 끼치는 요인 분석</li>
      </ul>
    </li>
    <br>
    <li><strong>2.데이터 설명</strong>
      <ul>
        <li><strong>활용 데이터:</strong>
          <ul>
            <li>서울시 부동산 실거래가 현황</li>
            <li>서울시 대규모 점포 인허가 현황</li>
            <li>서울시 자치구별 지하철역 정보</li>
          </ul>
        </li>
        <br>
        <li><strong>데이터 수집 출처:</strong>
          <ul>
            <li>공공 데이터 포털</li>
          </ul>
        </li>
      </ul>
    </li>
    <br>
    <li><strong>3.데이터 분석</strong>
      <ul>
          <li>필요한 데이터를 활용하기 위하여 전처리 후 하나의 테이블로 구성</li>
          <li>회귀분석을 통하여 분석 진행</li>
      </ul>
    </li>
    <br>
    <li><strong>4.결과</strong>
      <ul>
        <li>데이터 내에서 위치, 아파트 여부가 결정적인 요인</li>
        <li>건축년도가 가장 영향력이 낮음</li>
      </ul>
    </li>
  </ul>
</div>

<br>

<div>
  <h2><strong>보안점</strong></h2>
  <ul>
    <li>데이터의 한계점</li>
      <ul>
        <li>금리, 학군, 지하철 외 교통 요인 등 추가 고려</li>
        <li>2023년 이전 데이터 추가</li>
      </ul>
  </ul>
</div>

