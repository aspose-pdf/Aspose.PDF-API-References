---
title: "Класс Stamp"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Facades.Stamp. Класс, представляющий штамп"
type: docs
weight: 4840
url: /ru/net/aspose.pdf.facades/stamp/
---
## Stamp class

Класс, представляющий штамп.

```csharp
public sealed class Stamp
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Stamp](stamp/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Получает или задает значение BlendingColorSpace, определяющее цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Получает или задает статус фона. Если true, штамп будет размещён как фон обработанной страницы. По умолчанию установлено false. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Получает или задает непрозрачность штампа. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Получает или задает номер страницы. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Получает или задает массив номеров страниц, которые будут затронуты штампом. Если Pages = null, затронуты все страницы документа. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Получает или задает качество штампа‑изображения в процентах. Допустимые значения 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Получает или задает вращение штампа в градусах. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Получает или задает идентификатор штампа. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Устанавливает изображение, которое будет использоваться в качестве штампа. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Устанавливает изображение как штамп. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Устанавливает текст в качестве штампа. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Устанавливает PDF‑файл и номер страницы, которые будут использоваться в качестве штампа. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Устанавливает PDF‑файл и номер страницы, которые будут использоваться в качестве штампа. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Устанавливает состояние текста штампа. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Устанавливает размер штампа‑изображения. Изображение будет масштабировано в соответствии с указанными значениями. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Устанавливает позицию на странице, где будет размещён штамп |

### См. также

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


