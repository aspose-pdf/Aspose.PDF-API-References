---
title: "DocSaveOptions.RecognitionMode Enum"
linktitle: "DocSaveOptions.RecognitionMode"
articleTitle: "DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for .NET"
description: "Allows to control how a PDF document is converted into a word processing document."
type: docs
weight: 600
url: "/net/aspose.pdf/docsaveoptions.recognitionmode/"
product_version: "26.9.0"
---
## DocSaveOptions.RecognitionMode enumeration

Allows to control how a PDF document is converted into a word processing document.

```csharp
public enum RecognitionMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| Textbox | `0` | This mode is fast and good for maximally preserving original look of the PDF file, 
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

## Remarks

Use the `Textbox` mode when the resulting document is not goining 
 to be heavily edited futher. Textboxes are easy to modify when there is not a lot to do.
 
Use the `Flow` mode when the output document needs further editing. 
 Paragraphs and texlines in the flow mode allow easy modification of text, but unupported
 formatting objects will look worse than in the `Textbox` mode.

### See Also

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

