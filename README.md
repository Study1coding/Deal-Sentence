# Deal-Sentence
1.	编写一个DealSentence 程序，主要功能： 对用户输入的英文句子，根据命令选项执行相应操作，命令格式是：
DealSentence [-w ] [-r ] [-u ]  <a sentence>  
      其中[ ] 表示可选参数，句子以双引号引住(如：DealSentence “Hello world!”)
      -w: 分解为单词分行输出
		  -r: 反向输出（若同时有-w选项，分词分行反向输出）
      -u：处理结果以大写字母输出
（提示： 反向功能 也可利用数组Array的成员函数Reverse()来实现）
输出要求示例： 原句子为 ：Hello world！
a)	无选项则直接输出：Hello world!
b)	含-w不含-r选项， 输出： Hello
            World
c)	含-r 不含-w选项，输出：!dlrow olleH
d)	同时有-w -r ,输出： dlrow
      olleH
e)	只要含-u ，则大写所有字符，再按上面4条规则输出。
可以自行选择以过程式方式或是面向对象方式来实现。

