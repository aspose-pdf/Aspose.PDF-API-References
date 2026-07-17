---
title: Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction method
linktitle: CreateBookmarksAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction method. Creates a bookmark with the specified action in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor::CreateBookmarksAction method


Creates a bookmark with the specified action.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateBookmarksAction(const System::String &title, System::Drawing::Color color, bool boldFlag, bool italicFlag, const System::String &file, const System::String &actionType, const System::String &destination)
```


| Parameter | Type | Description |
| --- | --- | --- |
| title | const System::String\& | The title of the bookmark. |
| color | System::Drawing::Color | The colour of the bookmark's title. |
| boldFlag | bool | The flag of bold attribution. |
| italicFlag | bool | The flag of italic attribution. |
| file | const System::String\& | Another file or application required when the action type is "GoToR" or "Launch". |
| actionType | const System::String\& | The action type. The value can be: "GoToR", "Launch", "GoTo", "URI". |
| destination | const System::String\& | The local destination or remote destination or URL. |

## See Also

* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
