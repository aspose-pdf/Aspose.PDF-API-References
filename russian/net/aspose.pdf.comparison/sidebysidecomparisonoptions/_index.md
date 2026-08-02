---
title: "Класс SideBySideComparisonOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Comparison.SideBySideComparisonOptions. Представляет класс параметров для сравнения документов с выводом sidebyside"
type: docs
weight: 3400
url: /ru/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## SideBySideComparisonOptions class

Представляет класс параметров для сравнения документов с выводом бок о бок.

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
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Получить и задать свойство, определяющее, отображаются ли дополнительные маркеры изменений. Если установлено, отображаются метки изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменение расположено между словами, метка может быть не точно позиционирована относительно пробельного символа. Значение по умолчанию — `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Получить и установить область сравнения. Используется для первой страницы или документа в методе сравнения. Этот параметр нельзя установить одновременно с опциями [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) и [`ExcludeAreas2`](./excludeareas2/) options. |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Получить и установить область сравнения. Используется для второй страницы или документа в методе сравнения. Этот параметр нельзя установить одновременно с опциями [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) и [`ExcludeAreas2`](./excludeareas2/) options. |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Получает и задает режим сравнения. Значение по умолчанию — !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Получить и установить области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно установить вместе с опцией [`ExcludeTables`](./excludetables/). Этот параметр нельзя установить одновременно с опцией [`ComparisonArea1`](./comparisonarea1/) option. |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Получить и установить области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно установить вместе с опцией [`ExcludeTables`](./excludetables/). Этот параметр нельзя установить одновременно с опцией [`ComparisonArea2`](./comparisonarea2/) option. |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Получить и установить параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя установить одновременно с [`ComparisonArea1`](./comparisonarea1/) и [`ComparisonArea2`](./comparisonarea2/). Значение по умолчанию — `false`. |

### См. также

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


