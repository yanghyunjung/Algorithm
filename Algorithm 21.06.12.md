## 3,4주차 강의:memo:   

### __3주차__   
__스택(Stack)__ 은 나중에 들어간 게 먼저 나오고(last in, first out)   
__큐(Queue)__ 는 먼저 들어간 게 먼저 나온다(first in, first out).   

* 스택! 왜 필요한가?   
넣은 순서를 쌓아두고 있기 때문에 이 순서가 필요한 경우가 있다. 예를 들어 컴퓨터의 되돌리기 기능이 있다. 직전에 했던 행동을 되돌리고 싶을 때 사용하는 기능이다.   
`push(data)` : 맨 위에 데이터 넣기   
`pop()` : 맨 위 데이터 뽑기->맨 위를 뽑기 때문에 굳이 인자가 필요 없다.   
`peek()` : 맨 위 데이터 보기   
`isEmpty()` : 스택이 비었는지 안 비었는지 여부 반환해주기   

* 큐! 왜 필요한가?   
순서대로 처리되어야 하는 일에 필요하기 때문이다. 에를 들어 주문이 들어왔을 때, 놀이기구 줄!   
`enqueue(data)` : 맨 뒤에 데이터 추가하기(삽입연산이 이루어짐)   
`dequeue()` : 맨 앞 데이터 뽑기(삭제연산이 이루어짐)   
`peek()` : 맨 앞 데이터 보기   
`isEmpty()` : 큐가 비었는지 안 비었는지 여부 반환해주기  

---     
* 파이썬에서 swap 하는 방법   
a,b = b,a 라고 적으면 된다. 아주 간단!   
---   

* 선택 정렬 vs 삽입 정렬   
-선택정렬이 전체에서 __최솟값__ 을 선택하는 거였다면 삽입 정렬은 __전체에서 하나씩 올바른 위치에 삽입__ 하는 방식이다.   
-삽입정렬은 시간복잡도를 줄일 수 있다.   

* 병합정렬-merge (더 공부할 예정)   

* 해쉬테이블이란?   
데이터의 검색과 저장이 아주 빠르게 진행된다   


### __4주차__   
큐, 스택은 선형구조라고 한다. But, 트리는 비선형구조! -> 표현적인 것에 초점이 맞춰져 있다.   
* 트리의 종류에는 이진트리가 있다. 이진트리는 각 노드가 최대 두개의 자식을 가진다는 것이다.   

* 완전 이진 트리 구조를 분석해보자!
1.	현재 인덱스 * 2 -> 왼쪽 자식 노드
2.	현재 인덱스 * 2 + 1 -> 오른쪽 자식 노드
3.	현재 인덱스 // 2 -> 부모의 인덱스
힙은 부모 노드의 값이 자식 노드의 값보다 크다!

* BFS & DFS (더 공부할 예정)

* Dynamic Programming (동적 프로그래밍)   
피보나치 수열(재귀함수) - 첫째 및 둘째 항이 1이며 그 뒤의 모든 항은 바로 앞 두 항의 합인 수열이다. 그러면 Fibo(n) = Fibo(n-1) + Fibo(n-2) 라고 표현할 수 있다. 재귀함수니까 꼭 탈출조건을 써야한다!   