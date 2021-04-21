
# 묵찌빠 프로젝트

## 1. 우리 팀만의 규칙

연락이 어려운 시간
- Kane - 수요일 저녁 이후
- 강경 - 수 12:00~15:00
- kio - 화, 금 20:00~22:00

TIL, 일일회고
- 새벽 1시까지 업로드하기

규칙
- 모르는 건 넘어가지 말고 물어보기

<br>

### 1-1. 스크럼

- 스크럼이란 모든 팀원이 모여 매일 짧게 진행 상황을 공유하는 것

시간

- 월, 목 09:10~09:30
- 화, 수, 금 10:00~10:30

주제

- 어제한 일
- 오늘한 일
- 컨디션
- 기술적 이슈

<br>

### 1-2. 프로젝트 협업 규칙

- 프로젝트 협업과 관련된 규칙을 정해요.
- 브랜치 이름규칙

    step1 (step1 메인) - PR 보내는 브랜치

    step1-Kane, step1-Kio, step1-Kangkyong

    step2 (step2 메인) - PR 보내는 브랜치

    step2-Kane, step2-Kio, step2-Kangkyong

- 커밋 규칙

    commit karma

    ```swift
    # <타입>: <제목>

    ##### 제목은 최대 50 글자까지만 입력 ############## -> |

    # 본문은 위에 작성
    ######## 본문은 한 줄에 최대 72 글자까지만 입력 ########################### -> |

    # 꼬릿말은 아래에 작성: ex) #이슈 번호

    # --- COMMIT END ---
    # <타입> 리스트
    #   feat    : 기능 (새로운 기능)
    #   fix     : 버그 (버그 수정)
    #   refactor: 리팩토링
    #   style   : 스타일 (코드 형식, 세미콜론 추가: 비즈니스 로직에 변경 없음)
    #   docs    : 문서 (문서 추가, 수정, 삭제)
    #   test    : 테스트 (테스트 코드 추가, 수정, 삭제: 비즈니스 로직에 변경 없음)
    #   chore   : 기타 변경사항 (빌드 스크립트 수정 등)
    # ------------------
    #     제목 첫 글자를 대문자로
    #     제목은 명령문으로
    #     제목 끝에 마침표(.) 금지
    #     제목과 본문을 한 줄 띄워 분리하기
    #     본문은 "어떻게" 보다 "무엇을", "왜"를 설명한다.
    #     본문에 여러줄의 메시지를 작성할 땐 "-"로 구분
    # ------------------
    ```

    참고사이트

    - 좋은 커밋 메시지를 작성하기 위한 커밋 템플릿 만들어보기 : [https://junwoo45.github.io/2020-02-06-commit_template/](https://junwoo45.github.io/2020-02-06-commit_template/)
    - 커밋 메시지의 규칙 : [https://udacity.github.io/git-styleguide/](https://udacity.github.io/git-styleguide/)
    - [https://blog.munilive.com/posts/my-git-commit-guide.html](https://blog.munilive.com/posts/my-git-commit-guide.html)

<br>
<br>

## 2. 묵찌빠 프로젝트 세부사항
### 2-1. 타임라인 ('21.03.01 ~ '21.03.05)

- 월 - 팀그라운드룰 설정, step 1 의사코드 설계, step 1 각자 코딩해보기
- 화 - step1 PR
- 수 - step1 PR 리뷰 & step2 슈도코드 각자 설계
- 목 - step1 refactor
- 금 - step2 PR
### 2-2. 프로젝트 초기 설계

```swift
class step1 {
	/// 게임 스타트 메서드
	func gameStart() {
	
	}

	/// 최초 출력 메서드
	func temp1() {

	}

	/// 사용자 입력 받는 메서드
	func temp2() {

	}

	/// 결과 판별 후 출력 메서드
	func temp3() {

	}
}

step1().gameStart()
```

<br>

### 2-3. 묵찌빠 프로젝트 구현내용


<br>

### 2-4. 학습 키워드

- eunm 열거형
	- String, Int
	- CaseIterable
	- Comparble
	- Error
	- rawValue
- 반복문
	- while { }
	- repeat { } while
- 옵셔널 바인딩
	- if let
	- guard let
- do catch문
- class
	- init(생성자)
	- 열거형 타입 부여
