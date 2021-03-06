# 第1章 设计与架构究竟是什么？
## 现状
1. 编写与调试一段代码直到成功运行并不需要特别高深的知识和技能。
2. **软件架构设计**是一件非常困难的事情，需要大多数程序员所不具备的经验和技能。
3. 好的软件架构所带来的：
    - 维持系统正常运转不需要成群的程序员。
    - 每个变更的实施不再需要巨大的需求文档和复杂的任务追踪系统。
    - 程序员再也不用疯狂加班。

## 架构设计的目标
1. 设计和架构二者没有任何区别。
    - 架构使用与高层级的讨论。这类讨论一般把底层的实现细节排除在外。
    - 设计往往用来指代具体的系统底层组织结构和实现的细节。
2. 软件架构设计的目标：**软件架构的终极目标是，用最小的人力成本来满足构建和维护该系统的需求。**
3. 一个软件架构的优劣，可以用它**满足用户需求所需要的成本来衡量**。

## 乱麻系统的特点
1. 乱麻系统的特点：没有经过设计，匆忙被构建起来，然后加快发布的速度，拼命往团队里加入新人，同时加上决策层对代码质量提升和设计结构优化存在着持续的，长久的忽视。
2. 乱麻系统带来挫败感，工程师永远在**拆东墙补西墙，周而往复，偶尔有精力能顺便实现一点小功能**。

## 问题根源
1. 工程师持续低估那些好的，良好设计的、整洁的代码的重要性。
2. 清理乱麻代码的能力过于自信。
3. 胡乱编写代码的工作速度其实比循规蹈矩更慢。
4. 要想跑得快，先要跑的稳。
5. 过度自信只会使得重构设计陷入和原项目一样的困局中。

## 结论
1. 研发团队最好的选择是清晰地认识并避开工程师过度自信的特点，开始认真地对待自己的代码架构，对其质量负责。
2. 为了在系统构建过程中采用好的设计和架构以便减少构建成本，提高生产力，需要先了解系统架构的各种属性与成本和生产力的关系。