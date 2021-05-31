# ✍ 스파르타 스터디 클럽  
[**[공부 시간을 관리합시다! 스파르타 스터디 클럽 백엔드 리포지토리에 오신 여러분을 환영합니다!]**](https://tristy.tistory.com/)  

**나만의 공부 시간 관리! 스파르타 스터디 클럽과 함께 하세요~**

오늘 하루 나는 몇시간 동안 공부했을까?  
스파르타 스터디 클럽에서는 개인 공부 시간도 체크할 수 있고, 그룹별로 체크해 경쟁할 수도 있답니다.  

시간 내에 모든 목표를 달성하세요! 학습 목표를 확실하게 관리해드립니다!  

<br/>
<br/>

[**[Fornt-End Github]**](https://github.com/miniPinetree/Sparta-Study-Club)  
[**[Back-End Github]**](https://github.com/sanchoco/SpartaStudyClub)  
[**[Demo Video]**](https://www.youtube.com/watch?v=PO9PinZHFJs&t=4s)  

<br/>
<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/52685665/120208943-08cded00-c269-11eb-87d0-84965791d78b.png"></p>  
<p align="center"><img src="https://user-images.githubusercontent.com/58046372/115713603-2b8afd00-a3b1-11eb-8357-62f4a9676f8b.gif"></p> 

<br/>
<br/>

🎮 스파르타 코딩 클럽 기능  
-------------  

- 매일 매일 학습 목표와 시간을 설정하고 완료한 것은 체크할 수 있어요!
- 최근 5일간 학습한 그래프를 볼 수 있고 달력을 통해 이전 기록들을 볼 수 있어요! 달성률이 높은 날일수록 색이 진하게 보입니다.
- 채팅을 통해 다른 유저를 응원하고 소통할 수 있어요~
- 스터디 그룹에 가입하여 비슷한 목표를 가진 사람들끼리 경쟁하고 랭킹을 볼 수 있어요.
- 스터디 그룹 내 게시판을 활용하여 정보를 교류하거나 응원의 메세지를 남길 수 있습니다!

<br/>
<br/>

🤔 Team 
-------------  
[Front-End] [고미송](https://github.com/miniPinetree)  
[Back-End] 원동균, [조상균](https://github.com/sanchoco)  

- **공통** :  프로젝트(API, DB) 설계 및 세팅
- **조상균** : 회원가입, 로그인, 미들웨어 및 인증, 채팅 기능 [``src/user``, ``src/middleware``, ``src/chat``]
- **원동균** : 나의 목표 설정 및 관리, 스터디 그룹 기능 [``src/quest``, ``src/group``, ``src/comment``]

<br/>
<br/>


🤔 프로젝트 개요
-------------  
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li><b>진행 날짜 - 2021.04.09 ~ 2021.04.22 </b></li>
<li><b>목적 - 팀원들과 함께, 백엔드와 프론트 엔드의 역할을 맡아 주제를 선정하고 프로젝트를 진행하자</b></li>
<li><b>필수 포함 사항</b></li>
</ul>

<br/>
<br/>

<p align="center"><img src="https://user-images.githubusercontent.com/52685665/120211266-b04c1f00-c26b-11eb-880d-bf4c33efa920.png"></p>

<br/>
<br/>


😎 Architecture
-----------------  

<p align="center"><img src="https://user-images.githubusercontent.com/52685665/120212383-e50ca600-c26c-11eb-8ae8-958871f40984.png"></p>

<br/>
<br/>

😎 ERD
-----------------  

<p align="center"><img src="https://user-images.githubusercontent.com/52685665/120213443-2baed000-c26e-11eb-9872-6f84bcf0eb71.png"></p>

<br/>
<br/>


🤩 나의 업무   
-----------------  
  
* 조장 역할을 맡아 팀원들의 업무 분담 및 관리
* 데이터베이스 설계 및 관리
* 나의 목표 설정 API 구성
* 스터디 그룹 API 구성

<br/>
<br/>


🤭 이번 프로젝트를 하며 새롭게 배운 것
-----------------
1.  Nest JS 사용해보기  
2.  sequelize 대신 TypeOrm 사용해보기  
3.  JavaScript 대신 TypeScript 사용해보기    

<br/>
<br/>

🤭 Nest Js를 사용한 이유  
-----------------

<br/>
<br/>

Express + JavaScript 프로젝트를 하다가 다음과 같은 불편함을 느꼈습니다.  

<br/>

```bash
1. Express 환경에서는 모든것을 사용자 스스로 만져야 하다보니, 협업 환경을 만드는데 생각보다 시간이 걸린다.  
2. JavaScript 고유의 Type Safe 문제가 있어서 오류가 발생했던 적이 많았습니다.  
```

<br/>

그래서 찾던 중 Nest Js라는 프레임워크를 찾을 수 있었습니다.  

사실 이번 프로젝트에서 Nest Js가 어렵거나 난해했으면, 불편함을 감수하고 그냥 Express를 사용했을 것 같습니다.  
하지만 Nest Js가 낯설어서 처음에 조금 헤맨 것 말고는 크게 어려웠던 점은 없었으며, 오히려 Express보다 협업할 때 더 편했습니다.  

저는 저번 인스타 클론 코딩 때 Express를 사용했고, MVC 구조 비슷하게 만들어서 백앤드 파일 구조를 만들었으며, 백앤드 작업을 하는 팀원에게 작업을 할당해주었습니다. 문제는 Express에서 그러한 구조를 만들려면 처음부터 끝까지 하나하나 만들어 가야 하고, 여기에 쏟은 시간이 엄청났었습니다. 때문에 다음에는 Nest를 사용해서 프로젝트를 해야겠다고 마음먹었죠.  

Nest Js를 실제로 써보니까. 정말 간단하고 괜찮은 프레임워크라는 생각이 들었습니다.  
파일 구조를 힘들게 마우스 오른쪽 눌러가며 만들지 않아도, Nest Js 명령어만 몇 줄 사용하면 간단하게 내가 원하는 파일 구조를 만들어 주었습니다. 그리고 Nest Js와 궁합이 잘 맞는다고 알려진 TypeScript를 사용했기 때문에 타입으로 인해 발생하는 문법 오류들이 많이 줄어들게 됐습니다.  

요번에 저와 함께 백앤드를 작업한 팀원 분도 요번에 제가 졸라서(?) Nest Js를 하게 되었는데,  
그분도 처음에만 힘들었지, 가면 갈수록 express보다 편한 것 같다고 말씀해 주셨습니다.  

<br/>
<br/>


😭 이번 프로젝트를 하며 어려웠던 것  
-----------------  

<br/>
<br/>

### 1. Nest Js 배우기  

Nest Js를 잘 쓰려면 학습은 필수였습니다. 마땅히 괜찮은 강의를 찾지 못하던 와중 Nomad Corder 강의에서 Nest 무료 강의를 발견할 수 있었습니다.  
초보들이 이해하기에 정말 좋으니 Nest Js 도전해보실 분들은 꼭 한번 들으셨으면 좋겠습니다.  

[**노마드코더 Nest Js 강의**](https://nomadcoders.co/nestjs-fundamentals/lobby)


<br/>
<br/>

### 2. TypeOrm 사용방법  

이번 프로젝트를 하며 제일 시간이 오래 걸리고 어려웠던 것은, TypeOrm 사용방법이었습니다.  
일단 항해 99에서 Nest JS + TypeOrm으로 하는 조가 우리밖에 없었고, 정보를 얻는 것이 쉽지 않았습니다.  

오랜시간 구글링한 끝에 TypeOrm 학습에 유용한 링크 2개를 찾았고, 시행착오를 거쳐서 문제를 해결할 수 있었습니다.  

TypeOrm도 find, findOne 메서드 등을 지원하며, 이런 메서드들만 사용해도 어느 정도 문제는 해결할 수 있습니다.  
하지만 조금 복잡한 조건의 조인이 들어가거나, 쿼리가 깊어지는 경우는 TypeOrm의 createQueryBuilder로 해결하시길 바랍니다.  
TypeOrm의 공식 깃허브에서도 createQueryBuilder의 사용을 권장하고, 궁금한 게 있어서 글을 올려도 거의 대부분 createQueryBuilder를 사용하는 방법을 알려주셨습니다.  

[**TypeOrm 번역 블로그**](https://yangeok.github.io/orm/2020/12/14/typeorm-decorators.html)
[**TypeOrm 공식 깃허브**](https://github.com/typeorm/typeorm/blob/master/docs/select-query-builder.md)

<br/>
<br/>

🛠 이번 프로젝트에서 보완해야 할 점  
-----------------  

<br/>
<br/>

### 1. Try Catch문의 error 메시지 보완

Try Catch문을 신경쓰지 않고 막 쓰고, error 발생 시 메시지를 전부 fail로 통일해서 사용했습니다.  
그런식으로 작업을 진행하다 보니 테스트를 해도 어디서 오류가 났는지 알기 힘들었고, 어떤 오류인지 확인하기 힘들었습니다.  

그래서 다음 프로젝트 부터는 무언가 구분되는 error 메시지 처리를 해놔야겠다고 생각했습니다.  

<br/>
<br/>
