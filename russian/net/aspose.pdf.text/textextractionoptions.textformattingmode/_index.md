---
title: "Перечисление TextExtractionOptions.TextFormattingMode"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Перечисление Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode. Определяет различные режимы, которые могут использоваться при преобразовании pdf‑документа в текст. См. класс TextDevice"
type: docs
weight: 11080
url: /ru/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

Определяет различные режимы, которые могут использоваться при преобразовании pdf‑документа в текст. См. класс !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Pure | `0` | Отображает содержимое pdf с небольшим набором форматирующих процедур. |
| Raw | `1` | Отображает содержимое pdf как есть, то есть без форматирования. |
| Flatten | `2` | Отображает содержимое pdf с позиционированием текстовых фрагментов по их координатам. По сути это аналог режима "Raw". Однако в то время как "Raw" ориентирован на сохранение структуры текстовых фрагментов (операторов) в документе, "Flatten" ориентирован на сохранение текста в порядке его чтения. |
| MemorySaving | `3` | Извлечение с экономией памяти. Практически аналогично режиму 'Raw', но работает немного быстрее и использует меньше памяти. |

### См. также

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


