---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink method"
linktitle: "CreateApplicationLink"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink method. Создаёт ссылку для запуска приложения в PDF‑документе на C++."
type: docs
weight: 700
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t) method


Создаёт ссылку для запуска приложения в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| приложение | const System::String\& | Путь к приложению, которое будет запущено. |
| страница | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) method


Создаёт ссылку для запуска приложения в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page, System::Drawing::Color clr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| приложение | const System::String\& | Путь к приложению, которое будет запущено. |
| страница | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
| clr | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Создаёт ссылку для запуска приложения в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateApplicationLink(System::Drawing::Rectangle rect, const System::String &application, int32_t page, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| приложение | const System::String\& | Путь к приложению, которое будет запущено. |
| страница | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
| clr | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Массив действий (члены перечисления PredefinedAction), соответствующих выполнению пунктов меню в просмотрщике Acrobat. |
## Примечания



///
## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
