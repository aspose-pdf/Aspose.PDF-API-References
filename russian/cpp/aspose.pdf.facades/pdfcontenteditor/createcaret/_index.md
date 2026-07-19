---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateCaret метод"
linktitle: "CreateCaret"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateCaret метод. Создаёт аннотацию caret в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor::CreateCaret method


Создаёт аннотацию каретки.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateCaret(int32_t page, System::Drawing::Rectangle annotRect, System::Drawing::Rectangle caretRect, const System::String &symbol, const System::String &annotContents, System::Drawing::Color color)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| caretRect | System::Drawing::Rectangle | Фактические границы базовой каретки. |
| symbol | const System::String\& | Символ будет связан с кареткой. Значение может быть: "P" (Paragraph), "None". |
| annotContents | const System::String\& | Содержимое аннотации. |
| color | System::Drawing::Color | Цвет аннотации. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
