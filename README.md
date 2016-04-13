# Informal translations of C++ standard drafts in Chinese(Simplified)

These are the translations of C++ standard drafts. The primative materials were fetched from https://github.com/cplusplus/draft. These translations could make contributuions to chinese readers and should never be considered as official publication of any orgnization.


# C++标准草案非正式中文（简体）译本

本译本为C++标准草案的译本，原草案自https://github.com/cplusplus/draft 获取。译本对使用中文的读者具有参考意义，除此之外，本译本并不作为任何组织的出版物。


----

本译本遵循以下原则：
+ 只要有可能，就不改变原版草案的格式
+ 力求精准
+ 大多数名词的翻译都参考自*C++ Primer（人民邮电出版社）*一书，完整的名词对照表在文件src\words.md中
+ 本译本使用的原版草案不一定与https://github.com/cplusplus/draft 同步
+ 为保证翻译质量（包括翻译的正确性和翻译风格的统一），本项目的发起者目前欢迎、感激并可能采纳任何贡献者的翻译建议以及错误勘正，**但主体翻译任务目前仅由发起者一人进行且暂时并未考虑多人共同翻译**，在以后会考虑多人一起参与翻译工作

目前需要进行的工作：
### 排版
  希望有熟悉latex的伙伴负责译本的排版。例如，译本目前暂时使用{CJKutf8}宏包进行中文显示，可以看到目前的编译结果有失偏颇，比如表格无法对齐、黑体斜体等无法显示等。
### 勘误
  错误总是很难避免，众人拾柴火焰高！
  一般勘误的过程是：
+ 您提出ISSUEs
+ 我（或如果可能后期成立专门的讨论组/群）仔细论证
+ 采纳您的建议或向您说明我的想法
### 鼓励您提出下列任何的ISSUEs：
+ 对原稿的表意有误
+ 语句不通顺或不够直白
+ 排版有误或不美观

#### 只言片语 
##### 翻译初衷
C++语言优美，提供了多种抽象级别，是一种容易直接编译为机器码的静态语言。随着C++11的推出，语言的表达力和潜在的性能又提升了许多。为人所知的例如auto的新定义以及移动语义、lambda表达式等。功能强大的背后是复杂的规模，C++模块众多，却又要保证模块之间可以互相操作；并且，C++将内存的分配权利赋予了用户，导致用户很容易在这方面跌倒；容器以及智能指针的出现缓解了这个问题，但也不是万能——例如，std::vector在初学者手里可能变成灾难——不经意间就操纵了失效的引用或迭代器等。避免上述问题的一个可能就是尽量按规范使用C++，这是本译本存在的根本。  
仍有大量用户使用C++，其中一个群体就是使用中文的用户（比如中国用户），本译本服务的目标正是这些用户——使用他们的母语查看标准的C++手册。   
C++标准是ISO的专利，因此，本译本的源仅来自于公开在GitHub上的草稿，并且译本的发起也是个人，本译本一再声明“Informal”、“Unoffical”也是因此。
