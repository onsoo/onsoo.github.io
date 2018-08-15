---
layout: post
title: 카테고리 만들기
category: help
tags: [using jekyll]
comments: true
---

# 카테고리 만들기

1. 'config.yml' 파일에서 nav에 category추가

    ```
    nav:
        Categories:
            - { category_name: '/blog/categories/#category_name' }
    ```
2. 폴더 '_posts'에서 md 확장자 파일로 쓰기
   
    * 이 때 편하게 하기 위해서, 폴더를 카테고리별로 관리하면 좋다.
    * 포트스 파일명은 해당 포스트의 url로 사용된다.

# 포스팅 하기

1. 우선 수정한 파일 모두 저장하기
2. commit 하고 push하면 끝  
