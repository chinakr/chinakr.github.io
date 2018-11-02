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


## 基本概念

分数(fen1 shu4)：[名]把一个单位分成若干等份，表示其中的一份或几份的数，是除法的一种书写形式，如$$\frac{2}{5}$$（读作五分之二），$$2\frac{3}{7}$$（读作二又七分之三）。在分数中，符号“$$\frac{}{}$$”叫作分数线，相当于除号；分数线上面的数叫做分子，相当于被除数，如$$\frac{2}{5}$$中的2；分数线下面的数叫作分母，相当于除数，如$$\frac{2}{5}$$中的5。

分式(fen1 shi4)：[名]有除法运算，而且除式中含有字母的有理式，如$$\frac{1}{x}$$，$$\frac{a}{b-c^2}$$。

有理式：[名]没有开方运算，或有开方运算但被开方数不含字母的代数式。如$$a^2+b$$，$$\frac{\sqrt{2}}{x-y}$$。

代数式：[名]用代数运算法（加、减、乘、除、乘方、开方）把数和表示数的字母联结起来的式子。

## 解题技巧

1. 先约分，再进行其他运算。
2. 结果可以写成带分数形式，也可以写成假分数形式，但不管哪种形式，都必须是最简形式（不能再约分）。
3. 除以一个数，等于乘以这个数的倒数。
4.当分数运算中出现小数时，根据实际情况，可以把小数化为分数，或者小数直接和分母约分后再和分子相乘。
5. 带分数在加减法运算中，整数部分可以先运算。
6. 带分数在乘除法运算中，要先化成假分数再进行其他运算。
7. 整数混合运算中的巧算方法同样可以有条件地运用，例如改变运算顺序、凑整等。


## 错题巩固

1.$$\frac{25}{5}-\frac{10}{5}=$$

答案：3

2.$$\frac{1}{2}+\frac{1}{5}+\frac{1}{2}=$$

答案：$$1\frac{1}{5}$$

3.$$\frac{7}{9}+\frac{1}{9}+\frac{4}{9}=$$

答案：$$\frac{4}{3}$$

4.$$\frac{21}{13}-1+\frac{3}{13}=$$

答案：$$\frac{11}{13}$$

5.$$\frac{3}{5}+\frac{1}{15}=$$

答案：$$\frac{2}{3}$$

6.$$1-\frac{7}{12}=$$

答案：$$\frac{5}{12}$$

7.$$\frac{11}{12}-(\frac{1}{6}+\frac{1}{8})=$$

答案：$$\frac{5}{8}$$

8.$$\frac{7}{12}-(\frac{3}{4}-\frac{1}{2})=$$

答案：$$\frac{1}{3}$$

9.$$\frac{1}{5}+\frac{7}{15}+\frac{4}{15}=$$

答案：$$\frac{14}{15}$$

10.$$\frac{7}{10}-（\frac{3}{4}-\frac{2}{5})=$$

答案：$$\frac{7}{20}$$

11.$$5\times\frac{3}{10}=$$

答案：$$\frac{3}{2}$$

12.$$\frac{3}{8}\times12$$

答案：$$\frac{9}{2}$$

13.$$17\times\frac{4}{85}=$$

答案：$$\frac{4}{5}$$

14.$$91\times\frac{3}{26}=$$

答案：$$\frac{21}{2}$$

15.$$121\times\frac{7}{11}=$$

答案：77

16.$$289\times\frac{7}{17}=$$

答案：119

17.$$23\times\frac{46}{529}=$$

答案：2

18.$$24\times\frac{48}{576}=$$

答案：2

19.$$25\times\frac{35}{125}=$$

答案：7

20.$$27\times\frac{3}{18}=$$

答案：$$\frac{9}{2}$$

21.$$35\times\frac{7}{15}=$$

答案：$$\frac{49}{3}$$

22.$$65\times\frac{5}{26}=$$

答案：$$\frac{25}{2}$$

23.$$75\times\frac{10}{125}=$$

答案：6

24.$$28\times\frac{3}{42}=$$

答案：2

25.$$85\times\frac{2}{51}=$$

答案：$$\frac{170}{51}$$

26.$$\frac{8}{76}\times\frac{57}{64}=$$

答案：$$\frac{3}{32}$$

27.$$\frac{15}{32}\times\frac{64}{25}=$$

答案：$$\frac{6}{5}$$

28.$$\frac{63}{54}\times\frac{9}{14}=$$

答案：$$\frac{3}{4}$$

