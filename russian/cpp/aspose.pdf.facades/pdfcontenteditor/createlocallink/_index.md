---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink method"
linktitle: "CreateLocalLink"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink method. Создаёт локальную ссылку в PDF‑документе в C++."
type: docs
weight: 1500
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t) method


Создаёт локальную ссылку в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| desPage | int32_t | Страница назначения. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к локальной ссылке. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) method


Создаёт локальную ссылку в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| desPage | int32_t | Страница назначения. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к локальной ссылке. |
| clr | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) method


Создаёт локальную ссылку в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateLocalLink(System::Drawing::Rectangle rect, int32_t desPage, int32_t originalPage, System::Drawing::Color clr, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| desPage | int32_t | Страница назначения. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к локальной ссылке. |
| clr | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Массив действий (члены перечисления PredefinedAction), соответствующих выполнению пунктов меню в просмотрщике Acrobat. |

## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
