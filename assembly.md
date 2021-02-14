一般寄存器：EAX、EBX、ECX、EDX

EAX：累积暂存器，EBX：基底暂存器（在内存寻址时存放基地址），ECX：计数暂存器（是重复REP前缀指令和LOOP指令的内定计数器），EDX：资料暂存器（放整数除法产生的余数）

索引暂存器：ESI、EDI（分别叫做"源/目标索引寄存器",因为在很多字符串操作指令中, DS:ESI指向源串,而ES:EDI指向目标串.）

ESI：来源索引暂存器，EDI：目的索引暂存器

堆叠、基底暂存器：ESP、EBP

ESP：堆叠指标暂存器（ 专门用作堆栈指针，在32位平台上，ESP每次减少4字节），EBP：基底指标暂存器（基址指针）

<img src="https://upload-images.jianshu.io/upload_images/1208639-9c29243af0edc5f8.png?imageMogr2/auto-orient/strip|imageView2/2/w/546" alt="栈" style="zoom:67%;" />



je；等于则跳转

jne；不等于则跳转

jmp；无条件跳转

jg；有符号大于则跳转

jg；无符号大于则跳转

指令大全：https://blog.csdn.net/zhu2695/article/details/16812415

AT&T 汇编与intel汇编的区别：https://www.jianshu.com/p/0480e431f1d7