---
title: "Aspose::Pdf::Comparison::ComparisonMode enum"
linktitle: "ComparisonMode"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Comparison::ComparisonMode enum. Перечисление режимов сравнения в C++."
type: docs
weight: 2100
url: /ru/cpp/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enum


Перечисление режимов сравнения.

```cpp
enum class ComparisonMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Normal | 0 | Нормальный режим. Учитываются только пробелы внутри текстовых фрагментов (в зависимости от способа генерации документа.) |
| IgnoreSpaces | 1 | Все пробелы игнорируются. Изменения ищутся только в словах. |
| ParseSpaces | 2 | Этот режим похож на нормальный, но пытается учитывать визуальное расстояние между текстовыми фрагментами на основе расстояния. Определение количества пробелов между фрагментами может быть неточным, поскольку это сильно зависит от способа генерации документов. Если документы созданы разными генераторами, могут возникать неточности при сравнении пробелов между текстовыми фрагментами. |

## См. также

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
