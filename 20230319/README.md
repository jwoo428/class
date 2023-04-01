# 주성분분석
 
## 차원과 차원축소
### 차원
데이터가 가진속성 = 특성 = 차원<br/>
### 차원축소
데이터를 가장 잘 나타내는 일부 특성을 선택해 데이터 크기를 줄이고 지도 학습모델의 성능을 향상시킬수 있음<br/>
![image](https://user-images.githubusercontent.com/126637081/229269769-db6d50d5-5f79-467c-ae8d-096e614582b8.png)
<br/>
(복원도 가능)<br/>
<br/>
## 주성분분석(PCA)
데이터에 있는 분산이 큰 방향을 찾는것
<br/>
![image](https://user-images.githubusercontent.com/126637081/229269896-f6e513b6-3b6f-475c-9537-58c343c0becb.png)
<br/>
직관적으로 오른쪽위를 향하는 대각선방향이 분산이 가장 크다고 알수 있다.
<br/>
![image](https://user-images.githubusercontent.com/126637081/229269910-0d75086f-2a3c-4ca3-9029-d16e8d89f0b9.png)
<br/>
원점에서 출발한다고 생각했을대 두 원소로 이루어진 벡터로 쓸 수 있는데 이 벡터를 주성분이라고 부른다.
<br/>
![image](https://user-images.githubusercontent.com/126637081/229269919-f238faf5-fdb2-4322-9f83-e5ed6520a825.png)
<br/>
이차원이기때문에 두번째 주성분은 하나밖에 존재하지 않음.
<br/>
![image](https://user-images.githubusercontent.com/126637081/229269929-3009093e-c7fc-48e9-84b8-d28d0e78f81c.png)
<br/>


## 설명된 분산
주성분이 원본데이터의 분산을 얼마나 잘 나타내는지 기록한 값<br/>
