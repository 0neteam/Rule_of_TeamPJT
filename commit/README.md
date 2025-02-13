# git 명령어 알고싶으면 여기 가서 보시고...

https://github.com/JosephBean/Docs/tree/main/git


## git commit 명령어

git commit -m “타입: branch명 내용요약” ^ <br>
-m “무엇을, 왜 커밋했는지 작성” <br>


### 출력되는 커밋 내용 예시 (전체 예시는 디스코드에 있음)
```
기능추가: user 회원가입 기능 추가
회원가입 기능 추가 완료 (무엇을, 왜 작성)
```
<br>


## git add 취소

git reset HEAD .


## git commit 취소

git reset --soft HEAD~1


## Oneteam의 주의사항

1. main branch는 팀장만 건들 것.
2. pull 잘 활용할 것.
3. 이슈를 만들어 활용 할 것.


## git branch 작명소

- main 배포용(팀장만 만질 수 있음)
- dev (중간다리)
- order (창고_발주)
- stock (창고_재고/입고)
- comp (창고,제조_인사)
- biz (창고,제조_거래처관리)
- quo (제조_견적,수주)
- transport (제조_운송)
- prod (제조_재고)
  

## Repository Naming Conventio

1. 소문자를 사용해라 (use lower case)
2. 대시(-)를 사용해라 (use dashes)
3. 명확하게 작성해라 (be specific)
4. 일관성있게 작성해라 (be consistent)

## Formats for Commit Messages

<p align="center">
  <img src="https://blog.kakaocdn.net/dn/xteMz/btskha3GV9d/jJOTTbW8lzcKExUDpri7EK/img.png" height="250">
</p>

## Type

해당 커밋은 무엇에 대한 작업인지 키워드를 통해 표시합니다.

기능추가 : 새로운 기능 추가 커밋<br>
버그수정 : 버그 수정<br>
배포관련 : 빌드 관련 파일 수정<br>
문서: 문서 추가, 수정, 삭제<br>
코드수정 : 오타 등 간단한 수정 (로직 변경 X)<br>
리팩토링 : 코드 리팩토링 (코드 가독성, 유지보수 등을 위한 구조 재조정, 기능은 동일)<br>
테스트 : 테스트 코드 추가, 수정, 삭제 (로직 변경 X)<br>
CI관련 : CI 관련 커밋<br>
기타 : 기타 변경사항<br>

  
## 2.2 Subject
커밋 메세지의 제목입니다.

- 제목은 50자를 넘기지 않고, 마침표를 붙이지 않습니다.
- 제목에 커밋 타입을 함께 작성합니다.
- 과거 시제를 사용하지 않고 명령조로 작성합니다.
- 제목과 본문은 한 줄 띄워 분리합니다.
- 제목의 첫 글자는 반드시 대문자로 씁니다.
- 이슈에 관련된 내용이라면 이슈 번호를 붙힙니다.
- 

## 2.3. Body
커밋 메세지의 본문입니다. 

- 선택 사항이므로 모든 커밋에 작성할 필요는 없습니다.
- 한 줄에 72자를 넘기면 안 됩니다.
- 어떻게(how)보다 무엇(what), 왜(why)에 집중하여 내용을 작성합니다.
- 설명뿐만 아니라 커밋의 이유를 작성할 때도 작성합니다.


## git 규칙 만드는 이유
  - **서로 무슨 작업을 했는지 한 눈에 보이지 않음.**
  - **상대방이 작업한 내용을 위해 코드를 반드시 읽어봐야 함.**

사람마다 메세지가 완벽하게 일치할 필요는 없지만, <br>
통일성 있게 작성하여 메세지만으로 무슨 작업을 진행했는지 확인할 수 있도록 작성하는 것이 중요합니다.

## 1. Importance of Commit Message Rules

커밋 메세지를 작성할 때 규칙이 필요한 이유는 다음과 같습니다.

- 팀원과의 소통
- 편리한 과거의 기록 추적
- 이슈(issue) 관리
- 
## 결론 
  
커밋 메세지를 잘 작성하는 것은 협업에서 기본적인 습관입니다.

내가 다른 사람의 작업 내용을 한눈에 파악할 수 없다는 것을 알고 있다면 <br>  
다른 사람 역시 내가 작성한 커밋에 대한 내용을 파악하기 어렵다는 것을 인지해야합니다.

팀에서 함께 위와 같은 컨벤션으로 일할 수 있다면 히스토리를 파악하고 코드 리뷰도 짧은 시간 내에 해결할 수 있을 것 같다.
  
## Ref

- [좋은 git commit 메세지를 위한 영어 사전](https://blog.ull.im/engineering/2019/03/10/logs-on-git.html)
- [Commit message 줄바꿈](https://guuumi.tistory.com/128)
  
  
## 예시 

<p align="center">
  <img src="https://blog.kakaocdn.net/dn/dtCL21/btsklmCgFie/QDPW3LejAG0htEsJ3N628k/img.png" height="600">
</p>

##출처
https://parkdoyoung98.tistory.com/entry/Git-%EA%B7%9C%EC%B9%99%EC%A0%81%EC%9D%B8-Commit-%EB%A9%94%EC%84%B8%EC%A7%80%EB%A1%9C-%EA%B0%9C%EB%B0%9C%ED%8C%80-%ED%98%91%EC%97%85
