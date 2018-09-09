---
layout: post
title:  "分数计算练习题"
date:   2018-09-9 12:00:00 +0800
categories: 数学
---

# 分数计算练习题

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


## 解题技巧


## 错题巩固