29.$$\frac{22}{33}\times\frac{35}{77}=$$

答案：$$\frac{10}{33}$$

30.$$\frac{29}{42}\times\frac{56}{87}=$$

答案：$$\frac{4}{9}$$

31.$$\frac{26}{63}\times\frac{28}{39}=$$

答案：$$\frac{8}{27}$$

32.$$\frac{30}{33}\times\frac{22}{50}=$$

答案：$$\frac{2}{5}$$

33.$$\frac{2}{33}\times\frac{121}{77}=$$

答案：$$\frac{2}{21}$$

34.$$\frac{50}{48}\times\frac{64}{75}=$$

答案：$$\frac{8}{9}$$

35.$$\frac{16}{36}\times\frac{54}{8}=$$

答案：3

36.$$\frac{10}{32}\times\frac{4}{55}=$$

答案：$$\frac{1}{44}$$

37.$$\frac{54}{12}\times\frac{2}{81}=$$

答案：$$\frac{1}{9}$$

38.$$\frac{52}{64}\times\frac{32}{78}=$$

答案：$$\frac{1}{3}$$

39.$$4.4\times\frac{4}{11}=$$

答案：1.6

40.$$0.85\times1.01=$$

答案：0.8585

41.$$5.2\times3.05\times4.8=$$

答案：$$\frac{9516}{125}$$

42.$$\frac{6}{5}\div3=$$

答案：$$\frac{2}{5}$$

43.$$\frac{6}{7}\div3=$$

答案：$$\frac{2}{7}$$

44.$$\frac{11}{18}\div22$$

答案：$$\frac{1}{36}$$

45.$$1\frac{1}{2}\div2=$$

答案：$$\frac{3}{4}$$

46.$$3\frac{1}{4}\div2=$$

答案：$$\frac{13}{8}$$

47.$$(\frac{2}{3}+2)\div8=$$

答案：$$\frac{1}{3}$$

48.$$(2-\frac{1}{3})\div3=$$

答案：$$\frac{5}{9}$$

49.$$(3-2\frac{1}{2})\div3=$$

答案：$$\frac{1}{6}$$

50.$$(10-5\frac{2}{3})\div13=$$

答案：$$\frac{1}{3}$$

51.$$(8+4\frac{1}{2})\div5=$$

答案：$$\frac{5}{2}$$

52.$$(4-2\frac{1}{2})\div3$$

答案：$$\frac{1}{2}$$

53.$$(\frac{1}{3}+\frac{1}{2})\div5=$$

答案：$$\frac{1}{6}$$

54.$$(1\frac{2}{3}-\frac{1}{6})\div5=$$

答案：$$\frac{3}{10}$$

55.$$(\frac{1}{2}\times5\frac{1}{2})\div2=$$

答案：$$\frac{11}{8}$$

56.$$4\div\frac{4}{5}=$$

答案：5

57.$$3\div\frac{3}{7}=$$

答案：7

58.$$7\div\frac{7}{11}=$$

答案：11

59.$$2\div\frac{4}{3}=$$

答案：$$\frac{3}{2}$$

60.$$96\div1\frac{7}{9}=$$

答案：54

61.$$11\div\frac{10}{2}=$$

答案：$$\frac{11}{5}$$

62.$$14\div1\frac{1}{5}=$$

答案：$$\frac{35}{3}$$

63.$$8\div5\frac{4}{5}=$$

答案：$$\frac{40}{29}$$

64.$$21\div3\frac{1}{2}=$$

答案：6

65.$$6\div4\frac{7}{14}=$$

答案：$$\frac{4}{3}$$

66.$$18\div5\frac{4}{5}=$$

答案：$$\frac{90}{29}$$

67.$$13\div8\frac{2}{3}=$$

答案：$$\frac{3}{2}$$

68.$$28\div7\frac{1}{3}=$$

答案：$$\frac{42}{11}$$

69.$$19\div(\frac{9}{14}+\frac{7}{14})=$$

答案：$$\frac{133}{8}$$

70.$$\frac{5}{4}\div\frac{9}{3}=$$

答案：$$\frac{5}{12}$$

71.$$\frac{1}{6}+\frac{1}{6}+\frac{1}{3}=$$

答案：$$\frac{2}{3}$$

72.$$2-\frac{1}{6}-\frac{1}{3}=$$

答案：$$1\frac{1}{2}$$

73.$$\frac{1}{5}\times\frac{1}{5}-\frac{1}{5}\times\frac{1}{5}=$$

