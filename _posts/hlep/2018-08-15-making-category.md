---
layout: post
title: 카테고리 만들기
category: help
tags: [using jekyll]
comments: true
---

## 카테고리 만들기

1. 'config.yml' 파일에서 nav에 category추가

    ```
    nav:
        Categories:
            - { category_name: '/blog/categories/#category_url' }
    ```
    * category_name : 카테고리 이름, post 작성시 'category'에 적는 이름과 동일
    * category_url : 해당 카테고리 포스트들의 url이 되는 부분
    * 한글명으로 카테고리는 만들 수 있다. *2018/08/21*
        * category_name 만 한글로 쓰기
        * category_name, category_url 둘다 한글로 쓰고
        * post 내 하위 폴더는 포스트를 관리하기 위함이라 위 두개와 상관없이 마음대로 쓰면 된다. 


2. 폴더 '_posts'에서 md 확장자 파일로 쓰기
   
    * 이 때 편하게 하기 위해서, 폴더를 카테고리별로 관리하면 좋다.
    * 포스트 파일명은 'yyyy-mm-dd-post-url.md'형태로 적는다.
        * yyyy-mm-dd 부분은 포스팅 날짜로 노출된다.
        * 해당 포스트의 url은 '/yyyy/mm/dd/post-url'이 된다.
    * 포스트 시작할 때 상단에 이렇게 포스트의 정보를 적고 시작한다.  
        ```
        ---
        layout: post
        title: 카테고리 만들기
        category: help
        tags: [using jekyll]
        comments: true
        ---
        ```


## 포스팅 하기

1. 우선 수정한 파일 모두 저장하기
2. commit 하고 push하면 끝  
