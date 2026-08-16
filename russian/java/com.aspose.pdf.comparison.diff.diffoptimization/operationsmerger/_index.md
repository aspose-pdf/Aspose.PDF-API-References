---
title: "OperationsMerger"
linktitle: "OperationsMerger"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для объединения равенств и комбинирования соседних одинаковых изменений. Он сортирует и объединяет изменения между операциями Equals, поскольку изменение их порядка и объединение."
type: docs
weight: 30
url: /ru/java/com.aspose.pdf.comparison.diff.diffoptimization/operationsmerger/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.diff.diffoptimization.OperationsMerger

**All Implemented Interfaces:**
IDiffOptimizationOperation

```
public final class OperationsMerger extends Object implements IDiffOptimizationOperation
```

Представляет класс для объединения равенств и комбинирования смежных идентичных изменений. Он сортирует и объединяет изменения между операциями Equals, поскольку изменение их порядка и объединение не меняет результат, но делает вывод более читаемым. Это объединяет смежные операции Equal.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OperationsMerger](#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-) | Создаёт экземпляр класса {@link OperationsMerger}. |

## Методы

| Метод | Описание |
| --- | --- |
| [execute](#execute-com.aspose.ms.System.Collections.Generic.List-) | Выполняет объединения. |

### OperationsMerger {#OperationsMerger-com.aspose.pdf.comparison.EditOperationsOrder-}
Создаёт экземпляр класса {@link OperationsMerger}.

### execute {#execute-com.aspose.ms.System.Collections.Generic.List-}
Выполняет объединения.
