---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Vector.SvgExtractionOptions. Представляет класс параметров для извлечения векторной графики из страницы pdf-документа
type: docs
weight: 11240
url: /ru/net/aspose.pdf.vector/svgextractionoptions/
---
## Класс SvgExtractionOptions

Представляет класс параметров для извлечения векторной графики из страницы pdf-документа.

```csharp
public class SvgExtractionOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Получает и устанавливает параметр для автоматической группировки подпутей в изображения. Этот параметр исключает опцию [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Получает и устанавливает параметр для извлечения каждого подпути из PDF-документа в отдельные SVG-изображения. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Получает и устанавливает ограничивающий прямоугольник, который определяет область извлечения для SVG-извлечения. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Получает и устанавливает параметр силы группировки подпутей в изображения. Позволяет настроить степень группировки подпутей. Значение варьируется от 0 до 1. Значение 0 соответствует включенной опции [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/). Значение 1 создаст одно изображение для всех векторных путей на странице. Параметр имеет эффект, когда [`AutoGrouping`](./autogrouping/) равно false. Значение по умолчанию — `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Получает или устанавливает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если в PDF используется более тонкая ширина штриха, она будет заменена на эту ширину. Значение по умолчанию — 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Получает и устанавливает параметр для строгой проверки того, находятся ли подпути в указанном прямоугольнике в [`ExtractionAreaBound`](./extractionareabound/). Если установлено значение false, то подпути, которые не полностью включены в [`ExtractionAreaBound`](./extractionareabound/), будут извлечены. Значение по умолчанию — `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Получает и устанавливает флаг, который определяет, должны ли XForm, найденные на страницах, быть распакованы или нет. Элементы XForm могут оказаться в разных SVG-файлах. Только XForms, которые отображаются с помощью операторов Do из содержимого страницы, распаковываются. Вложенные XForms не распаковываются. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Получает и устанавливает параметр для распаковки только XForm, соответствующего указанному предикату. |

### См. также

* пространство имен [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../)