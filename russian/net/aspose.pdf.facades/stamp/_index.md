---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Facades.Stamp. Класс, представляющий штамп
type: docs
weight: 4720
url: /ru/net/aspose.pdf.facades/stamp/
---
## Класс Штамп

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
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Получает или задает значение BlendingColorSpace, которое определяет цветовое пространство, используемое для выполнения операций прозрачности и смешивания на странице. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Получает или задает статус фона. Если true, штамп будет размещен как фон на штампованной странице. По умолчанию установлено значение false. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Получает или задает непрозрачность штампа. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Получает или задает номер страницы. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Получает или задает массив с номерами страниц, на которые будет воздействовать штамп. Если Pages = null, на все страницы документа будет оказано воздействие. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Получает или задает качество изображения штампа в процентах. Допустимые значения 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Получает или задает угол поворота штампа в градусах. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Получает или задает идентификатор штампа. |

## Методы

| Имя | Описание |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Устанавливает изображение, которое будет использоваться в качестве штампа. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Устанавливает изображение в качестве штампа. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Устанавливает текст в качестве штампа. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Устанавливает PDF-файл и номер страницы, который будет использоваться в качестве штампа. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Устанавливает PDF-файл и номер страницы, который будет использоваться в качестве штампа. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Устанавливает состояние текста штампа. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Устанавливает размер изображения штампа. Изображение будет масштабироваться в соответствии с указанными значениями. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Устанавливает позицию на странице, где будет размещен штамп. |

### См. также

* пространство имен [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../)