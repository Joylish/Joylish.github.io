---
layout: post
comments: true
date: 2019-06-14
title: "List 함수"
description: "append, insert, extend, remove, pop, sort, reverse, index, count"
subject: blog
categories: [python]
tags: [python, list함수]
---

<h3>list함수 사용 형식</h3>

$$
[ list 이름].[list 함수] (필요인자)
$$



<h3> append(), extend(), insert()</h3>

* **append(객체)**

  <u>object</u>를 list 맨 뒤에 추가한다.

* **extend(객체)**

  <u>iterable object(순서가 있는 객체)의 **모든 요소 **</u>를 list맨 뒤에 순서대로 추가한다.

* insert(*인덱스=위치*, *객체 1개* )

  단 하나의 객체를 list의 <u>특정 위치</u>에 추가한다. 

  

<h3> remove(), pop()</h3>

* remove(요소)

  인자가 주어지지 않을때(default): **에러**

  list에서 가장 먼저 나오는 특정요소를 삭제한다.

* **pop(*인덱스=위치* )**

  인자 주어지지 않을때(default): **list의 맨 마지막 요소**

  list에서 특정 위치에 있는 요소를 삭제한다. 



<h3>reverse(), sort()</h3>

* reverse()

  list의 요소들을 <u>역순으로 뒤집는다.</u>

* sort()

  list의 요소들을 정렬한다.

  * reverse = True 인자가 있을 때,

    list의 요소들을 <u>역순으로 정렬한다.</u>



<h3>index(), count()</h3>

* index(요소)

  list 내에서 해당 요소의 위치를 구해준다.

* count(요소)

  list내에서 해당 요소의 개수를 구해준다.