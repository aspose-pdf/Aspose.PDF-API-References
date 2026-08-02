---
title: "Класс SvgExtractionOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Vector.SvgExtractionOptions. Представляет класс параметров для извлечения векторной графики со страницы pdf документа."
type: docs
weight: 11430
url: /ru/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

Представляет класс параметров для извлечения векторной графики со страницы PDF‑документа.

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
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Получает и задает параметр автоматической группировки подмассивов в изображения. Этот параметр исключает параметр [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Получает и задает параметр извлечения каждого подпути из PDF документа в отдельные SVG изображения. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Получает и задает ограничивающий прямоугольник, определяющий область извлечения для SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Получает и задает параметр Сила группировки подмассивов в изображения. Позволяет настроить степень группировки подмассивов. Диапазон значений от 0 до 1. Значение 0 соответствует включенному параметру [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/). Значение 1 создаст единое изображение для всех векторных путей на странице. Параметр влияет, когда [`AutoGrouping`](./autogrouping/) отключён. Значение по умолчанию — `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Получает или задает минимальную ширину штриха, которая будет использоваться в результирующем SVG. Если PDF использует более тонкую ширину штриха, она будет заменена этой шириной. Значение по умолчанию — 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Получает и задает параметр, строго проверяющий, находятся ли подпути внутри указанного прямоугольника в [`ExtractionAreaBound`](./extractionareabound/). Если установить в false, то подпути, не полностью включённые в [`ExtractionAreaBound`](./extractionareabound/), будут извлечены. Значение по умолчанию — `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Получает и задает флаг, определяющий, следует ли распаковывать найденные на страницах XFrom. Элементы XFrom могут оказаться в разных SVG‑файлах. Распаковываются только XForm, отрисованные операторами Do из содержимого страницы. Вложенные XForm не распаковываются. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Получает и задает параметр распаковки только того XForm, который соответствует указанному предикату. |

### См. также

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


