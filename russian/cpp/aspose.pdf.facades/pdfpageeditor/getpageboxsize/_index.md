---
title: "Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize метод"
linktitle: "GetPageBoxSize"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize метод. Возвращает размер указанного бокса в документе в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor::GetPageBoxSize method


Возвращает размер указанного блока в документе.

```cpp
System::Drawing::Rectangle Aspose::Pdf::Facades::PdfPageEditor::GetPageBoxSize(int32_t page, const System::String &pageBoxName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int32_t | [Страница](../../../aspose.pdf/page/) индекс. Страницы [Документ](../../../aspose.pdf/document/) нумеруются с 1. |
| pageBoxName | const System::String\& | Имя типа бокса. Допустимые значения: "art", "bleed", "crop", "media", "trim". |

### ReturnValue

[Rectangle](../../../aspose.pdf/rectangle/) which contains requested box.

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfPageEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
