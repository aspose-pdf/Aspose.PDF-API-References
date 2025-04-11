---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Comparison.SideBySideComparisonOptions. Представляет класс параметров для сравнения документов с побочным выводом
type: docs
weight: 3290
url: /ru/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## Класс SideBySideComparisonOptions

Представляет класс параметров для сравнения документов с побочным выводом.

```csharp
public class SideBySideComparisonOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Получает и устанавливает свойство, которое определяет, отображаются ли дополнительные маркеры изменений. Если установлено, отображает маркеры изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменения находятся между словами, маркер может быть не точно расположен относительно символа пробела. Значение по умолчанию — `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Получает и устанавливает область сравнения. Используется для первой страницы или документа в методе сравнения. Этот параметр не может быть установлен вместе с [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) и [`ExcludeAreas2`](./excludeareas2/) параметрами. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Получает и устанавливает область сравнения. Используется для второй страницы или документа в методе сравнения. Этот параметр не может быть установлен вместе с [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) и [`ExcludeAreas2`](./excludeareas2/) параметрами. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Получает и устанавливает режим сравнения. Значение по умолчанию — !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Получает и устанавливает исключаемые области. Используется для первой страницы или документа в методе сравнения. Этот параметр может быть установлен вместе с [`ExcludeTables`](./excludetables/). Этот параметр не может быть установлен вместе с [`ComparisonArea1`](./comparisonarea1/) параметром. |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Получает и устанавливает исключаемые области. Используется для второй страницы или документа в методе сравнения. Этот параметр может быть установлен вместе с [`ExcludeTables`](./excludetables/). Этот параметр не может быть установлен вместе с [`ComparisonArea2`](./comparisonarea2/) параметром. |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Получает и устанавливает параметр, который определяет, исключаются ли таблицы из сравнения. Этот параметр не может быть установлен вместе с [`ComparisonArea1`](./comparisonarea1/) и [`ComparisonArea2`](./comparisonarea2/). Значение по умолчанию — `false`. |

### См. также

* пространство имен [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* сборка [Aspose.PDF](../../)