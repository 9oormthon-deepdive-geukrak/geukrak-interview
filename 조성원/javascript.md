## 프로그래밍

### 프로그래밍이란 뭐라고 생각하나요?

- 컴퓨터가 작업을 수행하기 위해 따를 수 있는 프로그램이라는 명령어 순차 조합을 구성하는 것

### 컴파일러는 뭐고 인터프리터는 뭔가요?

- 컴파일러
  - 프로그램 전체를 스캔해 모두 기계어로 번역
  - 초기 스캔 시간이 오래 걸리지만, 실행 시간은 빠르다.
  - 많은 메모리 사용
    - 고급언어로 작성된 소스를 기계어로 번역(오브젝트 코드)
    - 만들어진 오브젝트 코드를 묶어서 하나의 실행 파일로 제작(링킹)
  - 코드 전체를 검사한 후 오류 메시지를 생성하므로 실행 전에 오류를 발견할 수 있다.
- 인터프리터
  - 프로그램 실행 시 한 번에 한 문장씩 번역
  - 메모리 효율이 좋으나, 실행 시간이 오래 걸린다.
  - 오류를 만나면 프로그램을 중지한다.
