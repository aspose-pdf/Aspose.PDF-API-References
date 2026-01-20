---
title: Aspose::Pdf::HtmlSaveOptions::AntialiasingProcessingType enum
linktitle: AntialiasingProcessingType
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::AntialiasingProcessingType enum. This enum describes possible antialiasing measures during conversion in C++.'
type: docs
weight: 5100
url: /cpp/aspose.pdf/htmlsaveoptions/antialiasingprocessingtype/
---
## AntialiasingProcessingType enum


This enum describes possible antialiasing measures during conversion.

```cpp
enum class AntialiasingProcessingType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoAdditionalProcessing | 0 | no special antialiasing processing in use. This is an optimal option for overhelming majority of documents and it does not require additional time during conversion |
| TryCorrectResultHtml | 1 | In such case converter tries to detect places with ajacent background graphical elements and correct result HTML in relevant way. This option allows enhance result of export for documents that contain backgrounds built from several ajacent graphical elements (for such kind of documents PDF renderers , f.e. Acrobat Reader, usually try smooth boundaries of elements during rendering. With this option converter imitates that behaviour of PDF-renderers. This option allows enhance layout of result of export for some specific documents (that use such compound backgrounds), but it requires additional time for processng (usually about 10-15% of additional time). So usage of this mode in general case is not recommended. |

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
