---
title: "ConversionMode Enum"
linktitle: "ConversionMode"
articleTitle: "ConversionMode"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.ConversionMode enum. Defines conversion mode of the output document."
type: docs
weight: 30
url: "/net/aspose.pdf.lowcode/conversionmode/"
product_version: "26.9.0"
---
## ConversionMode enumeration

Defines conversion mode of the output document.

```csharp
public enum ConversionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| TextBox | `0` | This mode is fast and good for maximally preserving original look of the PDF file, 
 but editability of the resulting document could be limited.
 
Every visually grouped block of text int the original PDF file is converted into a textbox 
 in the resulting document. This achieves maximal resemblance of the output document to the original 
 PDF file. The output document will look good, but it will consist entirely of textboxes and it 
 could makes further editing of the document in Microsoft Word quite hard.
 
This is the default mode. |
| Flow | `1` | Full recognition mode, the engine performs grouping and multi-level analysis to restore
 the original document author's intent and produce a maximally editable document.
 The downside is that the output document might look different from the original PDF file. |
| EnhancedFlow | `2` | An alternative Flow mode that supports the recognition of tables. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