答案：0

74.$$\frac{7}{19}\times\frac{7}{19}-\frac{7}{19}\times\frac{7}{19}=$$

答案：0

75.$$\frac{2}{3}\times3+\frac{1}{3}=$$

答案：$$2\frac{1}{3}$$

76.$$\frac{4}{9}\times3+\frac{1}{4}=$$

答案：$$\frac{19}{12}$$

77.$$\frac{2}{3}\times5-\frac{1}{3}=$$

答案：3

78.$$\frac{1}{2}\times\frac{1}{3}+\frac{1}{6}=$$

答案：$$\frac{1}{3}$$

79.$$\frac{7}{10}-\frac{3}{8}\times\frac{4}{5}=$$

答案：$$\frac{2}{5}$$

80.$$\frac{2}{7}\times\frac{2}{3}\times14=$$

答案：$$\frac{8}{3}$$

81.$$1-\frac{5}{18}\div1\frac{1}{3}=$$

答案：$$\frac{19}{24}$$

82.$$27\div\frac{9}{4}\div\frac{3}{5}=$$

答案：20。

83.$$(\frac{3}{5}+\frac{3}{8})\div\frac{4}{5}=$$

答案：$$\frac{39}{32}$$

84.$$\frac{4}{7}\div\frac{1}{14}\div1\frac{1}{14}=$$

答案：$$\frac{112}{15}$$

85.$$\frac{7}{20}\div\frac{14}{15}\div\frac{3}{5}=$$

答案：$$\frac{5}{8}$$

86.$$10\div\frac{5}{8}\div\frac{2}{5}\div{3}=$$

答案：$$\frac{40}{3}$$

87.$$\frac{6}{7}\times\frac{2}{3}\div4\div\frac{8}{5}=$$

答案：$$\frac{5}{56}$$

88.$$\frac{12}{58}\times\frac{29}{36}+\frac{3}{5}\times\frac{2}{3}=$$

答案：$$\frac{17}{30}$$

89.$$(\frac{11}{12}-\frac{5}{6}+\frac{1}{12})\times\frac{4}{5}=$$

答案：$$\frac{2}{15}$$

90.$$(\frac{2}{3}\div\frac{2}{3}\div\frac{2}{3}\div\frac{2}{3})=$$

答案：$$\frac{9}{4}$$

91.$$\frac{1}{3}\times\frac{6}{5}\div(0.5+\frac{1}{3})=$$

答案：$$\frac{12}{25}$$

92.$$\frac{2}{3}\times\frac{10}{3}\div(\frac{3}{5}\div5\frac{3}{5})=$$

答案：$$\frac{560}{27}$$

93.$$0.375\times\frac{4}{5}\div(\frac{4}{5}\div8)=$$

答案：3

94.$$(\frac{6}{7}\div\frac{2}{3}+\frac{1}{12})\times\frac{2}{3}=$$

答案：$$\frac{115}{126}$$

95.$$(\frac{4}{7}+\frac{5}{7}\times\frac{2}{3})\div\frac{2}{5}=$$

答案：$$\frac{55}{21}$$

96.$$(1-\frac{2}{5}\div\frac{3}{5}\div\frac{5}{6})\div3\frac{3}{5}=$$

答案：$$\frac{1}{18}$$

97.$$\frac{3}{2}+(2\frac{1}{3}-1\frac{1}{2})\div\frac{1}{3}=$$

答案：4

98.$$\frac{7}{19}\div\frac{11}{19}+\frac{1}{12}\div\frac{8}{9}=$$

答案：$$\frac{257}{352}$$

99.$$\frac{3}{2}\div(2\frac{1}{3}-1\frac{1}{2})\div\frac{2}{3}=$$

答案：$$\frac{27}{10}$$

100.$$\frac{2}{3}\times\frac{2}{3}\div2\frac{1}{4}+\frac{1}{12}\div\frac{2}{3}=$$

答案：$$\frac{209}{648}$$

101.$$\frac{1}{12}+\frac{3}{8}+\frac{11}{12}+\frac{5}{8}=$$

答案：2

102.$$\frac{11}{9}+\frac{1}{12}\div\frac{3}{10}-\frac{2}{9}\times3\frac{3}{2}=$$

答案：$$\frac{1}{2}

103.$$(\frac{11}{9}+\frac{1}{12})\div(\frac{3}{10}\div\frac{2}{9})\times3\frac{3}{2}=$$

答案：$$\frac{235}{54}$$

