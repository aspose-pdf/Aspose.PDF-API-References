---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Enum LoadOptionsMarginsAreaUsageModes Aspose.Pdf. Представляет режим использования области полей во время конвертации, таких как HTML, EPUB и т. д., определяет обработку инструкций импортированного формата, связанных с использованием полей.
type: docs
weight: 6130
url: /ru/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## Перечисление LoadOptions.MarginsAreaUsageModes

Представляет режим использования области полей во время конвертации (таких как HTML, EPUB и т. д.), определяет обработку инструкций импортированного формата, связанных с использованием полей.

```csharp
public enum MarginsAreaUsageModes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | В этом режиме конвертер подчиняется формату импортированного документа (например, CSS импортированного HTML) в использовании области полей. Таким образом, если формат импортированного документа требует использования области полей для рендеринга, конвертер это позволит. |
| NeverPutContentOnMarginArea | `1` | Этот режим строго запрещает использование области полей, поэтому конвертер никогда не будет использовать область полей для рендеринга, даже если CSS или формат исходного документа это позволяет или требует. |

### См. также

* класс [LoadOptions](../loadoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)