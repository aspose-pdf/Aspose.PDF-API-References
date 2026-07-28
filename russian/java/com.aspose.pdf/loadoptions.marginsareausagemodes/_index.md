---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет режим использования области полей при конвертации (например HTML, EPUB и т.д.), определяет обработку инструкций импортируемого формата, связанных с использованием полей."
type: docs
weight: 2800
url: /ru/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Представляет режим использования области полей при конвертации (например HTML, EPUB и т.д.), определяет обработку инструкций импортируемого формата, связанных с использованием полей.

## Поля

| Поле | Описание |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Этот режим строго запрещает использование области полей, поэтому конвертер никогда не будет использовать область полей для рендеринга, даже если CSS или формат исходного документа позволяют или требуют это. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | В этом режиме конвертер соблюдает формат импортируемого документа (например CSS импортированного HTML) при использовании области полей. Поэтому, если формат импортируемого документа требует использования области полей для рендеринга, конвертер позволит это. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Этот режим строго запрещает использование области полей, поэтому конвертер никогда не будет использовать область полей для рендеринга, даже если CSS или формат исходного документа позволяют или требуют это.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

В этом режиме конвертер соблюдает формат импортируемого документа (например CSS импортированного HTML) при использовании области полей. Поэтому, если формат импортируемого документа требует использования области полей для рендеринга, конвертер позволит это.
