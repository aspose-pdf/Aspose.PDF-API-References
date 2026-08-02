---
title: "Перечисление HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Перечисление Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes. Конвертированный PDF может содержать растровые изображения .png, .jpeg и т.д. Это перечисление определяет методы обработки растровых изображений при преобразовании PDF в HTML."
type: docs
weight: 5850
url: /ru/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Конвертированный PDF может содержать растровые изображения (.png, *.jpeg и т.д.). Это перечисление определяет методы обработки растровых изображений при преобразовании PDF в HTML.

```csharp
public enum RasterImagesSavingModes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | Для каждого отдельного растрового файла будет сгенерировано обёрточное SVG‑изображение, а растровое изображение будет встроено в виде строк, закодированных в Base64, в это SVG‑изображение. |
| AsExternalPngFilesReferencedViaSvg | `1` | Отдельные растровые изображения будут сохранены как PNG‑файлы, но будут ссылаться через обёрточные SVG‑изображения, то есть для каждого растрового изображения будет сгенерирован один PNG‑файл и один SVG, и каждый такой SVG будет содержать ссылки на соответствующий PNG‑файл. |
| AsEmbeddedPartsOfPngPageBackground | `2` | Для каждой результирующей страницы будет сгенерирован один большой PNG‑файл фона. Растровые изображения будут встроены в этот файл и отрисованы как области этого изображения. Внешние PNG‑файлы для каждого изображения создаваться не будут, будет присутствовать только один PNG‑файл на страницу в наборе файлов результата конвертации. |
| DontSave | `3` | Не сохранять изображения для фиксированной раскладки. |

### См. также

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


