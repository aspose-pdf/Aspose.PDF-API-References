---
title: "Метод Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink"
linktitle: "CreateWebLink"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink. Создает веб‑ссылку в PDF‑документе на C++."
type: docs
weight: 2600
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## PdfContentEditor::CreateWebLink(System::Drawing::Rectangle, const System::String\&, int32_t) method


Создает веб‑ссылку в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink(System::Drawing::Rectangle rect, const System::String &url, int32_t originalPage)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| url | const System::String\& | Назначение веб‑ссылки. |
| originalPage | int32_t | Номер оригинальной страницы, на которой будет создан прямоугольник, связанный с веб‑ссылкой. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateWebLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) method


Создает веб‑ссылку в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink(System::Drawing::Rectangle rect, const System::String &url, int32_t originalPage, System::Drawing::Color clr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| url | const System::String\& | Назначение веб‑ссылки. |
| originalPage | int32_t | Номер оригинальной страницы, на которой будет создан прямоугольник, связанный с веб‑ссылкой. |
| clr | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateWebLink(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Создает веб‑ссылку в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateWebLink(System::Drawing::Rectangle rect, const System::String &url, int32_t originalPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| url | const System::String\& | Назначение веб‑ссылки. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к веб‑ссылке. |
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
