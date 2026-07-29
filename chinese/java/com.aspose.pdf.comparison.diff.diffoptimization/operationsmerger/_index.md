---
title: "OperationsMerger"
linktitle: "OperationsMerger"
second_title: "Aspose.PDF for Java API 参考"
description: "表示一个用于合并相等项的类，并组合相邻的相同更改。它对 Equals 操作之间的更改进行排序和合并，因为更改它们的顺序和合并。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.comparison.diff.diffoptimization/operationsmerger/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.OperationsMerger

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class OperationsMerger extends Object implements IDiffOptimizationOperation
```

表示用于合并等价项并组合相邻相同更改的类。它对 Equals 操作之间的更改进行排序和合并，因为更改它们的顺序和合并不会改变结果，但会产生更易读的输出。这会合并相邻的 Equal 操作。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OperationsMerger](#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-) | 创建 {@link OperationsMerger} 类的实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | 执行合并。 |

### OperationsMerger {#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-}
创建 {@link OperationsMerger} 类的实例。

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
执行合并。
