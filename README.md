# 코드다듬기


코딩 테스트 제출 전, 사이트 제출 형식에 맞게 코드를 자동으로 정리해주는 Chrome 확장 프로그램입니다.

프로그래머스에서는 코드 실행, 제출, 초기화 단축키도 함께 사용할 수 있습니다.

---


## ✨ 주요 기능

* Java, C++, Python 코드 자동 감지
* 사이트별 Java 클래스명 자동 변경
* Java `package` 선언 제거
* 프로그래머스 Java/C++ `main` 제거
* Java/C++/Python 주석 제거
* 언어별 변환 옵션 설정
* 프로그래머스 단축키 지원

---
### ⚙️ 설정 화면

사용자는 팝업에서 언어별 변환 옵션을 켜고 끌 수 있습니다.

| Java 설정 | C++ 설정 | Python 설정 |
|----------|----------|----------|
| <img src="https://github.com/user-attachments/assets/7091dec2-3938-47c9-868f-c59238dcef57" width="250"> | <img src="https://github.com/user-attachments/assets/21028dcc-4ae4-4502-9d8e-a4d84b9523dd" width="250"> | <img src="https://github.com/user-attachments/assets/1576ec43-cca4-41b6-a8b7-ae32e79da835" width="250"> |

- Java: 클래스명 변경, package 제거, 주석 제거 설정
- C++: 주석 제거 설정
- Python: 주석 및 docstring 제거 설정

---


## 📸 예시

> 아래 예시는 프로그래머스 기준입니다.

<img width="800" height="227" alt="Image" src="https://github.com/user-attachments/assets/6ba4c376-a5ad-4afc-9b0d-02f6fb2440b2" />

### 변환 전

```java
package algo;

public class Main {
    public static void main(String[] args) {
        System.out.println("test");
    }
}

class MySolution {
    // comment
    public int solution(int n) {
        return n + 1;
    }
}
```

### 변환 후

```java
class Solution {
    public int solution(int n) {
        return n + 1;
    }
}
```

---

## 🌐 지원 사이트


| 사이트 | 자동 변환 | 단축키 |
|---------|---------|---------|
| 프로그래머스 | ✅ | ✅ |
| SWEA | ✅ | ❌ |
| ~~백준~~ | ❌ 지원 종료 | ❌ |

---

## ⌨️ 프로그래머스 단축키

프로그래머스 문제 풀이 화면에서만 사용할 수 있습니다.

| 단축키                      | 동작        |
| ------------------------ | --------- |
| Ctrl + Space             | 코드 실행     |
| Ctrl + Enter             | 제출 후 채점하기 |
| Ctrl + Shift + Backspace | 초기화       |

초기화 창이 열리면:

| 키     | 동작 |
| ----- | -- |
| Enter | 확인 |
| Esc   | 취소 |

---

## 🚀 설치

Chrome 웹스토어에서 설치할 수 있습니다.

[Chrome 웹스토어 링크 추가 예정]

---

## ⚙️ 자동 변환

### Java

* 클래스명 변경
* `package` 제거
* 주석 제거
* 프로그래머스 `main` 제거

### C++

* 주석 제거
* 프로그래머스 `main` 제거

### Python

* 주석 제거
* docstring 제거

---

## 🔒 개인정보

코드는 외부 서버로 전송되지 않습니다.

모든 변환은 브라우저 내부에서 수행됩니다.

자세한 내용은 [정책.md](privacy-policy.md)를 참고하세요.

