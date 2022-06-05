
# 개발자 북클럽 - Refactoring 2판 (2기)

> 2022.06.05부터 2022.07.31까지 8주 간 진행되는 Refactoring 2판 스터디입니다. <br>
> 마틴 파울러의 Refactoring 2판을 읽고 배운점을 남기고 피드백합니다.
> 
<br>

<img src="https://user-images.githubusercontent.com/69497936/172034496-d7e74b1c-7a67-456f-a3fa-3ce9193d90a4.jpg" alt="refactoring" width="820" height="400">

<br>

# 📒 진행 방식
- 매주 일요일 10시 스터디 진행한다.
- 토요일 오후 6시까지 '발표가 가능할 수준'까지 학습하며 학습 자료 PR 남긴다.
- 스터디 시작 전 일요일 9시까지 다른 팀원 코드 리뷰한다.
  - 최소 LGTM 라도 남겨주기
  - 리뷰가 완료되면 Approve 필수
- 스터디 당일, 모든 팀원이 돌아가며 학습 내용 발표한다.
  - 이해가 잘 되지 않는 부분이나 질문이 있다면 함께 피드백
  - 발표 및 피드백이 끝난 팀원의 PR은 merge
- 발표가 모두 종료되었다면 다음 스터디에서의 학습할 양과 담당자 정하고 스터디를 마친다.

<br>

# 🚩 스터디 참여 체크
스터디 참여는 2가지가 체크됩니다. 

1. 학습자료를 마감시간 전까지 작성했는가? 
2. 스터디 당일에 참석하고 발표를 진행했는가?

<br>

# 📅 일정

|일정|날짜|범위|담당자|완료여부|
|:--:|:--:|:--:|:--:|:--:|
|0주차|06.05 (일) 10:00|||✅|
|1주차|06.12 (일) 10:00|1장 (23~78)|
|2주차|06.19 (일) 10:00|2,3,4장 (114~152)|
|3주차|06.26 (일) 10:00|5,6장 (153~235)|
|4주차|07.03 (일) 10:00|7장 (236~277)|
|5주차|07.10 (일) 10:00|8,9장 (278~353)|
|6주차|07.17 (일) 10:00|10장 (354~412)|
|7주차|07.24 (일) 10:00|11장 (413~475)|
|8주차|07.31 (일) 10:00|12장 (476~536)|


<br>

# ⚙ 규칙
모든 작업은 Pull-Request 를 적극 활용하여 Review 와 커밋 기록을 남기는 것을 권장합니다.
### Directory Structure
- `/챕터/챕터번호_이니셜` 형식으로 업로드 해주세요.
  - ex) `Chapter01/01_hs.md`

### Branch
- `week_주차/이니셜` 형식으로 각 주차마다 새로운 브랜치에 작업해주세요.
  - ex) `week_1/hs`

### Commit Convention
- 커밋메시지는 아래와 같은 형식으로 작성
    - 한 주의 markdown문서를 시작할 때 
        :page_facing_up: Docs. {설명}
    -  새로운 내용 추가
        :pencil2: Add. {설명}  
    -  기존 내용을 업데이트한 경우  
        :bulb: Upt. {설명}
    -  오타 혹은 문장을 수정한 경우  
        :hammer: Fix. {설명}
    -  문서 스타일 및 포맷팅, 네이밍 변경  
         :art: Style. {설명}
    -  삭제한 경우  
        :fire: Del. {설명}
    -  되돌린 경우  
        :rewind: Rev. {설명}
    -  머지한 경우  
        :twisted_rightwards_arrows: Merge. {From브랜치명} into Main, {설명}
    - 개선해야하나 일단 커밋한 경우.    
        :poop: Bad. {설명}
-  그외 case는 추후 추가될 수 있습니다.
-  commit message가 고민될 때 [Git Commit Message 규칙](https://jason-api.tistory.com/89)
    
이모지 - gitmoji 를 이용하여 사용하면, 좀 더 쉽게 사용 가능  
>`npm -g install gitmoji-cli`

or
>`brew install gitmoji`

깃모지 커스텀 설정  
> `gitmoji --config`
```
? Enable automatic "git add ." No
? Select how emojis should be used in commits :smile:
? Enable signed commits No
? Enable scope prompt No
? Set gitmojis api url https://raw.githubusercontent.com/Developer-book-club//refactoring-2206/main/gitmojis.json
```
[https://raw.githubusercontent.com/Developer-book-club//refactoring-2206/main/gitmojis.json](https://raw.githubusercontent.com/Developer-book-club//refactoring-2206/main/gitmojis.json)


<br>

# 🙋‍♀ Members

<img align="left" width="40" height="40" src="https://avatars.githubusercontent.com/u/69497936?v=4">

[Hanseul-Lee](https://github.com/hanseul-lee) <br> - Front-end Developer

<img align="left" width="40" height="40" src="https://avatars.githubusercontent.com/u/81757940?v=4">

[Jason](https://github.com/bisor0627) <br> - App Developer

<img align="left" width="40" height="40" src="https://avatars.githubusercontent.com/u/35159888?v=4">

[Hoyoung-Kim](https://github.com/youngseo-im) <br> - Back-end Developer

</br>
