# 마크다운 언어 활용
## 1. 제목
- #기호로 표시하며, #의 개수에 따라 제목의 수준이 결정된다.
# 제목 1(#1)
## 제목 2(#2)
### 제목 3(#3)
#### 제목 4(#4)
##### 제목 5(#5)
###### 제목 6(#6)

## 2. 리스트
- 순서 없는 리스트: -,*, 또는 + 기호 사용
- 순서 있는 리스트: 숫자와 점 사용

## 3. 강조
1. 기울임꼴: 단어를 * 또는 _로 감싼다.
  - *기울임꼴*
  - _기울임꼴_

2. 굵은 글씨: 단어를 ** 또는 __로 감싼다.
  - **굵은 글씨**
  - __굵은 글씨__

## 4. 코드 블록
1. 인라인 코드:`백틱`으로 감싼다.
  `System.out.println("Hello Markdown");`
2. 블록 코드:
- 세 개의 백틱(```)을 사용한다.
- 백틱 뒤에 언어를 지정하면 구문 강조도 가능하다.
- 블록 코드의 끝에도 마찬가지로 세 개의 백틱을 작성하면 블록 코드가 끝난다.
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    } 
}
```

## 5. 링크와 이미지
- 링크: [링크 텍스트] (URL) 형식으로 작성한다.
  [Google](https://www.google.com)
- 이미지: ! [대체 텍스트] (이미지 URL) 형식으로 작성한다.
  ![이미지 설명](https://example.com/image.jpg)

## 6. 인용문
- '>' 기호로 시작
> 이것은 인용문입니다.

## 7. 수평선
- '---', '***', 또는 '___'으로 생성 가능하다.
  ---
  ***
  ___

## 8. 표
- 파이프(|)와 하이픈(-)을 사용하여 표를 만들 수 있다.
  | 헤더 1 | 헤더 2 |
  |--------|--------|
  | 내용 1 | 내용 2 |

## 9. 체크리스트
- 대괄호와 공백을 사용하여 만들 수 있다.
 - [ ] 미완료 항목
 - [x] 완료 항목


