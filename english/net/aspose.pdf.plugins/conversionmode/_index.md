---
title: Enum ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ConversionMode enum. Defines conversion mode of the output document
type: docs
weight: 8630
url: /net/aspose.pdf.plugins/conversionmode/
---
## ConversionMode enumeration

Defines conversion mode of the output document.

```csharp
public enum ConversionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| TextBox | `0` | This mode is fast and good for maximally preserving original look of the PDF file, but editability of the resulting document could be limited. |
| Flow | `1` | Full recognition mode, the engine performs grouping and multi-level analysis to restore the original document author's intent and produce a maximally editable document. The downside is that the output document might look different from the original PDF file. |
| EnhancedFlow | `2` | An alternative Flow mode that supports the recognition of tables. |

### See Also

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


