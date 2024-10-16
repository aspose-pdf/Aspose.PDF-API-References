---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Represents mode of usage of margins area during conversion like HTML EPUB etc defines treatement of instructions of imported format related to usage of margins
type: docs
weight: 4540
url: /net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

Represents mode of usage of margins area during conversion (like HTML, EPUB etc), defines treatement of instructions of imported format related to usage of margins.

```csharp
public enum MarginsAreaUsageModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | In this mode converter obeyes format of imported document (f.e. CSS of imported HTML) in usage of margins area.So, if format of imported document requires usage of margins area for rendering , converter will allow that |
| NeverPutContentOnMarginArea | `1` | This mode strictly forbids usage of margins area, so, converter will never use area of margins for rendering, even if CSS or format of source document allows or requirs that |

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


