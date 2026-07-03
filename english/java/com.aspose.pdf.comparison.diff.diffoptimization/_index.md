---
title: com.aspose.pdf.comparison.diff.diffoptimization
second_title: Aspose.PDF for Java API Reference
description: 
type: docs
weight: 70
url: /java/com.aspose.pdf.comparison.diff.diffoptimization/
---


## Interfaces

| Interface | Description |
| --- | --- |
| [IDiffOptimizationOperation](./idiffoptimizationoperation/) | Represents the interface of difference operations optimizers. |
## Classes

| Class | Description |
| --- | --- |
| [MergingOptimizer](./mergingoptimizer/) | Represents class to reorder and merge edit sections. It merge equalities and combines adjacent identical changes. It sorts and merge changes between Equals operations, because changing their order and merge does not change the result, but produces more readable output. This combines adjacent Equal operations. |
| [OperationsMerger](./operationsmerger/) | Represents a class to merge merge equalities and combines adjacent identical changes. It sorts and merge changes between Equals operations, because changing their order and merge does not change the result, but produces more readable output. This combines adjacent Equal operations. |
| [OperationsSlideMerger](./operationsslidemerger/) | Represents a class to identifies single edits that are surrounded by equalities and merge it with left or right equal operation. |
