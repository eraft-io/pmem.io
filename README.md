# pmem 中文社区

本站点关注 pmem 官网一些英文资料的解读，遇到任何错误欢迎 PR 指正

## 什么是持久化内存？

持久化内存允许程序像访问内存一样访问数据，它可以进行直接的地址寻址，同时它存储的内容是非易失的，断电重启后数据依然存在。它通常不会用来替代传统的内存或者存储。相反，持久化内存与内存和传统存储设备结合使用，使用持久化内存的存储系统可以优于传统的系统，提供更快的启动时间、加快对大型内存数据集的访问，并通常可以降低存储成本（比内存便宜，性能接近内存并且数据可以持久化）。

## 持久化内存开发工具包 (Persistent Memory Development Kit)

持久内存开发工具包（PMDK）是一套针对各种用例 (use cases) 开发的开源库。每个库都经过迭代，验证以达到生产环境要求，而且有完整的文档记录。
这些库提供了稳定的 API，因此开发人员可以在应用程序中快速的实现基于 PMem 的功能，而且无需担心硬件实现细节或不同代的变更。

## 持久化内存编程

持久化内存官方英文书 [持久化内存编程](https://pmem.io/books)

## 开发资料

快速开始

PMDK 

PMem 相关代码仓库

PMemKV
