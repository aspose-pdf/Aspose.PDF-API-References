---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Справочник API Aspose.PDF для Java"
description: "Перечисление режимов сравнения."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

Перечисление режимов сравнения.

## Поля

| Поле | Описание |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Все пробелы игнорируются. Изменения ищутся только в словах. |
| [Normal](#Normal) | Нормальный режим. Учитываются только пробелы внутри фрагментов текста (в зависимости от способа генерации документа). |
| [ParseSpaces](#ParseSpaces) | Режим похож на нормальный, но пытается учитывать визуальное расстояние между фрагментами текста на основе расстояния. Определение количества пробелов между фрагментами может быть неточным, поскольку это сильно зависит от того, как генерируются документы. Если документы создаются разными генераторами, могут возникать неточности при сравнении пробелов между фрагментами текста. Эта опция может дать результаты, которые, хотя и логичны, отличаются от ожидаемых результатов сравнения при применении к сложноструктурированным документам. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Все пробелы игнорируются. Изменения ищутся только в словах.

### Normal {#Normal}
```
public static final int Normal
```

Нормальный режим. Учитываются только пробелы внутри фрагментов текста (в зависимости от способа генерации документа).

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

Режим похож на нормальный, но пытается учитывать визуальное расстояние между фрагментами текста на основе расстояния. Определение количества пробелов между фрагментами может быть неточным, поскольку это сильно зависит от того, как генерируются документы. Если документы создаются разными генераторами, могут возникать неточности при сравнении пробелов между фрагментами текста. Эта опция может дать результаты, которые, хотя и логичны, отличаются от ожидаемых результатов сравнения при применении к сложноструктурированным документам.
