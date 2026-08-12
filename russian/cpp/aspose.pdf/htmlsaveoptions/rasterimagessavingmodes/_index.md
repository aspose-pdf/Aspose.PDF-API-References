---
title: "Aspose::Pdf::HtmlSaveOptions::RasterImagesSavingModes enum"
linktitle: "RasterImagesSavingModes"
second_title: "Справочник API Aspose.PDF для C++"
description: "Перечисление Aspose::Pdf::HtmlSaveOptions::RasterImagesSavingModes. Преобразованный PDF может содержать растровые изображения (.png, *.jpeg и т.д.). Это перечисление определяет способы обработки растровых изображений при конвертации PDF в HTML в C++."
type: docs
weight: 5900
url: /ru/cpp/aspose.pdf/htmlsaveoptions/rasterimagessavingmodes/
---
## RasterImagesSavingModes enum


Конвертированный PDF может содержать растровые изображения (.png, *.jpeg и т.д.). Этот enum определяет методы обработки растровых изображений при конвертации PDF в HTML.

```cpp
enum class RasterImagesSavingModes
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | 0 | для каждого отдельного растрового файла будет сгенерировано обёртывающее SVG‑изображение, а растровое изображение будет встроено в это SVG‑изображение в виде строк, закодированных в Base64 |
| AsExternalPngFilesReferencedViaSvg | 1 | отдельные растровые изображения будут сохранены как PNG‑файлы, но будут ссылаться через обёртывающие SVG‑изображения, то есть для каждого растрового изображения будет сгенерирован один PNG‑файл и один SVG, и каждый такой SVG будет содержать ссылки на соответствующий PNG‑файл |
| AsEmbeddedPartsOfPngPageBackground | 2 | Для каждой результирующей страницы будет создан один большой PNG‑файл фона. Растровые изображения будут встроены в этот файл и отрисованы как области этого изображения. Внешние PNG‑файлы для каждого изображения создаваться не будут, вместо этого будет присутствовать один PNG‑файл на страницу в наборе файлов результата конвертации. |
| DontSave | 3 | Не сохранять изображения для фиксированного макета. |

## См. также

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
