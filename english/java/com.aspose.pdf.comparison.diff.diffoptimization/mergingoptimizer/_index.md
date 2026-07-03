---
title: MergingOptimizer
second_title: Aspose.PDF for Java API Reference
description: Represents class to reorder and merge edit sections. It merge equalities and combines adjacent identical changes. It sorts and merge changes between Equals operations, because.
type: docs
weight: 20
url: /java/com.aspose.pdf.comparison.diff.diffoptimization/mergingoptimizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.MergingOptimizer

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class MergingOptimizer extends Object implements IDiffOptimizationOperation
```

Represents class to reorder and merge edit sections. It merge equalities and combines adjacent identical changes. It sorts and merge changes between Equals operations, because changing their order and merge does not change the result, but produces more readable output. This combines adjacent Equal operations.

## Constructors

| Constructor | Description |
| --- | --- |
| [MergingOptimizer](#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-) | Creates an instance of {@link MergingOptimizer} class. |

## Methods

| Method | Description |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Performs optimization of difference operations. |

### MergingOptimizer {#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-}
Creates an instance of {@link MergingOptimizer} class.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Performs optimization of difference operations.
