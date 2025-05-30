---
tags:
  - 数学
dlink:
  - "[[---假设检验---]]"
---
**p值检验法**是假设检验中的一种常见方法，它主要用于决定是否拒绝原假设 $H_0$ 。以下是p值检验法的核心内容和步骤。

### 1. **假设设定**
   - **原假设 $H_0$**: 通常代表没有效应或差异的情况（例如，样本均值与总体均值相等，两个样本均值相等，变量之间没有关系等）。
   - **备择假设 $H_1$**: 通常代表有效应或差异的情况（例如，样本均值与总体均值不等，两个样本均值不等，变量之间有关系等）。

### 2. **选择适当的检验统计量**
   - 选择合适的统计检验方法（如z检验、t检验、卡方检验等）来计算检验统计量。这一步取决于数据的类型和假设检验的目标。

### 3. **计算检验统计量**
   - 使用样本数据计算检验统计量。检验统计量的值表示观测结果与原假设的偏离程度。

### 4. **计算p值**
   - **p值**（probability value）是基于检验统计量计算的概率，表示在原假设为真时，观测到像样本这样极端或更极端的结果的概率。
   - 具体来说，p值越小，说明样本数据与原假设的偏离程度越大，原假设成立的可能性越小。

### 5. **与显著性水平比较**
   - 选择一个显著性水平 $\alpha$ （通常为0.05）。这个值是研究者预先设定的，用于判断结果是否具有统计显著性。
   - **p值与显著性水平 $\alpha$** 进行比较：
     - 如果 $p \leq \alpha$：拒绝原假设 $H_0$ ，认为数据提供了足够的证据支持备择假设 $H_1$ 。
     - 如果 $p > \alpha$：不能拒绝原假设 $H_0$ ，认为数据不提供足够的证据支持备择假设 $H_1$ 。

### 6. **作出结论**
   - 根据p值的大小与显著性水平的比较，得出对原假设的判断（拒绝或不拒绝）。
   - 需要注意的是，“不拒绝原假设”并不意味着原假设为真，而只是数据不足以显示原假设为假。

### **总结**

p值检验法在假设检验中起到了核心作用，它量化了观测数据在原假设条件下出现的概率，帮助研究者通过设定的显著性水平作出是否拒绝原假设的决策。这一方法在统计学中广泛应用，是许多统计检验的标准步骤。