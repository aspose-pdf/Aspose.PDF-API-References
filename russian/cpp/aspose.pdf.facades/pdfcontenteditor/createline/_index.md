---
title: "Метод Aspose::Pdf::Facades::PdfContentEditor::CreateLine"
linktitle: "CreateLine"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfContentEditor::CreateLine. Создает аннотацию линии в C++."
type: docs
weight: 1400
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor::CreateLine method


Создаёт линейную аннотацию.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLine(System::Drawing::Rectangle rect, const System::String &contents, float x1, float y1, float x2, float y2, int32_t page, int32_t border, System::Drawing::Color clr, const System::String &borderStyle, const System::ArrayPtr<int32_t> &dashArray, const System::ArrayPtr<System::String> &LEArray)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| contents | const System::String\& | Содержимое аннотации. |
| x1 | float | Начальная горизонтальная координата линии. |
| y1 | float | Начальная вертикальная координата линии. |
| x2 | float | Конечная горизонтальная координата линии. |
| y2 | float | Конечная вертикальная координата линии. |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| border | int32_t | Ширина границы в пунктах. Если значение равно 0, граница не рисуется. Значение по умолчанию — 1. |
| clr | System::Drawing::Color | Цвет линии. |
| borderStyle | const System::String\& | Стиль границы, определяющий ширину и шаблон штриховки, используемые при рисовании линии. Это значение может быть: "S" (сплошная), "D" (пунктирная), "B" (скошенная), "I" (внутренняя), "U" (подчёркнутый). |
| dashArray | const System::ArrayPtr\<int32_t\>\& | Массив штрихов, определяющий шаблон пунктиров и пробелов, используемых при рисовании пунктирной границы. Если он используется, borderSyle должен быть соответственно установлен в "D". |
| LEArray | const System::ArrayPtr\<System::String\>\& | Массив из двух значений, соответственно определяющих начальный и конечный стиль рисуемой линии. Значения могут быть: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
