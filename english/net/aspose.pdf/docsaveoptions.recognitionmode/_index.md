---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode enum. Allows to control how a PDF document is converted into a word processing document
type: docs
weight: 1910
url: /net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

Allows to control how a PDF document is converted into a word processing document.

```csharp
public enum RecognitionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Textbox | `0` | This mode is fast and good for maximally preserving original look of the PDF file, but editability of the resulting document could be limited. |
| Flow | `1` | Full recognition mode, the engine performs grouping and multi-level analysis to restore the original document author's intent and produce a maximally editable document. The downside is that the output document might look different from the original PDF file. |
| EnhancedFlow | `2` | An alternative Flow mode that supports the recognition of tables. |

## Remarks

Use the Textbox mode when the resulting document is not goining to be heavily edited futher. Textboxes are easy to modify when there is not a lot to do.

Use the Flow mode when the output document needs further editing. Paragraphs and texlines in the flow mode allow easy modification of text, but unupported formatting objects will look worse than in the Textbox mode.

### See Also

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


