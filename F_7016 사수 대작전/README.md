## 7016 사수 대작전

수뭉이는 2호선으로 등교를 하기 때문에 오늘도 시청역에서 7016을 타기 위한 사투를 벌이고 있다.

수뭉이는 버스를 타기 위해 $1$번 정류장에서 탑승하여, $N+1(1\leq N\leq 30,000)$번 정류장에서 내려야 한다.

버스 이동 중, 수뭉이는 앉은 상태와 서 있는 상태 중 하나를 선택 할 수 있으며, 각 정류장에서 다음 정류장으로 이동 할 때 소모되는 힘은 선택한 자세에 따라서 달라진다.

앉은 경우

$i(1 \leq i \leq N)$번 정류장에서 앉아서 $i + 1$번 정류장으로 이동 할 때 $A_i(1 \leq A_i \leq 100)$의 힘이 든다.

단, $i$번 정류장에서 앉으면 다른 정류장에서 일어나거나 좌석을 옮기기 전까지는 동일하게 $A_i$의 힘이 든다.

서 있는 경우

$i$번 정류장에서 $i + 1$번 정류장으로 이동 할 때 $B_i(1 \leq B_i \leq 100)$의 힘이 든다.

수뭉이는 $N + 1$번 정류장까지 최소한의 힘을 들여서 가고 싶어 한다.

수뭉이를 위해 $N + 1$번 정류장까지 가는 데에 드는 힘의 최솟값을 구해주자!

## 서브태스크
|번호|배점|제한|
|---|---|---|
|1|15|$1\leq N\leq 10$|
|2|45|$1\leq N\leq 1000$|
|3|40|추가 제한 사항 없음|

## 입력
첫 번째 줄에는 테스트 케이스의 수 $T(1\leq T\leq 10)$가 주어진다.

각 테스트 케이스의 첫 번째 줄에 정류장의 개수 $N(1\leq N\leq 30,000)$이 주어진다.

두 번째 줄에는 정류장 $i(1\leq i\leq N)$에서 앉아 있을 때 드는 힘 $A_i(1\leq A_i\leq 100)$가 주어진다.

세 번째 줄에는 정류장 $i(1\leq i\leq N)$에서 서 있을 때 드는 힘 $B_i(1\leq B_i\leq 100)$가 주어진다.

## 출력
각 테스트 케이스마다 $1$번 정류장에서 $N + 1$번 정류장까지 가는 데 드는 힘의 최솟값을 출력한다. 

## 예제 입력
2

4

5 2 3 1

1 4 2 3

4

5 1 3 2

1 4 2 3

## 예제 출력
6

4

## 힌트
첫 번째 테스트케이스에서 1번 정류장에서 서 있고, 2, 3번 정류장에서 2번 정류장의 좌석

4번 정류장에서 4번 정류장의 좌석에 앉으면 1 + 2 + 2 + 1 = 6의 힘이 든다.

두 번째 테스트케이스에서 1번 정류장에서 서 있고, 2, 3, 4번 정류장에서 2번 정류장의 좌석에 앉으면 1 + 1 + 1 + 1 = 4의 힘이 든다.

또한 앉아 있는 상태에서 바로 다른 좌석으로 옮기는 것도 가능하다.
