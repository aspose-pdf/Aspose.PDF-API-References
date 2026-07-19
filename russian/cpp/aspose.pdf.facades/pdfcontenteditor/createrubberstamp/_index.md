---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp метод"
linktitle: "CreateRubberStamp"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp метод. Создаёт аннотацию‑штамп в C++."
type: docs
weight: 2200
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::SharedPtr\<System::IO::Stream\>\&) method


Создаёт аннотацию штампа.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &annotContents, System::Drawing::Color color, const System::SharedPtr<System::IO::Stream> &appearanceStream)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| annotContents | const System::String\& | Содержимое аннотации. |
| color | System::Drawing::Color | Цвет аннотации. |
| appearanceStream | const System::SharedPtr\<System::IO::Stream\>\& | Поток файла внешнего вида. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::String\&) method


Создаёт аннотацию штампа.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &annotContents, System::Drawing::Color color, const System::String &appearanceFile)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| annotContents | const System::String\& | Содержимое аннотации. |
| color | System::Drawing::Color | Цвет аннотации. |
| appearanceFile | const System::String\& | Путь к файлу внешнего вида. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateRubberStamp(int32_t, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) method


Создаёт аннотацию штампа.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateRubberStamp(int32_t page, System::Drawing::Rectangle annotRect, const System::String &icon, const System::String &annotContents, System::Drawing::Color color)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | int32_t | Номер оригинальной страницы, на которой будет создана аннотация. |
| annotRect | System::Drawing::Rectangle | Прямоугольник аннотации, определяющий её расположение на странице. |
| icon | const System::String\& | Иконка будет использоваться при отображении аннотации. Значение по умолчанию: 'Draft'. |
| annotContents | const System::String\& | Содержимое аннотации. |
| color | System::Drawing::Color | Цвет аннотации. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
