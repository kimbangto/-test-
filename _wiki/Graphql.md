---
layout  : wiki
title   : GraphQL
summary : 사용해가며 추가되는 지식
date    : 2022-11-15 15:03:25 +0900
updated : 2022-11-15 22:04:33 +0900
tag     : graphql apollo lacinia
toc     : true
public  : true
parent  : [[코드]]
latex   : false
---
* TOC
{:toc}

# 캐시 - Globally Unique IDs
```
엔드포인트 기반 API에서 클라이언트는 HTTP 캐싱을 사용하여 리소스 재요청을 쉽게 피하고 두 리소스가 동일한지 쉽게 식별할 수 있습니다. 이 API들의 URL이 클라이언트가 캐시를 구성하는데 사용할 수 있는 전역 고유 식별자 입니다. GraphQL에서는 주어진 객체에 대해 전역적으로 고유한 식별자를 제공하는 URL과 같은 원시값이 없습니다. 그러므로 클라이언트가 API를 사용할 수 있도록 이러한 식별자를 노출하는 것이 가장 좋습니다.
```
캐싱을 하기 위해 Globally Unique ID를 사용하는건 좋아보인다. 

# Query
## Fragment
# Resolver
## Type Resolver

# 참고자료
[GraphQL Caching](https://graphql-kr.github.io/learn/caching/) \
[웹 앱 API 개발을 위한 GraphQL](http://www.yes24.com/Product/Goods/81537382)
