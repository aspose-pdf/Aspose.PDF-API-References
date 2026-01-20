---
title: Aspose::Pdf::DocSaveOptions::RecognitionMode enum
linktitle: RecognitionMode
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocSaveOptions::RecognitionMode enum. Allows to control how a PDF document is converted into a word processing document in C++.'
type: docs
weight: 2700
url: /cpp/aspose.pdf/docsaveoptions/recognitionmode/
---
## RecognitionMode enum


Allows to control how a PDF document is converted into a word processing document.

```cpp
enum class RecognitionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Textbox | 0 | This mode is fast and good for maximally preserving original look of the PDF file, but editability of the resulting document could be limited. |
| Flow | 1 | Full recognition mode, the engine performs grouping and multi-level analysis to restore the original document author's intent and produce a maximally editable document. The downside is that the output document might look different from the original PDF file. |
| EnhancedFlow | 2 | An alternative [Flow](../../../aspose.pdf.flow/) mode that supports the recognition of tables. |

## Remarks


Use the [RecognitionMode::Textbox](./) mode when the resulting document is not goining to be heavily edited futher. Textboxes are easy to modify when there is not a lot to do.

Use the [RecognitionMode::Flow](./) mode when the output document needs further editing. [Paragraphs](../../paragraphs/) and texlines in the flow mode allow easy modification of text, but unupported formatting objects will look worse than in the [RecognitionMode::Textbox](./) mode.
## See Also

* Class [DocSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
