---
title: "Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink метод"
linktitle: "CreateCustomActionLink"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink метод. Создаёт ссылку на пользовательские действия в PDF‑документе на C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor::CreateCustomActionLink method


Создаёт ссылку на пользовательские действия в PDF‑документе.

```cpp
void Aspose::Pdf::Facades::PdfContentEditor::CreateCustomActionLink(System::Drawing::Rectangle rect, int32_t originalPage, System::Drawing::Color color, const System::ArrayPtr<System::SharedPtr<System::BoxedValueBase>> &actionName)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | System::Drawing::Rectangle | Прямоугольник для активного клика. |
| originalPage | int32_t | Номер исходной страницы, на которой будет создан прямоугольник, привязанный к ссылке. |
| color | System::Drawing::Color | Цвет прямоугольника при активном щелчке. |
| actionName | const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\& | Массив действий (члены перечисления PredefinedAction), соответствующих выполнению пунктов меню в просмотрщике Acrobat. |
## Примечания



///
## См. также

* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Color](../../../system.drawing/color/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BoxedValueBase](../../../system/boxedvaluebase/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
