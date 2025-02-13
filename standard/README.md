# git 협업을 위한 standard
<br><br>

## 1. issue 하나가 끝나면 'dev'가 기준이다.

우리는 각 파트의 branch를 사용하여 commit를 합니다.<br>
issue를 마치고 나면 우리는 우리의 branch를 dev로 merge 합니다.<br>
그렇게 'dev'는 작업물의 기준이 됩니다.<br>
<br>

## 2. merge는 심사숙고
merge를 하게 되면 우리가 열심히 만든 작업물의 기준이 바뀝니다.<br>
이렇게 중요한 사항은 심사숙고를 할 필요가 있어 보입니다.<br>
생각을 3분만 하면 야근 30분이 줄어듭니다.
merge 전 행동 규칙을 제안합니다.
```
1. pull request (이하 pr)를 하기 전 팀장에게 확인해 줄 수 있는지 요청을 한다.
2. 팀장이 확인해 줄 수 있다면 pr을 한 뒤 검토 후 merge를 진행한다.
3. 팀장이 확인해 줄 수 없다면 팀원 2인을 구하여 본인을 포함한 3인이 확인 후 pr을 한다.
```
<br><br>

## 3. 자신의 파트만 건들도록 합니다.
우리가 작업물의 기준을 만드는 것은 모두가 같은 작업물을 가지고 작업을 하고 싶기 때문입니다.<br>
그런데 자신의 파트가 아닌 다른 사람의 작업물을 건들게 될 경우 서로 다른 파일이 되어버려 충돌이 생깁니다.<br>
이렇게 되면 현실에서도 충돌이 생길 수 있습니다.
<br><br>

## 4. 공용파일이 문제가 될 경우
공용으로 쓰는 파트가 문제가 되어 수정을 해야 할 경우 팀원에게 모두 공유하도록 합니다.<br>
공유를 하지 않게 될 경우 서로 다른 공용 파일을 가지게 되는 불상사가 생길 수 있습니다.<br>
공유를 하지 않은 자, 공유를 했음에도 공유 받지 않는 자 모두 처단의 대상이 됩니다.
<br><br>
