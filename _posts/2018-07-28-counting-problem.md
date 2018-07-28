---
layout: post
title:  "计数问题笔记"
date:   2018-07-28 12:00:00 +0800
categories: 数学
---

## 加法原理

分类相加。

注：属于“分类计数”。

要求：不重、不漏。


## 乘法原理

分步相乘。


## 排列组合


## 容斥原理

逐步淘汰。

注：属于“分类计数”。

容斥原理是组合计数领域中最核心的原理之一。

### 容斥原理的内容

#### 双重叠问题(容斥原理I)

$$A∪B=A+B-A∩B$$

说明：重叠部分重复计算了1次，需要扣除。

#### 三重叠问题(容斥原理II)

$$A∪B∪C=A+B+C-A∩B-B∩C-C∩A+A∩B∩C$$

### 容斥原理和加法原理的关系

考虑极限情况：当不存在重叠部分时，容斥原理就变成了加法原理。因此，加法原理是容斥原理的特殊情况，容斥原理是加法原理的一般推广。

### 容斥原理的一般解题步骤

“容斥”就是“包容”和“排斥”。首先计算包容，如果包容过多，就要进行排斥；如果排斥过多，又要进行包容；重复这个过程，直到得到最终结果。

### 容斥原理的应用

#### 双重叠问题

(1) 全班48人，37人完成了语文作业，42人完成了数学作业。请问有几人同时完成了语文和数学作业？

解：根据韦恩图可知，同时完成语文和数学作业的有$$37+42-48=31(人)$$。

注：相当于知道$$A$$、$$B$$和$$A∪B$$，求$$A∩B$$。

(2) 56名同学学习乐器，学习小提琴的有40人，学习钢琴的有30人。请问两种乐器都学习的有几人？只学习小提琴的有几人？

解：两种乐器都学习的有$$40+30-56=14(人)$$。只学习小提琴的有$$40-14=26(人)$$。

(3) 100以内不是3或5的倍数的正整数有几个？

解：100以内3的倍数有3到99共33个，5的倍数有5到100共20个，3和5的公倍数有15到90共6个，所以不是3或5的倍数的有$$100-(33+20-6)=53(个)$$。

注：$$33+20-6=47$$是3或5的倍数的集合的元素个数。

#### 三重叠问题

(1) 学校举行演讲比赛，获奖同学中有24名不是五年级的，有22名不是六年级的，五、六年级获奖同学共有10名。请问其他年级获奖同学共有几名？

解：设获奖同学五年级有A名，六年级有B名，其他年级有C名，则$$B+C=24$$，$$A+C=22$$，$$A+B=10$$。通过加减消元法(或容斥原理)可得$$C=18$$。

(2) 全班同学至少喜欢语、数、英三门中的一门，其中30人喜欢语文，32人喜欢数学，21人喜欢英语，15人既喜欢语文又喜欢数学，14人既喜欢数学又喜欢英语，12人既喜欢语文又喜欢英语，8人三门都喜欢。请问全班有多少人？

解：设喜欢语文的有A人，喜欢数学的有B人，喜欢英语的有C人，则$$A=30$$，$$B=32$$，$$C=21$$，$$A∩B=15$$，$$B∩C=14$$，$$A∩C=12$$，$$A∩B∩C=8$$。根据容斥原理II，全班有$$A∪B∪C=A+B+C-A∩B-B∩C-C∩A+A∩B∩C=30+32+21-15-14-12+8=50(人)$$。


## 递推方程


## 波利亚计数公式