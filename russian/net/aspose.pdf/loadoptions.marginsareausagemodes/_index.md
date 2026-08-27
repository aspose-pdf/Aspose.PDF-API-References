---
title: "Перечисление LoadOptions.MarginsAreaUsageModes"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Представляет режим использования области полей при конвертации, такой как HTML, EPUB и т.д., определяет обработку инструкций импортированного формата, связанных с использованием полей"
type: docs
weight: 6270
url: /ru/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

Представляет режим использования области полей при конвертации (например, HTML, EPUB и т.д.), определяет обработку инструкций импортированного формата, связанных с использованием полей.

```csharp
public enum MarginsAreaUsageModes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | В этом режиме конвертер следует формату импортированного документа (например, CSS импортированного HTML) при использовании области полей. Поэтому, если формат импортированного документа требует использования области полей для рендеринга, конвертер позволит это. |
| NeverPutContentOnMarginArea | `1` | Этот режим строго запрещает использование области полей, поэтому конвертер никогда не будет использовать область полей для рендеринга, даже если CSS или формат исходного документа позволяют или требуют этого. |

### См. также

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


