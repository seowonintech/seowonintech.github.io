---
layout:     post
title:      "블로그에 글을 올려봅시다."
subtitle:   "어떻게 올리냐구요?"
date:       2017-03-31 12:10:00+09:00
author:     "Start Bootstrap"
header-img: "img/post-bg-06.jpg"
---

* Table of Contents
{:toc}

# 0. Jekyll 환경 설정

* [http://vjinn.github.io](http://vjinn.github.io) <= 여기에서 많이 배웠어요.

# 1. 서원인텍 블로그 Clone

```shell
$ git clone https://github.com/seowonintech/seowonintech.github.io.git
```

# 2. _posts 폴더에 글쓰기

>`/_post`폴더에 `YYYY-MM-DD-title.md` 형식의 파일 생성(포스트)

## 문법

[GFM (Github Flavored Markdown)](https://help.github.com/categories/writing-on-github/)

## 예시

>`/_post/2017-03-31-post-test.md`

## 확인(Jekyll이용해서 로컬에서 작성)

>아래 명령어를 실행하고 [localhost:4000](http://localhost:4000/)에서 확인

```
jekyll serve
```

# 3. Git add, commit, push

>Push하면 최종적으로 적용됩니다. [https://seowonintech.github.io](https://seowonintech.github.io)

Git을 모르시면 참고하세요.
* [Git](https://git-scm.com/book/ko/v2)
* [git - 간편 안내서](https://rogerdudler.github.io/git-guide/index.ko.html)