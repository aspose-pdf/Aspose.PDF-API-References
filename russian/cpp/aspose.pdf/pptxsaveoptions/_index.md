---
title: "Aspose::Pdf::PptxSaveOptions class"
linktitle: "PptxSaveOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::PptxSaveOptions class. Параметры сохранения для экспорта в формат SVG в C++."
type: docs
weight: 15800
url: /ru/cpp/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class


Параметры сохранения для экспорта в формат SVG.

```cpp
class PptxSaveOptions : public Aspose::Pdf::UnifiedSaveOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_CustomProgressHandler](./get_customprogresshandler/)() const | Этот обработчик можно использовать для обработки событий прогресса конвертации, напр., его можно использовать для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц, пример кода обработчика, показывающего прогресс в консоли: |
| [get_ImageResolution](./get_imageresolution/)() const | Получает разрешение изображения (dpi). По умолчанию 192 dpi. |
| [get_OptimizeTextBoxes](./get_optimizetextboxes/)() const | Переключает распознавание колонок текста. |
| [get_SeparateImages](./get_separateimages/)() const | Если установлено в true, то изображения отделяются от всей остальной графики. |
| [get_SlidesAsImages](./get_slidesasimages/)() const | Если установлено в true, то всё содержимое распознаётся как изображения (по одному на страницу). |
| [PptxSaveOptions](./pptxsaveoptions/)() | Конструктор. |
| [set_CustomProgressHandler](./set_customprogresshandler/)(UnifiedSaveOptions::ConversionProgressEventHandler) | Этот обработчик можно использовать для обработки событий прогресса конвертации, напр., его можно использовать для отображения индикатора прогресса или сообщений о текущем количестве обработанных страниц, пример кода обработчика, показывающего прогресс в консоли: |
| [set_ImageResolution](./set_imageresolution/)(int32_t) | Устанавливает разрешение изображения (dpi). По умолчанию 192 dpi. |
| [set_OptimizeTextBoxes](./set_optimizetextboxes/)(bool) | Переключает распознавание колонок текста. |
| [set_SeparateImages](./set_separateimages/)(bool) | Если установлено в true, то изображения отделяются от всей остальной графики. |
| [set_SlidesAsImages](./set_slidesasimages/)(bool) | Если установлено в true, то всё содержимое распознаётся как изображения (по одному на страницу). |
## См. также

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
