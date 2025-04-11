---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsRasterImagesSavingModes от Aspose.Pdf. Конвертированный PDF может содержать растровые изображения .png .jpeg и т.д. Этот перечисляемый тип определяет методы обработки растровых изображений во время конвертации PDF в HTML
type: docs
weight: 5720
url: /ru/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## Перечисление HtmlSaveOptions.RasterImagesSavingModes

Конвертированный PDF может содержать растровые изображения (.png, *.jpeg и т.д.) Этот перечисляемый тип определяет методы обработки растровых изображений во время конвертации PDF в HTML

```csharp
public enum RasterImagesSavingModes
```

### Значения

| Название | Значение | Описание |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | для каждого отдельного растрового файла будет сгенерировано оберточное SVG изображение, и растровое изображение будет встроено как строки, закодированные в Base64, в это SVG изображение |
| AsExternalPngFilesReferencedViaSvg | `1` | отдельные растровые изображения будут сохранены как PNG файлы, но будут ссылаться через оберточные SVG изображения, т.е. будет сгенерирован один PNG файл и одно SVG для каждого растрового изображения, и каждое из таких SVG будет содержать ссылки на соответствующий PNG файл |
| AsEmbeddedPartsOfPngPageBackground | `2` | Будет сгенерирован один большой PNG файл фона для каждой результирующей страницы. Растровые изображения будут встроены в этот файл и отображены как области этого изображения. Внешние PNG файлы для каждого изображения не будут сгенерированы, только один PNG файл на страницу будет присутствовать в наборе файлов результата конвертации. |
| DontSave | `3` | Не сохранять изображения для фиксированной компоновки |

### См. также

* класс [HtmlSaveOptions](../htmlsaveoptions/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)