---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters. Класс для задания параметров изменения размера страницы. Позволяет установить следующие параметры Размер результирующей страницы в стандартных единицах пространства или в процентах от начального размера страниц; Левые, Верхние, Нижние и Правые поля в стандартных единицах пространства или в процентах от начального размера страницы; Некоторые значения могут быть оставлены пустыми для автоматического расчета. Эти значения будут рассчитаны из остатка размера страницы после явного указания значений. Этот класс используется в методе ResizeContents.
type: docs
weight: 4480
url: /ru/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## Класс PdfFileEditor.ContentsResizeParameters

Класс для задания параметров изменения размера страницы. Позволяет установить следующие параметры: Размер результирующей страницы (ширина, высота) в стандартных единицах пространства или в процентах от начального размера страниц; Левые, Верхние, Нижние и Правые поля в стандартных единицах пространства или в процентах от начального размера страницы; Некоторые значения могут быть оставлены пустыми для автоматического расчета. Эти значения будут рассчитаны из остатка размера страницы после явного указания значений. Например: если ширина страницы = 100 и новая ширина страницы указана как 60 единиц, то левые и правые поля автоматически рассчитываются: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents.

```csharp
public class ContentsResizeParameters
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Создает параметры изменения размера, где все значения установлены в "авто". Позже поля и размер содержимого могут быть указаны при необходимости. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Создает параметры изменения размера с указанными значениями полей и размером содержимого. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Получает или задает нижнее поле на результирующей странице. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Получает или задает высоту содержимого исходной страницы на результирующей странице. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Получает или задает ширину содержимого исходной страницы на результирующей странице. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Получает или задает левое поле на результирующей странице. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Получает или задает правое поле на результирующей странице. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Получает или задает верхнее поле на результирующей странице. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Создает параметры изменения размера с указанным размером содержимого. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Создает параметры изменения размера с указанным размером содержимого в процентах от начального размера страницы. Параметры полей рассчитываются автоматически. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Создает параметры изменения размера с указанными значениями полей. Размер содержимого рассчитывается автоматически. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Создает параметры изменения размера. Параметры полей указаны в процентах от начального размера страницы. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Создает параметры изменения размера для изменения размера страницы. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Создает параметры изменения размера для изменения размера страницы. Новые размеры указаны в процентах. |

### См. также

* класс [PdfFileEditor](../pdffileeditor/)
* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)