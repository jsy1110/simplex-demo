---
layout: post #Do not change.
category: [programming, life] #One, more categories or no at all.
title:  "무엇을 쓸 것인가? 블로그 시작"
date:   2022-02-17 09:00:00 +0900
author: zzi #Author's nick.
#nextPart: _posts/2021-06-16-syntax-example.md #Next part.
#prevPart: _posts/2021-01-30-example.md #Previous part.
#og_image: assets/example.png #Open Graph preview image.
og_description: "무엇을 쓸것인가? 고민" #Open Graph description.
fb_app_id: example
---
## 무엇을 쓸 것인가?

네이버 블로그, 티스토리, 브런치, GitHub Page, Notion 까지 사람들이 주로 사용하는 서비스를 고민했다. 최종 선택은 `GitHub Page` 이었는데 선택하기까지의 생각의 흐름을 정리해봤다.

1. **네이버 블로그** : 블로그 하면 네이버. 실제로 운영하지는 않지만 예전에 게이밍 모니터를 상품으로 준다는 말에 혹해서 컨텐츠를 올려본적이 있다.
찾아보니 미국 교환학생 시절 배웠던 Computer Graphics 관련 테스트 한 자료도 있고, 비공개로 필요한 자료를 한번씩 올리는 용도로 사용해왔다.
그런데 이번에 만들 블로그는 주로 개발에 관한 이야기가 주가 될것 같아서 네이버 블로그는 패스하기로 했다.
그리고 미안하지만 네이버 블로그는 뭔가 장사하는 느낌이라...

2. **티스토리** : 개발 블로그 하면 가장 먼저 생각나는 티스토리. 한참 유행할 때는 초대장 받기도 쉽지 않아서 희소성이 있었는데 요새는 글쎄...
그리고 티스토리로 만들어진 블로그들을 보면 구글AD들이 너무 덕지덕지 붙어있어서 보는 입장에서 지저분해보이는 블로그들이 많다.
오래된 블로그들은 어쩔수 없지만 새로 만드는 블로그를 굳이 티스토리로 할 필요가 있을까?
3. **브런치** : 깔끔하고 디자인도 내가 좋아하는 스타일이다. 다만 브런치는 `작가로 등록`되야 한다. 개발 이야기가 아닌 면접 후기, 워라벨 등 누구나 읽어보면 재밌게 볼 수 있는 내용이라면 한번 운영해 보고 싶긴 하다.  어쨌든 개인 기록의 의미가 큰 블로그로는 적절하지 않다.
4. **GitHub Page** : GitHub에서 Page라는 서비스를 이용해서 블로그를 만드는 방식이다. 이건 장단점이 너무나 명확하다.
장점 - 글로벌 서비스, 쉽게 구할 수 있는 테마, 개발자 친화적인 사이트
단점 - 쉽게 관리하기 위해 `jekyll` 이라는 서비스 이용이 거의 필수, 블로그 컨텐츠 업로드를 GitHub를 통해 올려야함(개발자가 아닌 사람이 쓰기엔 `commit, push` 등의 개념이 어렵다), 편집기가 제공되지 않음(아니 Markdown 문법을 직접 작성해서 글을 쓰라고?) 등등
아무리 봐도 장점에 비해 단점이 너무 크다.
5. **Notion** : 원래 블로그 용도로 나온 서비스가 아니다. 현재는 기존에 사용하던 onenote를 대신해서 개인용도로 쓰고 있는데, 팀 공유로 위키를 만들 수 있고, 페이지를 URL 로 만들어서 공유할 수 있다.  블로그 메인용 페이지를 만들고 하위페이지를 연결하는 방식으로 운영할 수 있겠지만 Markdown 문법으로 블로그 전체를 꾸미기엔 제약이 많다. 다만 적절한 Markdown 편집기가 없는 상황에서 Notion 자체는 좋은 툴이다. 특히, **대학교 이메일**을 이용할 경우 `프로 요금제로 무료 업그레이드`를 해줘서 감사할 따름
![Untitled 1](https://user-images.githubusercontent.com/6336815/154431431-c3f459d1-f06a-4045-b8a6-08019a943977.png)


## 왜 GitHub Page인가?

위에 언급했든 GitHub Page는 불편한점이 너무나 많다. 일단 Markdown 문법 사용부터 테마 적용까지 조금이라도 편하게 설치하기 위해서는 Jekyll 사용이 필수적이다. 때문에 GitHub Page 소개란에 보면 [Jekyll 을 공식적으로 소개](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)하고 있다. 
![Untitled 2](https://user-images.githubusercontent.com/6336815/154431735-0555f52d-3c35-41e6-842e-2e6ef28c387f.png)

심지어 Jekyll 사용을 위해서 Ruby, Bundler 등 설치가 필수적이다. 추가로 GitHub에서 repository 설정부터 신경쓸게 너무 많다.

이렇게 아무리 생각해도 단점이 너무 큰데 GitHub Page를 이용하게 된 가장 큰 이유는 Jekyll을 사용하면 Markdown 문법을 지원한다는 점이다. GitHub 공식 홈페이지를 보면 아래와 같이 적혀있다. (이런 Jekyll(제킬)...ㅈㅅ)

![Untitled 3](https://user-images.githubusercontent.com/6336815/154431851-69882d81-2a7b-4f2b-bce7-aa0681228329.png)

최근에 Notion을 사용하면서 Markdown 매력에 빠지게 됐는데 표 만드는것도 어렵고, 글씨체도 마음대로 못바꾸는 이 불편한걸 왜 쓰지? 로 시작했다가 이렇게 편할수가? 로 바뀌었다. 만약 네이버 블로그나 티스토리 등 웹 사이트에서 지원하는 html 기반의 편집기를 쓴다면 익숙하긴 하겠지만 신경쓸점도 많아진다. 근데 이 Markdown이라는 놈은 가볍게 글을 적을 때 부담이 없다.

그리고 GitHub Page는 `사용자id.github.io` 주소만 봐도 개발자 느낌나는게 싫지가 않다. 이제 문제는 앞으로 올릴 컨텐츠를 어떻게 작성할 것이냐이다. 일단 GitHub의 자체에서 Markdown 편집기까지는 아니지만 미리보기를 지원하기 때문에 간단한 수정을 할 수 있다. 하지만 어딘가 불편하다.

다음 글은 GitHub에서 쉽게 컨텐츠 작성하기 위해 사용하는 Tool을 소개하고,  이후에 `GitHub Page로 블로그 만들기` 에 대한 상세 방법을 작성하겠다.

![Untitled 4](https://user-images.githubusercontent.com/6336815/154431906-ea4ec16e-e7b0-4659-962e-d8327cb22a39.png)

![Untitled 5](https://user-images.githubusercontent.com/6336815/154431970-a9e23f2a-60ea-4331-93df-090d4f9444cc.png)