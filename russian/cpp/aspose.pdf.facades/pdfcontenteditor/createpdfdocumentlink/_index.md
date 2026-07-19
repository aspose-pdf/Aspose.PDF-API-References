---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink метод"
linktitle: "CreatePdfDocumentLink"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink метод. Создает ссылку на другую страницу PDF‑документа в C++."
type: docs
weight: 1800
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t) method


Создаёт ссылку на страницу другого PDF‑документа.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| remotePdf | const System::String\& | PDF‑документ, страница которого будет открыта. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
| destinationPage | int32_t | Страница назначения. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) method


Создаёт ссылку на страницу другого PDF‑документа.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| remotePdf | const System::String\& | PDF‑документ, страница которого будет открыта. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
| destinationPage | int32_t | Страница назначения. |
| clr | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Создаёт ссылку на страницу другого PDF‑документа.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreatePdfDocumentLink(System::Drawing::Rectangle rect, const System::String &remotePdf, int32_t originalPage, int32_t destinationPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| remotePdf | const System::String\& | PDF‑документ, страница которого будет открыта. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
| destinationPage | int32_t | Страница назначения. |
| clr | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Массив действий (члены перечисления PredefinedAction), соответствующих выполнению пунктов меню в просмотрщике Acrobat. |

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
