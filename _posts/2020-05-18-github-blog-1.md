---
title: Github 블로그 만들기
tags: github blog jekyll
---

  Github에서는 Github Repository를 이용하여 Static Website를 제공해주는 Github 
  Pages 서비스를 제공하기 때문에,
해당 서비스를 통하여 블로그를 구성할 수 있습니다. <!--more--> 
  이 글에서는 Github Pages 서비스와 Jekyll 이용하여 블로그를 만들기 위한 방법을 소개합니다.

# Github Repository 만들기
## Repository 만들기

Github 페이지 접속 후 Repository 생성페이지로 진입합니다.
![github Repository 새페이지](/assets/images/github-blog/github-repository-new.png)

Repository name 항목에 `username.github.io`와 같이 입력 후 `Public`로 생성합니다.

## 생성되어진 Repository 확인
![github Repository 만들기](/assets/images/github-blog/github-repository-initialize.png)

최초 생성되어진 Repository에서 `creating a new file`을 선택하여 index.html 파일을 생성합니다.

![index.html 파일 만들기](/assets/images/github-blog/github-repository-create-index.png)

index.html 내용 작성 후 해당파일을 Commit 하고,
잠시 후 등록하신 Repository의 도메인을 호출하시면 됩니다.

![URL 호출](/assets/images/github-blog/github-repository-call-index.png)


# Jekyll를 이용한 화면 구성

## Jeklly 환경 설정 및 리소스
  정적 웹사이트를 구성하기 위하여 [Jekyll](https://jekyllrb-ko.github.io/)를 이용하고자 합니다.
Jekyll를 사용하기 위해서는 ruby 개발환경이 설정되어있어야 하며, 자세한 내용은 [Documentation](https://jekyllrb-ko.github.io/docs/)을 확인하면 됩니다.

![URL 호출](/assets/images/github-blog/github-repository-clone.png)
원하시는 테마의 github에서 `Clone or Download`를 선택해서 테마의 리소스 파일을 받아주시면 됩니다.
  

## 자신의 Repository로 리소스 파일 이동
  테마 리소스 파일을 자신의 Repository로 복사후 해당 내용은 Commit 및 Push 하시면 됩니다.


# 자료출처
[Jekyll](https://jekyllrb-ko.github.io/)
