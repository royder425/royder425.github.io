---
layout: post
title: "Github 블로그 만들기 5탄 - Jekyll 설정하기"
subtitle: "Creating a Github Blog Part 5 - Jekyll setting"
categories: Blog, Github, Ruby, Jekyll
---

드디어 Blog를 로컬 환경에서 열 수 있게 되었다.

겨우 열었지만 이제 시작이다.

아 참고로 저번 편에서 Git Bash로 열었지만 Ruby로도 열 수 있다.

![3](https://github.com/royder425/royder425.github.io/assets/155123794/7f39f168-187f-410f-9b3a-3b4eac1c72cc)

Window > Start Command Prompt with Ruby > 실행


![3](https://github.com/royder425/royder425.github.io/assets/155123794/73243b2d-d732-4566-84bb-0d3d2b4a88fc)

<br><br>Prompt 화면에서 블로그 파일들이 있는 곳으로 이동

```ruby
cd [블로그 파일 경로]
```

그 다음에 서버 실행

```ruby
bundle exec jekyll s
```
![3](https://github.com/royder425/royder425.github.io/assets/155123794/6ce8679b-b79e-4312-a610-1cf3e31fb42f)

이런식으로 Server address가 뜨면 성공적으로 서버가 열렸다.

서버를 닫는 방법은 Ruby 화면에서 Ctrl + C를 누르면 서버를 닫겠냐는 말을 해준다.

![1](https://github.com/royder425/royder425.github.io/assets/155123794/a1c0cbf7-d7e8-47db-b088-79489c6978ff)

웹 브라우저에 127.0.0.1:4000를 넣고 Enter

나는 네이버 웨일을 썻지만 자신이 원하는 웹 브라우저에서 들어가주면 된다.

![2](https://github.com/royder425/royder425.github.io/assets/155123794/61dda5e3-bfb1-47c9-a689-9ed76ed7b5a7)

들어오면 짜잔!

내 블로그가 개설 되었다.

이제부터 간단하게 블로그 설정을 바꿔보자

Jekyll은 기본적으로 “**_config.yml”** 파일로 설정하는 것 같다.

왜 같냐고 말 하냐면 나도 잘 모르고 만들고 있는 중이라서 나도 하면서 배워야 한다.

혹시 매끄러운 Github Blog를 원하는 사람이라면 아마 내 블로그 글이 별로 도움이 안 될 것 같은데….. 뭐 어때 누군가는 나와 같이 이렇게 막무가내로 만들고 싶어할 수 있으니깐…

“**_config.yml”**  파일은 블로그 파일이 모여있는 곳에 있다.

아마도 폴더 명이 [github 아이디].github.io 폴더에 들어있을 것 이다.

![3](https://github.com/royder425/royder425.github.io/assets/155123794/80e6f57e-9362-4100-a604-e2653785419b)

“**_config.yml”**  파일을 열어야 하는데 나는 VScode를 사용해서 열었다.

내가 VScode를 사용한 이유는 그냥 내가 처음 프로그래밍을 접했을 때 다녔던 회사에서 개발자 분이 VScode를 사용하고 계셨기 때문이다.

혹시 다른 걸 사용하고 싶으면 뭐 본인 마음이니까 알아서 다운 받아서 열어보시길 바란다.

![4](https://github.com/royder425/royder425.github.io/assets/155123794/b7910eb9-2016-49f0-b93e-901c72c0c0eb)

파일을 열면 이런 식으로 영어로 적어져 있다.

물론 하나 하나 다 읽을 순 있겠지만 지금은 영어 공부하는 시간이 아니니깐 간단하게 넘어가려고 구글 번역 기능을 이용하거나 #로 시작하는 글은 과감하게 넘기고 바로 Jekyll yml파일에 대해서 구글링을 했다.

https://jekyllrb.com/docs/variables/

Jekyll 사이트에 들어가면 아주 자세하게 나와있다.

나의 경우에는 “**_config.yml”** 여기 파일에서 궁금한 것을 Jekyll 사이트에서 검색하면서 하나 하나 찾았다.

기본적으로 **“Title”** 이건 뭐 따로 적을 필요가 없을 것 같다.

![5](https://github.com/royder425/royder425.github.io/assets/155123794/60c3324e-b66e-4a67-86c3-d1e9e2fcd2a1)

**“Title”** 을 Royblog로 변경하니 실제로 로컬 서버에서 열린 블로그에 반영이 되어있다.

근데 폰트? 글자? 가 뭔가 별로니 나중에 바꾸려고 한다.

일단 뭘 바꿔야 뭘 바뀌는지 알아 보는 게 먼저인 것 같다.

 **“email”, “author”** 이건 못 찾았다.

일단 넘어가고 다른 걸 찾아야겠다.

근데 다음편에~