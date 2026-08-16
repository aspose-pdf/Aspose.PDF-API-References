---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Справочник API Aspose.PDF для Java"
description: "Преобразованный PDF может содержать растровые изображения (.png, *.jpeg и т.д.). Этот перечисление определяет способы обработки растровых изображений при преобразовании PDF в HTML."
type: docs
weight: 2140
url: /ru/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

Преобразованный PDF может содержать растровые изображения (.png, *.jpeg и т.д.). Этот перечисление определяет способы обработки растровых изображений при преобразовании PDF в HTML.

## Поля

| Поле | Описание |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Для каждой результирующей страницы будет сгенерирован один большой PNG‑файл фона. Растровые изображения будут встроены в этот файл и отрисованы как области этого изображения. Отдельные PNG‑файлы для каждого изображения создаваться не будут, будет присутствовать только один PNG‑файл на страницу в наборе файлов результата конвертации. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Отдельные растровые изображения будут сохранены как PNG‑файлы, но будут ссылаться через обёртывающие SVG‑изображения, т.е. для каждого растрового изображения будет создан один PNG‑файл и один SVG, и каждый такой SVG будет содержать ссылки на соответствующий PNG‑файл. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | Для каждого отдельного растрового файла будет сгенерировано обёртывающее SVG‑изображение, а растровое изображение будет встроено в него в виде строк, закодированных в Base64. |
| [DontSave](#DontSave) | Не сохранять изображения для фиксированного макета |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Для каждой результирующей страницы будет сгенерирован один большой PNG‑файл фона. Растровые изображения будут встроены в этот файл и отрисованы как области этого изображения. Отдельные PNG‑файлы для каждого изображения создаваться не будут, будет присутствовать только один PNG‑файл на страницу в наборе файлов результата конвертации.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Отдельные растровые изображения будут сохранены как PNG‑файлы, но будут ссылаться через обёртывающие SVG‑изображения, т.е. для каждого растрового изображения будет создан один PNG‑файл и один SVG, и каждый такой SVG будет содержать ссылки на соответствующий PNG‑файл.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

Для каждого отдельного растрового файла будет сгенерировано обёртывающее SVG‑изображение, а растровое изображение будет встроено в него в виде строк, закодированных в Base64.

### DontSave {#DontSave}
```
public static final int DontSave
```

Не сохранять изображения для фиксированного макета
