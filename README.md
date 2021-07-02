# 数栈代码评审工程实践文档

## 代码评审指南介绍

* [数栈代码评审指南](review/index.md), 包含4个子章节：
  * [代码评审指南](review/CodeReview/index.md)
  * [代码评审者指南](review/Reviewers/index.md)
  * [代码开发者指南](review/Developer/index.md)
  * [代码评审机制保障](review/Mechanism/index.md)

## 注意事项

* 经常进行代码评审
* 代码评审不要太正式，要短
* 尽可能让不同的人评审你的代码
* 保持积极的正面态度

## 常见问题

* **代码评审者提出的都是一些编码风格和代码规范的东西**？
  
   编码规范应该交给工具去做，代码需遵循数栈代码风格指南

* **为什么要鼓励为主而不是责罚并举**
  
  众所周知代码评审并不容易施行，因为它是团队和个人长期才能感受到好处的过程，即使不做似乎也看不到啥影响，业务也照跑，而惩罚是阶段性的反馈，所以现阶段还是以鼓励为主，但是由于对代码提交人和代码评审人要求不同，对提交人的责任要求更大点。对审核覆盖率有要求，也有责任推进评审进度。
对于代码评审主要是鼓励，因为代码评审是利他行为。在某些情况下会有一些惩罚要求：该模块很重要，引发了故障。而此问题是可以通过明显的评审发现的，此时也要承担责任

## 路线图

* [ ] 本指南达成共识 @TeamLeader
* [ ] 数栈代码风格指南落地和达成共识
* [ ] 整理输出团队自身的Checklist @TeamLeader
