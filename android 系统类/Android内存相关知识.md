# Android内存相关知识

## 1. 内存抖动

短时间内有大量的对象被创建或者被回收的现象。

## 2. 内存泄漏

某一段内存在程序里功能上已经不需要了，但是垃圾回收机制回收内存时检测那段内存还是被需要的，不能被回收，这种在程序中在没有使用的但是又不能被回收的内存就是被泄漏的内存

## 3. 内存溢出(OOM)

