---
title: LoadOptions.MarginsAreaUsageModes
linktitle: LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for Java API Reference
description: Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins.
type: docs
weight: 2800
url: /java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins.

## Fields

| Field | Description |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | This mode strictly forbids usage of margins area, so, converter will never use area of margins for rendering, even if CSS or format of source document allows or requirs that |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | In this mode converter obeyes format of imported document (f.e. CSS of imported HTML) in usage of margins area.So, if format of imported document requires usage of margins area for rendering , converter will allow that |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

This mode strictly forbids usage of margins area, so, converter will never use area of margins for rendering, even if CSS or format of source document allows or requirs that

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

In this mode converter obeyes format of imported document (f.e. CSS of imported HTML) in usage of margins area.So, if format of imported document requires usage of margins area for rendering , converter will allow that
