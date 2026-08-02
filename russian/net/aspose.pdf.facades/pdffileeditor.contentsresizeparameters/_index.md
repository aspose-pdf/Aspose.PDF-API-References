---
title: "Класс PdfFileEditor.ContentsResizeParameters"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. Класс для указания параметров изменения размера страницы. Позволяет задавать следующие параметры: размер результирующей страницы (ширина, высота) в единицах пространства по умолчанию или в процентах от исходного размера страниц; левый, верхний, нижний и правый поля в единицах пространства по умолчанию или в процентах от исходного размера страницы. Некоторые значения могут быть оставлены null для автоматического вычисления. Эти значения будут рассчитаны из оставшегося размера страницы после вычисления явно указанных значений. Например, если ширина страницы = 100, а новая ширина страницы указана как 60 единиц, то левое и правое поля автоматически рассчитываются как (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents."
type: docs
weight: 4600
url: /ru/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters class

Класс для указания параметров изменения размера страницы. Позволяет задавать следующие параметры: размер результирующей страницы (ширина, высота) в единицах пространства по умолчанию или в процентах от исходного размера страниц; левое, верхнее, нижнее и правое поля в единицах пространства по умолчанию или в процентах от исходного размера страницы; некоторые значения могут быть оставлены null для автоматического вычисления. Эти значения будут рассчитаны из оставшегося размера страницы после вычисления явно указанных значений. Например: если ширина страницы = 100, а новая ширина страницы указана как 60 единиц, то левое и правое поля автоматически рассчитываются: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Создаёт параметры изменения размера, где все значения установлены в "auto". Позднее поля и размер содержимого могут быть указаны при необходимости. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Создаёт параметры изменения размера с указанными значениями полей и размером содержимого. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Получает или задаёт нижнее поле результирующей страницы. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Получает или задаёт высоту содержимого исходной страницы на результирующей странице. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Получает или задаёт ширину содержимого исходной страницы на результирующей странице. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Получает или задаёт левое поле результирующей страницы. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Получает или задает правый отступ на результирующей странице. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Получает или задает верхний отступ на результирующей странице. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Создает параметры изменения размера с указанным размером содержимого. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Создает параметры изменения размера с указанным размером содержимого в процентах от исходного размера страницы. Отступы рассчитываются автоматически. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Создает параметры изменения размера с указанным значением отступов. Размер содержимого рассчитывается автоматически. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Создает параметры изменения размера. Отступы задаются в процентах от исходного размера страницы. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Создает параметры изменения размера страницы. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Создает параметры изменения размера страницы. Новые размеры задаются в процентах. |

### См. также

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


