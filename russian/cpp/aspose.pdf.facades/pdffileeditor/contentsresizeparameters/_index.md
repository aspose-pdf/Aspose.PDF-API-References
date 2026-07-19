---
title: "Класс Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters"
linktitle: "ContentsResizeParameters"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Facades::PdfFileEditor::ContentsResizeParameters. Класс для указания параметров изменения размера страницы. Позволяет задавать следующие параметры: размер результирующей страницы (ширина, высота) в единицах пространства по умолчанию или в процентах от исходного размера страниц; поля Left, Top, Bottom и Right в единицах пространства по умолчанию или в процентах от исходного размера страницы; некоторые значения могут быть оставлены null для автоматического вычисления. Эти значения будут рассчитаны из оставшегося размера страницы после вычисления явно указанных значений. Например: если ширина страницы = 100 и новая ширина страницы указана как 60 единиц, тогда левое и правое поля рассчитываются автоматически: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents в C++."
type: docs
weight: 7300
url: /ru/cpp/aspose.pdf.facades/pdffileeditor/contentsresizeparameters/
---
## ContentsResizeParameters class


Класс для указания параметров изменения размера страницы. Позволяет задавать следующие параметры: размер результирующей страницы (ширина, высота) в единицах пространства по умолчанию или в процентах от исходного размера страниц; поля [Left](../../../aspose.pdf/left/), Top, Bottom и [Right](../../../aspose.pdf/right/) в единицах пространства по умолчанию или в процентах от исходного размера страницы; некоторые значения могут быть оставлены null для автоматического вычисления. Эти значения будут рассчитаны из оставшегося размера страницы после вычисления явно указанных значений. Например: если ширина страницы = 100 и новая ширина страницы указана как 60 единиц, тогда левое и правое поля рассчитываются автоматически: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents.

```cpp
class ContentsResizeParameters : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [ContentSize](./contentsize/)(double, double) | Создаёт параметры изменения размера с указанным размером содержимого. |
| static [ContentSizePercent](./contentsizepercent/)(double, double) | Создаёт параметры изменения размера с указанным размером содержимого в процентах от исходного размера страницы. Поля рассчитываются автоматически. |
| [ContentsResizeParameters](./contentsresizeparameters/)() | Создаёт параметры изменения размера, где все значения установлены в "auto". Позже при необходимости можно указать поля и размер содержимого. |
| [ContentsResizeParameters](./contentsresizeparameters/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Создаёт параметры изменения размера с указанными значениями полей и размером содержимого. |
| [get_BottomMargin](./get_bottommargin/)() const | Получает нижнее поле результирующей страницы. |
| [get_ChangeMediaBox](./get_changemediabox/)() const | Получает и задаёт, следует ли корректировать MediaBox страницы PDF во время операции изменения размера. Значение по умолчанию — **false** |
| [get_ContentsHeight](./get_contentsheight/)() const | Получает высоту содержимого исходной страницы на результирующей странице. |
| [get_ContentsWidth](./get_contentswidth/)() const | Получает ширину содержимого исходной страницы на результирующей странице. |
| [get_LeftMargin](./get_leftmargin/)() const | Получает левое поле результирующей страницы. |
| [get_RightMargin](./get_rightmargin/)() const | Получает правый отступ на результирующей странице. |
| [get_TopMargin](./get_topmargin/)() const | Получает верхний отступ на результирующей странице. |
| static [Margins](./margins/)(double, double, double, double) | Создает параметры изменения размера с указанным значением отступов. Размер содержимого рассчитывается автоматически. |
| static [MarginsPercent](./marginspercent/)(double, double, double, double) | Создает параметры изменения размера. Отступы указываются в процентах от начального размера страницы. |
| static [PageResize](./pageresize/)(double, double) | Создает параметры изменения размера страницы. |
| static [PageResizePct](./pageresizepct/)(double, double) | Создает параметры изменения размера страницы. Новые размеры указываются в процентах. |
| [set_BottomMargin](./set_bottommargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Устанавливает нижний отступ на результирующей странице. |
| [set_ChangeMediaBox](./set_changemediabox/)(bool) | Получает и задаёт, следует ли корректировать MediaBox страницы PDF во время операции изменения размера. Значение по умолчанию — **false** |
| [set_ContentsHeight](./set_contentsheight/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Устанавливает высоту содержимого исходной страницы на результирующей странице. |
| [set_ContentsWidth](./set_contentswidth/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Устанавливает ширину содержимого исходной страницы на результирующей странице. |
| [set_LeftMargin](./set_leftmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Устанавливает левый отступ на результирующей странице. |
| [set_RightMargin](./set_rightmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Устанавливает правый отступ на результирующей странице. |
| [set_TopMargin](./set_topmargin/)(const System::SharedPtr\<PdfFileEditor::ContentsResizeValue\>\&) | Устанавливает верхний отступ на результирующей странице. |
## См. также

* Class [Object](../../../system/object/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
