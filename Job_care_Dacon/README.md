# Jobcare-Dacon-
## Data preprocess
### 2022-01-10
#### 1. 모든 속성 데이터 프레임에 합침
#### 2. 합칠 때 이용한 최 하위 특성 칼럼 삭제
#### 3. 날짜 칼럼 datetime으로 바꾼 후 이를 다시 요일 정보로 반환
#### 4. person_attribute_a랑 그 하위 속성 합침(-10~10)
#### 5. contents_attribute_j랑 그 하위 속성 합침
#### 6. 1,2 만 갖는 칼럼들은 모두 0,1만 갖도록 수정
#### 7. person_f, person_g, contents_rn 등 필요없는 칼럼 삭제
#### 8. catboost를 이용하기 때문에 원핫인코딩 이용 x
#### 9. person과 contents에 같이 있는 속성 간 일치 여부 판정 칼럼 생성
### 2022-01-12
#### 1. person_attribute_a, contents_attribute_j 상, 하위 속성 다시 분리 