104.$$2\frac{8}{9}-\frac{1}{3}\div(\frac{3}{8}-\frac{1}{4})\div\frac{5}{9}\times\frac{1}{3}=$$

答案：$$\frac{58}{45}$$

105.$$\frac{1}{2}\div(\frac{1}{5}\div\frac{8}{9})\div(\frac{5}{6}\div\frac{1}{9})=$$

答案：$$\frac{8}{27}$$

106.$$\frac{8}{9}\times\frac{15}{36}+\frac{1}{27}=$$

答案：$$\frac{11}{27}$$

107.$$\frac{9}{7}-(\frac{2}{7}-\frac{10}{21})=$$

答案：$$1\frac{10}{21}$$

108.$$\frac{7}{9}\times\frac{15}{21}+\frac{1}{9}=$$

答案：$$\frac{2}{3}$$

109.$$\frac{9}{22}+\frac{1}{11}\div\frac{1}{2}=$$

答案：$$\frac{13}{22}$$

110.$$1+\frac{5}{6}-\frac{19}{12}=$$

答案：$$\frac{1}{4}$$

111.$$\frac{4}{7}\times\frac{1}{5}+\frac{3}{7}\div\frac{5}{9}=$$

答案：$$\frac{31}{35}$$

112.$$1\frac{7}{8}\div\frac{4}{5}=$$

答案：$$\frac{75}{32}$$

113.$$\frac{2}{8}\div2\frac{6}{7}=$$

答案：$$\frac{7}{80}$$

114.$$3\frac{1}{8}\div\frac{3}{4}=$$

答案：$$\frac{25}{6}$$

115.$$1\frac{3}{6}\div\frac{7}{5}=$$

答案：$$\frac{15}{14}$$

116.$$1\frac{4}{9}\div\frac{6}{5}=$$

答案：$$\frac{65}{54}$$

117.$$3\frac{7}{8}\div3\frac{1}{5}=$$

答案：$$\frac{155}{128}$$

118.$$14\frac{1}{2}\div2\frac{2}{8}=$$

答案：$$\frac{58}{9}$$

119.$$1\frac{4}{5}\div2\frac{3}{6}=$$

答案：$$\frac{18}{25}$$

120.$$13\frac{1}{2}\div5\frac{1}{4}=$$

答案：$$\frac{18}{7}$$

121.$$3\frac{2}{5}\div4\frac{6}{7}=$$

答案：$$\frac{119}{175}$$

122.$$5\frac{1}{2}\div5\frac{2}{4}=$$

答案：1

123.$$\frac{17}{32}-\frac{3}{4}\times\frac{9}{24}=$$

答案：$$\frac{1}{4}$$

124.$$\frac{3}{4}\times\frac{5}{7}\times\frac{4}{3}-\frac{1}{7}=$$

答案：$$\frac{4}{7}$$

125.$$\frac{8}{9}\times\frac{3}{4}-\frac{3}{8}\div\frac{3}{4}=$$

答案：$$\frac{1}{6}$$

126.$$(\frac{3}{8}+\frac{1}{27})\times8$$

答案：$$3\frac{8}{27}$$

127.$$(\frac{1}{4}+\frac{1}{4}\times99)\div\frac{25}{24}=$$

答案：24

128.$$\frac{34}{50}\times\frac{4}{7}-\frac{4}{7}\times\frac{9}{50}=$$

答案：$$\frac{2}{7}$$

129.$$\frac{1}{2}\div(\frac{7}{8}\div\frac{6}{5})=$$

答案：$$\frac{24}{35}$$

130.$$\frac{1}{2}\div(\frac{7}{8}+\frac{6}{5})=$$

答案：$$\frac{20}{83}$$

131.$$\frac{1}{2}\div(\frac{6}{7}\div\frac{1}{8})=$$

答案：$$\frac{7}{96}$$

132.$$\frac{1}{12}\div(\frac{6}{8}\div\frac{1}{8})=$$

答案：$$\frac{1}{72}$$

133.$$\frac{1}{11}\div(\frac{6}{11}\div\frac{7}{11})=$$

答案：$$\frac{7}{66}$$

134.$$\frac{4}{2}\div(1\frac{2}{3}\div\frac{6}{5})=$$

答案：$$\frac{36}{25}$$

135.$$\frac{1}{2}\div\frac{1}{33}\div\frac{9}{11}=$$

答案：$$\frac{121}{6}$$

