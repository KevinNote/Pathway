```mermaid
---
title: KevinZonda's Learning Pathway
---
flowchart LR
  subgraph UOB[U BHAM B.Sc. Computer Science]
    direction TB
    NTHU_OS[NTHU 10501：作業系統]
    S_CVDL[Stanford CS231n：计算机视觉深度学习]
    S_NLP[Stanford CS 124：从语言到信息]
    NTHU_OS ~~~ S_CVDL
    S_CVDL ~~~ S_NLP
  end

  OX_IntroUniMath[OX: Introduction to<br>University Mathematics]
  PKU_MathAnalysis[PKU: 数学分析<br>aka. 高等数学]
  
  NTHU_Parallel[NTHU 10710：平行程式]
  CMU_Parallel[CMU 15418：并行计算机架构与编程<br>Stanford CS149：并行计算]
  NTHU_Parallel -.- CMU_Parallel
  MIT_DistSys[MIT6.824：分布式系统]
  

  UOB -.-> NTHU_Parallel
  UOB -.-> CMU_Parallel
  NTHU_Parallel -.-> MIT_DistSys
  CMU_Parallel -.-> MIT_DistSys

  UOB -.-> OX_IntroUniMath
  OX_IntroUniMath -.-> PKU_MathAnalysis
  
```

PKU 数学分析 [Bilibili](https://www.bilibili.com/video/BV1T5411P7wi/) [官网](https://resource.pku.edu.cn/index.php?r=course%2Fview&id=1083)  
OX Introduction to University Math [官网](https://courses.maths.ox.ac.uk/course/view.php?id=4938)
