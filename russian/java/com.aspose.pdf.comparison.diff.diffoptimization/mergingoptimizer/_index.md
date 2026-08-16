---
title: "MergingOptimizer"
linktitle: "MergingOptimizer"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для переупорядочивания и объединения участков правки. Он объединяет равенства и комбинирует соседние одинаковые изменения. Он сортирует и объединяет изменения между операциями Equals, потому что."
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.comparison.diff.diffoptimization/mergingoptimizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.MergingOptimizer

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class MergingOptimizer extends Object implements IDiffOptimizationOperation
```

Представляет класс для переупорядочивания и объединения разделов правок. Он объединяет равенства и комбинирует смежные идентичные изменения. Он сортирует и объединяет изменения между операциями Equals, поскольку изменение их порядка и объединение не меняет результат, но делает вывод более читаемым. Это объединяет смежные операции Equal.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MergingOptimizer](#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-) | Создаёт экземпляр класса {@link MergingOptimizer}. |

## Методы

| Метод | Описание |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Выполняет оптимизацию операций сравнения. |

### MergingOptimizer {#MergingOptimizer-com.aspose.pdf.comparison.EditOperationsOrder-}
Создаёт экземпляр класса {@link MergingOptimizer}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Выполняет оптимизацию операций сравнения.
