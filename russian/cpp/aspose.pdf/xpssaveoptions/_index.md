---
title: "Aspose::Pdf::XpsSaveOptions class"
linktitle: "XpsSaveOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XpsSaveOptions class. Параметры сохранения для экспорта в формат Xps в C++."
type: docs
weight: 21100
url: /ru/cpp/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class


Параметры сохранения для экспорта в формат Xps.

```cpp
class XpsSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                       public Aspose::Pdf::IPipelineOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_BatchSize](./get_batchsize/)() override | Определяет размер пакета, если пакетная конвертация применима к паре форматов источника и назначения. |
| [get_DefaultFont](./get_defaultfont/)() const | Получает/устанавливает имя шрифта по умолчанию. Используется, если встроенное имя шрифта не найдено в системе. |
| [get_SaveTransparentTexts](./get_savetransparenttexts/)() const | Указывает, следует ли сохранять прозрачный (распознанный OCR) текст. |
| [get_UseEmbeddedTrueTypeFonts](./get_useembeddedtruetypefonts/)() const | Получает/устанавливает флаг использования встроенных шрифтов TrueType. Отказ от использования встроенных шрифтов TrueType может сократить время конвертации. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Получает параметр UseNewImagingEngine. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Определяет размер пакета, если пакетная конвертация применима к паре форматов источника и назначения. |
| [set_DefaultFont](./set_defaultfont/)(const System::String\&) | Получает/устанавливает имя шрифта по умолчанию. Используется, если встроенное имя шрифта не найдено в системе. |
| [set_SaveTransparentTexts](./set_savetransparenttexts/)(bool) | Указывает, следует ли сохранять прозрачный (распознанный OCR) текст. |
| [set_UseEmbeddedTrueTypeFonts](./set_useembeddedtruetypefonts/)(bool) | Получает/устанавливает флаг использования встроенных шрифтов TrueType. Отказ от использования встроенных шрифтов TrueType может сократить время конвертации. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Устанавливает параметр UseNewImagingEngine. |
| [XpsSaveOptions](./xpssaveoptions/)() | Конструктор. |
## См. также

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
