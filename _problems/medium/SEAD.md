---
category_name: medium
problem_code: SEAD
problem_name: 'Sereja and D'
languages_supported:
    - ADA
    - ASM
    - BASH
    - BF
    - C
    - 'C99 strict'
    - CAML
    - CLOJ
    - CLPS
    - 'CPP 4.3.2'
    - 'CPP 4.9.2'
    - CPP14
    - CS2
    - D
    - ERL
    - FORT
    - FS
    - GO
    - HASK
    - ICK
    - ICON
    - JAVA
    - JS
    - 'LISP clisp'
    - 'LISP sbcl'
    - LUA
    - NEM
    - NICE
    - NODEJS
    - 'PAS fpc'
    - 'PAS gpc'
    - PERL
    - PERL6
    - PHP
    - PIKE
    - PRLG
    - PYTH
    - 'PYTH 3.4'
    - RUBY
    - SCALA
    - 'SCM guile'
    - 'SCM qobi'
    - ST
    - TCL
    - TEXT
    - WSPC
max_timelimit: '1'
source_sizelimit: '50000'
problem_author: sereja
problem_tester: null
date_added: 11-02-2014
tags:
    - binary
    - ltime09
    - medium
    - segment
    - sereja
    - sparse
editorial_url: 'http://discuss.codechef.com/problems/SEAD'
time:
    view_start_date: 1393146000
    submit_start_date: 1393146000
    visible_start_date: 1393146000
    end_date: 1735669800
    current: 1493557899
layout: problem
---
All submissions for this problem are available.###  Read problems statements in [Mandarin Chinese](http://www.codechef.com/download/translated/LTIME09/mandarin/SEAD.pdf) and [Russian](http://www.codechef.com/download/translated/LTIME09/russian/SEAD.pdf).

Sereja have array that consist of _n_ integers _a_1 ≤ _a_2 ≤ ... ≤ _a__n_. Now Sereja have _m_ queries as pair of two integers _t_ and _d_. Answer for query will be minimal integer _i_ such that exist some _k_ (_i_ ≤ _k_) for which _a__i_ + _d_ ≥ _a__i_ + 1, _a__i_ + 1 + _d_ ≥ _a__i_ + 2, ..., _a__k_ - 1 + _d_ ≥ _a__k_, _a__k_ ≤ _t_ and _a__k+1_ > _t_(if it exists).

Help Sereja, find the answer for each query.



### Input





First line of input contain integer _n_. Next line contain _n_ integers _a_1, _a_2, ..., _a__n_. Next line contain integer _m_. Next _m_ lines contain pairs of integers — queries.

### Output





For each query output answer.

### Constraints

- 1 ≤ _n_, _m_ ≤ 105.
- 1 ≤ _a__i_ ≤ 1066. 
   _a_1 ≤ _t_ ≤ 106
- 0 ≤ _d_ ≤ 106

### Example

**Input**

`<pre class="content">5<br></br>1 2 3 10 50<br></br>6<br></br>1 1<br></br>5 3<br></br>11 7<br></br>100000 1<br></br>1000000 1000000<br></br>11 6<br></br>`**Output**

`<pre class="content">1<br></br>1<br></br>1<br></br>5<br></br>1<br></br>4<br></br>`For **30 points(tests 0..20)** 1 ≤ _n_, _m_ ≤ 10000.

For **70 points(tests 21..33)** 1 ≤ _n_, _m_ ≤ 100000.