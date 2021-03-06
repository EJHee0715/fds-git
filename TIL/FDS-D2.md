#FDS Day-2


---
##### 컴퓨터의 역사

+ 전기 - 기계식 컴퓨터
  - 릴레이
    - 전자석으로 만들어져 있으며, 켜짐과 꺼짐 상태를 알 수 있다.
    - 진공관, 트랜지스터와 작동원리는 다르지만 같은 역활을 한다.

+ 전자식 컴퓨터
  - 진공관
    - 릴레이와 다르게 전자식으로 움직인다, 릴레이와 똑같지만 계산 속도가 더 빠르다.
  - 트랜지스터
    - 진공관 보다 훨씬 작고, 발열도 적으며 나중에는 점점 더 작아졌다.
    - 현재는 실리콘 기판에 트랜지스터를 인쇄해서 사용한다.
  - 집적 회로

`컴퓨터는 내부가 수많은 0과1 스위치로 작동한다.`

---

##### 컴퓨터는 0과 1 밖에 모른다

+ 스위치가 꺼진 상태는 0, 켜진상태는 1

##### 컴퓨터의 표현방법

+ 수
  - 이진법
  - 부동소수점
  
+ 문자
  - 아스키 코드
  - 유니코드

`인코딩 디코딩은 어떤 정보를 0과 1로 데이터화 한게 인코딩 인코딩을 다시 사람의 언어로 복구 하는것이 디코딩이다.`

---

##### 십진법 & 이진법 & 16진법

[십진법 & 이진법 & 16진법 이미지](https://github.com/fds11/fds-introduction/raw/master/images/binary-number-values.gif)

- 10진수에서는 한자리에 10개의 수를 쓸 수 있다. (8진수는 8개)

- 16진수는 한자리에서 15까지 표현이 가능하며, 10은 a 11은 b ... 15는 f 까지 표현한다.

`CSS에서의 컬러코드는 16진수를 사용한다.`

---

##### 정보의 크기를 나타내는 단위

- 1 bit = 0과 1 = 두가지 경우의 수

  - 1 bit 는 0과 1 밖에 저장 할 수 있다. (스위치가 하나씩 생길 때 마다 x2의 갯수가 늘어난다. 예를 들어 스위치가 3개면 8개의 수를 저장 할 수 있다)

- 1 byte = 8비트 = 256 가지 경우의 수

  - bit가 8개면 1byte가 되며, 1byte는 256가지의 수를 나타낼 수 있다.

`KB = KiB 는 같은거며, byte가 천개면 킬로바이트 1024개면 키비바이트 라고 말한다. 사람은 킬로 바이트라고 표현하지만 컴퓨터는 키비바이트로 표현한다`

---

##### 컴퓨터 구조

[컴퓨터구조](https://github.com/fds11/fds-introduction/raw/master/images/architecture.gif)

- 컴퓨터 구조
  - Bus
    - 메인통로라고 불리며, 많은 장치가 연결되어 있다. 
    
  - Main Memory (주기억장치)
    - RAM 이 사용됨
    - 빠르고 비싸며 용량이 적으며 휘발성이다.
    - 실행 중인 프로그램 및 그 프로그램이 필요로 하는 데이터가 저장되는 기억 장치

  - Secondary Memory (보조기억장치)
    - 속도가 느리며, 용량이 크고, 저렴하다, 비휘발성이다.
    - 하드디스크, SSD가 사용 됨
    - 실행 중이 아닌 프로그램 데이터가 저장

  - CPU (central Processing Unit)
    - 기계어로 작성된 프로그램을 실행
    - 실질적인 계산을 담당
    - 컴퓨터 시스템 전체를 제어 하는 곳 = 사람의 두뇌
  
  `주기억장치랑 보조기억장치가 나누어진 이유는 주기억장치는 사람의 머리, 보조기억장치는 노트로 생각한다.`