136.$$3\times(\frac{2}{15}+\frac{1}{12})-\frac{2}{5}=$$

答案：$$\frac{1}{4}$$

137.$$\frac{15}{16}+(\frac{7}{16}-\frac{1}{4})\div\frac{1}{2}=$$

答案：$$\frac{21}{16}$$

138.$$\frac{12}{13}\times\frac{3}{7}+\frac{4}{7}\times\frac{12}{13}+\frac{12}{13}=$$

答案：$$\frac{24}{13}$$

139.$$\frac{1}{2}\times\frac{1}{3}\div\frac{1}{2}\times\frac{1}{3}=$$

答案：$$\frac{1}{9}$$

140.$$\frac{9}{10}\times[\frac{7}{8}\div(\frac{4}{5}+\frac{1}{4})]=$$

答案：$$\frac{3}{4}$$

141.$$239\times\frac{13}{238}=$$

答案：$$\frac{3107}{238}$$

142.$$56\times5\frac{7}{8}=$$

答案：329

143.$$18\times4\frac{7}{9}=$$

答案：86

144.$$4\times5\frac{1}{24}=$$

答案：$$\frac{121}{6}$$

145.$$8\times2\frac{3}{32}=$$

答案：$$\frac{67}{4}$$

146.$$16\times2\frac{1}{8}=$$

答案：34

147.$$1\div(\frac{6}{2}+\frac{1}{3}+1\frac{3}{4})=$$

答案：$$\frac{12}{61}$$

148.$$3\div(\frac{3}{4}+\frac{1}{5}+1\frac{5}{6})=$$

答案：$$\frac{180}{167}$$

149.$$6\div(\frac{5}{6}+\frac{3}{4}+1\frac{3}{8})=$$

答案：$$\frac{144}{71}$$

150.$$13\div(\frac{4}{8}+\frac{6}{4}+1\frac{2}{3})=$$

答案：$$\frac{39}{11}$$

151.$$81\div(12-\frac{5}{7}+\frac{4}{9})=$$

答案：$$\frac{5103}{739}$$

152.$$5\div(\frac{6}{2}+2+1\frac{3}{4})=$$

答案：$$\frac{20}{27}$$

153.$$4\div(15-4\frac{1}{3}+1\frac{3}{4})=$$

答案：$$\frac{48}{149}$$

154.$$10\div(5-4\frac{8}{9}+1\frac{1}{5})=$$

答案：$$\frac{450}{59}$$

155.$$21\div(\frac{5}{7}+\frac{4}{7}+1\frac{3}{7})=$$

答案：$$\frac{147}{19}$$

156.$$\frac{1}{2}\div(5+1\frac{2}{8}\div\frac{6}{5})=$$

答案：$$\frac{12}{145}$$

157.$$\frac{1}{3}\div(\frac{2}{5}+\frac{1}{4}\div\frac{1}{5})=$$

答案：$$\frac{20}{99}$$

158.$$\frac{1}{2}\div(2+\frac{7}{4}\div\frac{3}{8})=$$

答案：$$\frac{3}{40}$$

159.$$\frac{5}{4}\div(\frac{2}{7}+\frac{1}{4}\div\frac{1}{5})=$$

答案：$$\frac{35}{43}$$

160.$$\frac{1}{3}\div(3+\frac{1}{4}\div\frac{1}{5})=$$

答案：$$\frac{4}{51}$$

161.$$\frac{2}{9}\div(\frac{3}{4}+\frac{1}{12}\div\frac{6}{4})=$$

答案：$$\frac{8}{29}$$

162.$$2\frac{1}{3}\div(4+\frac{7}{6}\div\frac{14}{6})=$$

答案：$$\frac{14}{27}$$

163.$$\frac{3}{8}\div(\frac{1}{2}+\frac{8}{6}\div\frac{1}{5})=$$

答案：$$\frac{9}{172}$$

164.$$\frac{8}{5}\div(4+\frac{7}{6}\div\frac{3}{4})=$$

答案：$$\frac{36}{125}$$

165.$$\frac{5}{12}\div(\frac{2}{11}+\frac{7}{3}\div\frac{7}{9})=$$

答案：$$\frac{11}{84}$$

166.$$4\frac{1}{3}\div(6+\frac{7}{8}\div\frac{2}{9})=$$

答案：$$\frac{208}{477}$$

167.$$\frac{3}{5}\div(\frac{12}{3}+\frac{5}{7}\div\frac{3}{14})=$$

答案：$$\frac{9}{110}$$
