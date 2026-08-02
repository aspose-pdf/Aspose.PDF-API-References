---
title: "Класс ComparisonOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Comparison.ComparisonOptions. Представляет класс параметров сравнения PDF‑документов"
type: docs
weight: 3260
url: /ru/net/aspose.pdf.comparison/comparisonoptions/
---
## ComparisonOptions class

Представляет класс параметров сравнения PDF‑документов.

```csharp
public class ComparisonOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Получает и задает порядок операций редактирования. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Получить и задать исключаемые области. Используется для первой страницы или документа в методе сравнения. Этот параметр можно установить вместе с [`ExcludeTables`](./excludetables/). Этот параметр нельзя установить вместе с параметром [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Получить и задать исключаемые области. Используется для второй страницы или документа в методе сравнения. Этот параметр можно установить вместе с [`ExcludeTables`](./excludetables/). Этот параметр нельзя установить вместе с параметром [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Получить и задать параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя установить одновременно с параметром [`ExtractionArea`](./extractionarea/). Значение по умолчанию — `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Получить и задать прямоугольную область, в которой будет сравниваться текст страниц. Этот параметр нельзя установить вместе с параметрами [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) и [`ExcludeAreas2`](./excludeareas2/). |

### См. также

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


