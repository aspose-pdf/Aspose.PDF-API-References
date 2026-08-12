---
title: "Перечисление Aspose::Pdf::LoadOptions::MarginsAreaUsageModes"
linktitle: "MarginsAreaUsageModes"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление Aspose::Pdf::LoadOptions::MarginsAreaUsageModes. Представляет режим использования области полей при конвертации (например HTML, EPUB и т.д.), определяет обработку инструкций импортированного формата, связанных с использованием полей в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf/loadoptions/marginsareausagemodes/
---
## MarginsAreaUsageModes enum


Представляет режим использования области полей при конвертации (например HTML, EPUB и т.д.), определяет обработку инструкций импортированного формата, связанных с использованием полей.

```cpp
enum class MarginsAreaUsageModes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | 0 | В этом режиме конвертер соблюдает формат импортированного документа (например CSS импортированного HTML) при использовании области полей. Поэтому, если формат импортированного документа требует использования области полей для рендеринга, конвертер позволит это. |
| NeverPutContentOnMarginArea | 1 | Этот режим строго запрещает использование области полей, поэтому конвертер никогда не будет использовать область полей для рендеринга, даже если CSS или формат исходного документа позволяют или требуют это. |

## См. также

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
