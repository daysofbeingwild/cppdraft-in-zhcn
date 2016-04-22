# Informal translations of C++ standard drafts in Chinese(Simplified)

These are the translations of C++ standard drafts. The original and various tools were fetched from https://github.com/cplusplus/draft. These translations, which are informal, could make contributuions to chinese readers.

# C++标准草案（简体）中译本

本译本（以下简称译本）为C++标准草案的中文译本，原文以及取自https://github.com/cplusplus/draft。译本对使用中文的读者具有参考意义。

----

本译本遵循以下原则：
+ 尽量不改变原版草案的排版
+ 力求精准
+ 大多数名词的翻译都参考自*C++ Primer（人民邮电出版社）*一书，完整的名词对照表在文件src\words.md中
+ 译本翻译的原文不一定就是 https://github.com/cplusplus/draft 最新的paper
+ 为保证翻译质量（包括翻译的正确性和翻译风格的统一），本项目的发起者目前欢迎、感激并可能采纳任何贡献者的翻译建议以及错误勘正，**但主体翻译任务目前仅由发起者一人进行且暂时并未考虑多人共同翻译**，在以后会考虑多人一起参与翻译工作

错误勘正主要包括以下几种：
+ 对原稿的表意有误
+ 语句不通顺或不够精确
+ 排版有误或不美观

欢迎你的贡献。

-----

#### 翻译初衷
C++语言优美，提供了多种抽象级别，是一种容易直接编译为机器码的静态语言。随着C++11的推出，语言的表达力和潜在的性能又提升了许多。为人所知的例如auto的新定义以及移动语义、lambda表达式等。功能强大的背后是复杂的规模，C++模块众多，却又要保证模块之间可以互相操作；并且，C++将内存的分配权利赋予了用户，导致用户很容易在这方面跌倒；容器以及智能指针的出现缓解了这个问题，但也不是万能——例如，std::vector在初学者手里可能变成灾难——不经意间就操纵了失效的引用或迭代器等。避免上述问题的一个可能就是尽量按规范使用C++，这是本译本存在的根本。  
仍有大量用户使用C++，其中一个群体就是使用中文的用户（比如中国用户），本译本服务的目标正是这些用户——使用他们的母语查看标准的C++手册。   
C++标准是ISO的专利，因此，本译本的源仅来自于公开在GitHub上的草稿，并且译本的发起也是个人，本译本一再声明“Informal”、“Unoffical”也是因此。
