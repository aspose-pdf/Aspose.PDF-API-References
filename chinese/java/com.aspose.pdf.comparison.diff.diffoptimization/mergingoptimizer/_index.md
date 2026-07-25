---
title: "MergingOptimizer"
linktitle: "MergingOptimizer"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于重新排序和合并编辑区段的类。它合并相等项并组合相邻的相同更改。它在 Equals 操作之间对更改进行排序和合并，因为。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.comparison.diff.diffoptimization/mergingoptimizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.MergingOptimizer

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class MergingOptimizer extends Object implements IDiffOptimizationOperation
```

表示用于重新排序和合并编辑部分的类。它合并等价项并组合相邻的相同更改。它对 Equals 操作之间的更改进行排序和合并，因为更改它们的顺序和合并不会改变结果，但会产生更易读的输出。这会合并相邻的 Equal 操作。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MergingOptimizer](#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-) | 创建 {@link MergingOptimizer} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | 执行差异操作的优化。 |

### MergingOptimizer {#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-}
创建 {@link MergingOptimizer} 类的实例。

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
执行差异操作的优化。
