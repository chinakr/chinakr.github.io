---
layout: post
title:  "带余除法笔记"
date:   2018-09-10 12:00:00 +0800
categories: 数学
---

# 带余除法笔记

<script>
function hide_answers() {
  //alert('隐藏所有答案');
  var paragraphs = document.getElementsByTagName('p');
  var answers = [];
  for (var i = 0; i < paragraphs.length; i++) {
    console.log(paragraphs[i].innerHTML == /^答案：/);
    if (/^答案/.test(paragraphs[i].innerHTML)) {
      answers.push(paragraphs[i]);
    }
  }
  //console.log(answers);
  button = document.getElementById('show_or_hide_answers');
  if (button.innerHTML == '隐藏答案') {
    button.innerHTML = '显示答案';
    display(answers, 'hide');
  } else if (button.innerHTML == '显示答案') {
    button.innerHTML = '隐藏答案';
    display(answers, 'show');
  }
}
function display(elements, status) {
  for (var i = 0; i < elements.length; i++) {
    if (status == 'hide') {
      elements[i].style.display = 'none';
    } else if (status == 'show') {
      elements[i].style.display = 'block';
    }
  }
}
</script>

<button id="show_or_hide_answers" onclick="hide_answers()">隐藏答案</button>


## 带余除法的基本概念

1.带余除法的定义：$$A \div B = a \cdots r$$

示例：$$17\div5=3 \cdots 2$$

2.大小：$$余<除$$ 即 $$r < B$$

3.化除为乘：$$A\div B=a…r\Rightarrow A= B\cdot a + r$$

4.最值：$$A_{min} = B_{min} \cdot a + r$$

5.分解：$$A - r = B \cdot a \Rightarrow B \mid A-r, a \mid A-r$$


## 余数的性质

1.可加性：$$A \div C = a \cdots r_{A}, B \div C = b \cdots r_{B} \Rightarrow (A+B) \div C \cdots (r_{A} + r_{B})$$ (注：如果$$r_{A} + r_{B} > C$$，那么余数为$$r_{A} + r_{B} - C$$)

2.可减性：$$A \div C = a \cdots r_{A}, B \div C = b \cdots r_{B} \Rightarrow (A-B) \div C \cdots (r_{A} - r_{B})$$ (注：如果$$r_{A} - r_{B} < 0$$，那么余数为$$r_{A} - r_{B} + C$$)

3.可乘性：$$A \div C = a \cdots r_{A}, B \div C = b \cdots r_{B} \Rightarrow (A \cdot B) \div C \cdots (r_{A} \cdot r_{B})$$ (注：如果$$r_{A} \cdot r_{B} > C$$，那么余数为$$r_{A} \cdot r_{B} - n \cdot C$$，n为自然数，用于确保余数大于0小于除数)

注：没有“可减性”。

4.周期性

注：余数的周期性是余数的可加性或可乘性的结果。

## 同余定理

1.同余的定义：除以相同的数，余数相同。即$$A \div C \cdots r, B \div C \cdots r$$。

2.同余定理：同余的两个数相减，差一定是除数的倍数。即$$C \mid (A - B)$$。

证明：$$A \div C = a \cdots r, B \div C = b \cdots r \Rightarrow A = C \cdot a + r, B = C \cdot c + r \Rightarrow A - C = (a - c) \cdot C \Rightarrow C \mid (A - C)$$

注：在应用同余定理时，经常需要通过调整余数来构造同余。
