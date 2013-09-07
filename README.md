C_passViaStack
==============

C 栈传递

参考：http://bbs.chinaunix.net/forum.php?mod=viewthread&tid=4076743
 
 
 
A: 问题是第二个%d，是解释变量b的？为什么会解释a的高地址了？
 
B: 执行的时候可没有a、b、c这玩意，printf根据格式化串取栈中的数据，%d对应int，你那环境应该是4字节。
