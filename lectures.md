---
layout: page
title: Lecture Schedule
nav_exclude: false
description: The weekly event schedule.
---

# Lecture Schedule

<!--iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSyvXLfZws2U5pKoXoKAH5apWmNX1ab-aD5PW1cpRgX3MUQ52zCPAeurXtdGfA5nKZmjSGIA0di7q8r/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSczFyCmp6guNbmXHgm_DD2gdC0hkAEtfweRANJWeRqORIYPv4hBdgXYxaJAYwsiszgJ-htX1pRivDi/pubhtml?gid=1299710416&amp;single=true&amp;widget=true&amp;headers=false" style="border:0" width="800" height="600" frameborder="0" scrolling="no"></iframe>-->


| Start Date | End Date | Topic                                    | Required Reading                                       | Additional Resources |
| ---------- | -------- | ---------------------------------------- | ------------------------------------------------------ | -------------------- |
|  23 July   |  23 July | [Introduction](01-intro.pdf)                             |  |  |
|  23 July   |  27 July | [Asymptotic Analysis of Algorithms](02-asymptotic.pdf)    |  GT Chapter 4.1, 4.2  |
|     |   | [Practice Assignment 1](PracA1.pdf)    |   |
|  27 July   |  30 July | [C++ Syntax & Object Oriented Programming](03-oop.pdf)   |  GT Chapters 1, 2   |
|  30 July   |  03 Aug  | [Arrays & Linked Lists](04-arraylists.pdf)   |   GT Chapters 3.1-3.4   |
|  03 Aug   |  06 Aug  | [Stacks & Amortized Analysis](05-stacks.pdf)   |   GT Chapters 5.1   |
|  06 Aug   |  06 Aug  | [Queues](06-queues.pdf)   |   GT Chapters 5.2, 5.3   |
|  10 Aug   |  10 Aug  | [Recursion](07-recursion.pdf)   |   GT Chapters 3.5   |
|     |   | [Practice Assignment 2](PracA2.pdf)    |   |
| 10 Aug    | 25 Aug   | [Programming Assignment 1](A1.pdf)    |   |
|  10 Aug   |  13 Aug  | [Trees](08-trees.pdf)   |   GT Chapters 7.1, 7.2   |

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
