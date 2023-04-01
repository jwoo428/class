# 결정트리
이유를 설명하기 쉬움<br/>
![image](https://user-images.githubusercontent.com/126637081/229266175-832fd3b9-8b21-4917-a968-fd1329923c12.png)
<br/>
### 결정트리 알고리즘의 프로세스
![image](https://user-images.githubusercontent.com/126637081/229266224-e896b209-720b-4a87-a415-28e034f68c60.png)
<br/>위의 그림과 같이 데이터를 가장 잘 구분할 수 있는 기준으로 나눔<br/>
![image](https://user-images.githubusercontent.com/126637081/229266230-a4650bb3-613d-408a-822a-44491bb4b7ca.png)
<br/>나뉜 각 범주에서 또 다시 데이터를 가장 잘 구분할 수 있는 질문을 기준으로 나눔.<br/>
그런데 이를 지나치게 많이 하면 아래의 그림과 같이 오버피팅이됨<br/>
결정트리에 아무 파라미터를 주지않고 모델링하면 오버피팅이 됨<br/>
![image](https://user-images.githubusercontent.com/126637081/229266239-36e698d1-c2e3-4ae0-819a-eb50fbe75ad9.png)
<br/>
### 가지치기
오버피팅을 막기위한 전략
<br/>즉 최대깊이나 터미널 노드의 최대 개수, 혹은 한 노드가 분할하기 위한 최소 데이터 수를 제한하는 것을 말함<br/>

### 불순도(Impurity)
불순도란 해당 범주안에서 서로 다른데이터가 얼마나 섞여있는지를 뜻함<br/>
![image](https://user-images.githubusercontent.com/126637081/229266373-a864025a-d2e9-4958-8e29-b01c066023e2.png)
<br/>위쪽의 범주는 불순도가 낮고 아래쪽범주는 불순도가 높음<br/>
### 지니불순도(gini)
데이터분석에서 흔히 의사결정트리에서 사용되는 클래스개수에 따른 케이스들의 불순한 정도를 나타내는 척도<br/>
![image](https://user-images.githubusercontent.com/126637081/229266604-299bd102-7e12-4912-9f27-1085e7cd7bcd.png)


### 엔트로피(Entropy)
엔트로피는 불순도를 수치적으로 나타낸 척도
<br/>엔트로피↑ - 불순도↑
<br/>엔트로피↓ - 불순도↓
<br/>![image](https://user-images.githubusercontent.com/126637081/229266439-8fc0d3ec-5523-4a9a-b6fd-fb67e9986795.png)

### 정보획득(Information gain)
분기 이전의 엔트로피에서 분기 이후의 엔트로피를 뺀 수치를 정보획득이라고 함<br/>
![image](https://user-images.githubusercontent.com/126637081/229266500-109b9020-a7b3-430c-bc70-8c9ac612830f.png)
<br/>
결정트리 알고리즘은 정보획득을 최대화하는 방향으로 학습이 진행됨<br/>

