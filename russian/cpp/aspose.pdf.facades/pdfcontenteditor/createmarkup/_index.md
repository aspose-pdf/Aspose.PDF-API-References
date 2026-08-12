---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateMarkup метод"
linktitle: "CreateMarkup"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateMarkup метод. Создаёт разметочную аннотацию в PDF‑документе на C++."
type: docs
weight: 1600
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor::CreateMarkup method


Создаёт разметочную аннотацию в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateMarkup(System::Drawing::Rectangle rect, const System::String &contents, int32_t type, int32_t page, System::Drawing::Color clr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник, определяющий расположение аннотации на странице. |
| contents | const System::String\& | Содержимое аннотации. |
| тип | int32_t | Тип разметочной аннотации. Может быть 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| clr | System::Drawing::Color | Цвет разметки. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
