---
title: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters конструктор"
linktitle: "ContentsResizeParameters"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters конструктор. Создает параметры изменения размера, где все значения установлены в \"auto\". Позже при необходимости могут быть указаны поля и размер содержимого в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/contentsresizeparameters/
---
## ContentsResizeParameters::ContentsResizeParameters() constructor


Создаёт параметры изменения размера, где все значения установлены в "auto". Позже при необходимости можно указать поля и размер содержимого.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters()
```

## См. также

* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
## ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) constructor


Создаёт параметры изменения размера с указанными значениями полей и размером содержимого.

```cpp
Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters::ContentsResizeParameters(const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &leftMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsWidth, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &rightMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &topMargin, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &contentsHeight, const System::SharedPtr<PdfFileEditor::ContentsResizeValue> &bottomMargin)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| leftMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Слева](../../../../aspose.pdf/left/) значение поля. |
| contentsWidth | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Ширина содержимого. |
| rightMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | [Справа](../../../../aspose.pdf/right/) поле. |
| topMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Верхний отступ. |
| contentsHeight | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Высота содержимого. |
| bottomMargin | const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\& | Нижний отступ. |
## Примечания



Пустые значения означают, что соответствующее значение рассчитывается автоматически
## См. также

* Typedef [SharedPtr](../../../../system/sharedptr/)
* Class [ContentsResizeValue](../../contentsresizevalue/)
* Class [ContentsResizeParameters](../)
* Class [PdfFileEditor](../../)
* Namespace [Aspose::Pdf::Facades](../../../)
* Library [Aspose.PDF for C++](../../../../)
