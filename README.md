# AlgorithmPractice
알고리즘 문제 풀이 저장소

## 사용한 IDE
- IntelliJ IDEA 2020.1.1 (EDU)

## 소스코드 작성법 및 실행방법
- 문제 풀이는 각각의 클래스를 생성해서 작성한다.
- 각각의 문제는 Problem 클래스를 상속받는다. 
- Main.java의 problems HashMap에 클래스를 넣는다.
- 풀이는 각 Problem 클래스의 solution() 메서드에 작성한다. 
- 실행하고자 하는 문제의 key로 문제에 접근하고 run()을 호출해 실행한다.

## 문제 풀이 기록
### 프로그래머스 기출
- [20.10.18] [크레인 인형뽑기 게임](src/problems/kakao/KakaoCranePick.java) - 프로그래머스(2019 카카오 개발자 겨울 인턴십)
- [20.10.18] [두 개 뽑아서 더하기](src/problems/code_challenge/PickAndPlus.java) - 프로그래머스(월간 코드 챌린지 시즌1)
- [20.10.20] [키패드 누르기](src/problems/kakao/KeypadClick.java) - 프로그래머스(카카오 인턴)

### 정렬
- [20.10.21] [K번째수 구하기](src/problems/sort/NumberInK.java) - 2차배열을 잘라서 정렬하고 임의의 차례에 있는 수 구하기
- [20.10.26] [가장 큰 수](src/problems/sort/BiggestNumber.java) - 배열의 숫자를 문자열로 변환하여 붙여서 가장 큰 수의 조합 찾기
- [20.10.27] [H-Index](src/problems/sort/HIndex.java) - 배열을 정렬해서 특정 조건의 숫자 구하기

### 해시
- [20.10.28] [완주하지 못한 선수](src/problems/hash/Marathon.java) - 조건에 부합하는 사람 이름 찾기
- [20.10.31] [전화번호 목록](src/problems/hash/PhoneNumbers.java) - 전화번호 중에 접두어가 겹치는 경우가 있는지 확인하기
- [20.11.01] [위장](src/problems/hash/Camouflage.java) - 2차원 배열에 담긴 옷을 서로 다른 종류대로 조합할 수 있는 경우의 수 구하기
- [20.11.07] [베스트앨범](src/problems/hash/BestAlbum.java) - 각 장르별로 가장 많이된 음악의 index를 최대 2개씩 구하기

### 스택/큐
- [20.11.09] [주식 가격](src/problems/stack_queue/StockPrice.java) - 초마다 기록된 주식가격이 각 초마다 가격이 떨어지지 않은 시간 구하기
- [20.11.11] [기능 개발](src/problems/stack_queue/DevelopingFunction.java) - 개발중인 기능의 작업진도와 속도를 고려해 일정별 배포 가능한 기능의 개수가 담긴 배열을 만들기
- [20.11.13] [다리를 건너는 트럭](src/problems/stack_queue/PassingTrucks.java) - 매 1초마다 1만큼 움직이는 트럭들이 다리가 견디는 무게를 넘지 않고 1차선 다리 위를 순서대로 모두 건너는 시간 구하기
- [20.11.14] [프린터](src/problems/stack_queue/Printer.java) - 우선순위가 높은 문서를 먼저 출력하는 프린터에서 내 문서가 출력되는 순서 구하기

### 힙(Heap)
- [20.11.18] [더 맵게](src/problems/heap/MoreSpicy.java) - 모든 음식이 스코빌 지수 K이상이 되도록 가장 덜 매운 음식 두 개를 조합하기
- [20.11.23] [디스크 컨트롤러](src/problems/heap/DiskController.java) - 2차원 배열로 주어진 작업시작 시간과 처리시간을 사용하여 총 처리 시간이 가장 적게 걸리는 방법으로 작업했을 때 평균값 구하
- [20.11.24] [이중우선순위큐](src/problems/heap/DoublePriorityQueue.java) - 임의의 자료구조 이중우선순위큐를 구현하여 최댓값/최솟값을 삽입 또는 삭제하는 연산을 수행하고 결과값을 리턴하기

### 완전탐색(Brute Force)
- [20.11.29] [모의고사](src/problems/brute_force/PracticeExam.java) - 모의고사에서 수학문제를 찍은 삼인방 중에 가장 문제를 많이 맞춘 사람 찾기
- [20.12.01] [소수찾기](src/problems/brute_force/FindingPrime.java) - 주어진 문자열안의 숫자를 조합하여 소수 찾기
- [20.12.05] [카펫](src/problems/brute_force/Carpet.java) - 주어진 카펫 격자의 숫자를 통해 카펫의 가로/세로 사이즈 구하기

### 깊이/너비 우선 탐색(DFS/BFS)
- [20.12.08] [타켓넘버](src/problems/dfs_bfs/TargetNumber.java) - 주어진 숫자들을 적절히 더하고 빼서 타겟 넘버를 만드는 방법의 수를 구하기
- [20.12.12] [네트워크](src/problems/dfs_bfs/Network.java) - 컴퓨터끼리 연결된 네트워크의 개수를 구하기
- [20.12.25] [단어변환](src/problems/dfs_bfs/ConvertingWord.java) - 한 글자씩만 단어을 변환해서 target 단어로 변환하는 가장 짧은 과정 구하기
- [21.01.05] [여행경로](src/problems/dfs_bfs/TravelRoute.java) - 2차원 배열로 주어지는 여행 경로(목적지, 출발지) 중 알파벳 순으로 가장 빠른 경로를 찾아서 배열로 반환하기 