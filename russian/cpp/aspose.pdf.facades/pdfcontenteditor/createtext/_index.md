---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateText method"
linktitle: "CreateText"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateText method. Создаёт текстовую аннотацию в PDF‑документе в C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor::CreateText method


Создает текстовую аннотацию в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateText(System::Drawing::Rectangle rect, const System::String &title, const System::String &contents, bool open, const System::String &icon, int32_t page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| title | const System::String\& | Заголовок аннотации. |
| contents | const System::String\& | Содержимое аннотации. |
| open | bool | Флаг, указывающий, должно ли аннотирование изначально отображаться открытым. |
| icon | const System::String\& | Имя значка, которое будет использоваться при отображении аннотации. Это значение может быть: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана текстовая аннотация. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
