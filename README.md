## 프로그래밍의 첫걸음: C 언어 입문

**Windows + Visual Studio 환경에서 실습**하는 **대학 1학년용 C 언어 입문 교재**
---

### **1주차: 프로그래밍 세계로의 초대**

* 컴퓨터와 프로그래밍 언어의 역사
* C 언어 소개: 특징과 활용 분야
* Visual Studio 설치 및 C 프로젝트 구성
* 첫 번째 프로그램: `Hello, World!`
* 팁: Visual Studio 단축키, 디버깅 시작 방법
* 💡 `//` 단일 행 주석(C99), C 표준 개요 소개

---

### **2주차: 변수, 상수, 데이터 타입**

* 기본 데이터 타입 (`int`, `float`, `char` 등)
* 변수 선언 및 초기화, `const` 상수
* `limits.h`, `float.h`의 활용
* `printf()`, `scanf()` 입출력 함수
* 팁: 정수 오버플로우, 부동소수점 비교 시 주의점

---

### **3주차: 연산자와 표현식**

* 산술, 관계, 논리, 비트 연산자
* 복합 대입 및 증감 연산자
* 형 변환 (묵시적/명시적)
* 연산자 우선순위
* 💡 팁: 주석 활용, 실수 표현의 정확도 실습

---

### **4주차: 조건문과 분기 처리**

* `if`, `if-else`, `else-if`, 중첩 조건문
* `switch` 문과 `break`
* 코드 가독성을 높이는 조건문 구조 설계
* 💡 팁: 조건부 컴파일 개념 맛보기 (`#ifdef` 활용 예고)

---

### **5주차: 반복문**

* `while`, `for`, `do-while` 구조
* `break`, `continue`, 무한 루프
* 💡 `for (int i=0;...)` 문법 (C99 선언 위치 자유화)
* 디버거를 통한 반복 흐름 시각화 실습

---

### **6주차: 함수와 변수의 영역**

* 함수 선언, 정의, 호출
* 매개변수와 반환값
* 지역변수와 전역변수, `static`, `extern` 키워드
* 💡 함수 분할과 유지보수성 높은 코드 구성

---

### **7주차: 배열, 문자열, 포인터 기초**

* 1차원 및 2차원 배열, 초기화 방법
* 문자열과 문자열 함수(`strlen`, `strcpy`, …)
* 포인터 개념, 배열과 포인터의 관계
* 💡 포인터 연산, `string.h` 헤더의 역할

---

### **8주차: 포인터 심화와 동적 메모리**

* 함수 매개변수로의 포인터 전달 (Call by reference)
* 이중 포인터의 개념
* `malloc`, `calloc`, `realloc`, `free`
* 💡 NULL 포인터 체크, 메모리 누수 방지 실습

---

### **9주차: 구조체와 공용체**

* 구조체 선언, 멤버 접근 (`.`/`->`)
* 구조체 배열, 포인터와 구조체
* 공용체(`union`)의 개념과 메모리 공유
* 💡 구조체 패딩 개념 및 실습

---

### **10주차: 파일 입출력과 전처리기**

* 텍스트 파일 입출력 (`fopen`, `fscanf`, `fprintf`)
* 이진 파일 입출력 (`fread`, `fwrite`)
* 전처리기: `#define`, `#include`, `#ifdef`, `#pragma once`
* 💡 include guard로 헤더 중복 방지 구현

---

### **11주차: 자료구조와 기초 알고리즘**

* 배열 기반 스택(Stack), 큐(Queue)
* 연결 리스트 기본 개념 소개
* 정렬 알고리즘 (버블, 선택)
* 검색 알고리즘 (선형, 이진)
* 💡 재귀 함수 (피보나치, 팩토리얼)

---

### **12주차: 난수 시뮬레이션과 실용적 프로젝트**

* `rand()`와 `srand()`로 난수 생성
* 주사위 시뮬레이션 구현
* 미니 게임, 주소록, 계산기 등 콘솔 프로젝트 구현

---

### **13주차: SQLite와 OpenGL 기초 실습**

* **SQLite3**:

  * SQL 기초 문법 (SELECT, INSERT, …)
  * C 언어와 SQLite 연동 (라이브러리 설정)
* **OpenGL**:

  * 점, 선, 삼각형 그리기
  * 좌표계 및 색상 개념
* 💡 SQL 인젝션 예방 (`Prepared Statement`), 그래픽스 드라이버 이슈 대처

---

### **14주차: 최신 C 표준과 고급 개념**

* C89 \~ C23 표준 흐름 요약
* `_Generic` 문법 (C11 제네릭)
* `<threads.h>` 멀티스레딩 소개
* C23 주요 변화: `nullptr`, `u8""`, `typeof`
* 💡 컴파일러 옵션(`-std=c11`) 및 문서 참조법 소개

---

### **15주차: 종합 프로젝트 발표 및 기말 시험**

* 팀별 또는 개인 프로젝트 발표 및 시연
* 기말 시험: 파일 입출력, 알고리즘, SQLite/OpenGL 응용 포함
* 💡 다음 단계 로드맵 안내:

  * C++로의 확장, 운영체제/자료구조 심화 학습
  * 버전 관리(Git)와 협업 경험의 중요성

---

## 📌 부록 (선택 제공)

* Visual Studio 디버깅 기초
* 컴파일러 동작 원리 (Preprocessor → Compiler → Linker)
* C언어 메모리 모델 (Stack/Heap/Data/Code 영역 시각화)
* 실습 예제 코드 모음
