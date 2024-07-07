## 声明

代码来自博客： https://jenkov.com/tutorials/java-nio/index.html 中提高的源码，感谢分享和支持

## 学习指导

英文水平不错的，建议直接看原文 [java-nio](https://jenkov.com/tutorials/java-nio/index.html)

在知乎上看到有个翻译版本 [翻译版](https://zhuanlan.zhihu.com/p/669720832?utm_medium=social&utm_psn=1793371861628874752&utm_source=wechat_session)


-----
摸鱼在公司偷学，没法把笔记和代码捞出来

代码待优化：
1. TLV定义的比较简单，大数据量，需要预先分配内存太多，要进一步优化
2. Buffer 采用预先分割的小中大类型的缓存区来处理，预先分配内存占用太多，不推荐，而且还有内存碎片，如果1优化了，2就能直接分配
