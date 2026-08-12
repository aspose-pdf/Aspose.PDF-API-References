---
title: "Aspose::Pdf::RenderingOptions class"
linktitle: "RenderingOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::RenderingOptions. Представляет параметры рендеринга в C++."
type: docs
weight: 16400
url: /ru/cpp/aspose.pdf/renderingoptions/
---
## RenderingOptions class


Представляет параметры рендеринга.

```cpp
class RenderingOptions : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [get_AnalyzeFonts](./get_analyzefonts/)() const | Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов следует этим шагам: |
| [get_BarcodeOptimization](./get_barcodeoptimization/)() const | Получает режим оптимизации штрих‑кода. |
| [get_ConvertFontsToUnicodeTTF](./get_convertfontstounicodettf/)() const | Указывает, что все шрифты будут преобразованы в версии TTF Unicode. Это полезно по соображениям совместимости и для оптимизации использования шрифтов, поскольку каждый новый шрифт TTF будет содержать не все символы исходного шрифта, а только те, которые используются в тексте. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Получает/устанавливает имя шрифта по умолчанию, используемого для замены отсутствующих шрифтов. |
| [get_HeightExtraUnits](./get_heightextraunits/)() const | Получает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Получает указание, что ошибки, связанные с отсутствием шрифта, будут игнорироваться. true — означает, что ошибки отсутствия шрифта будут игнорироваться. Сегменты [Text](../../aspose.pdf.text/), ссылающиеся на некорректные ресурсы, будут пропущены при обработке. По умолчанию false. |
| [get_InterpolationHighQuality](./get_interpolationhighquality/)() const | Получает режим высокого качества для интерполяции. |
| [get_MaxFontsCacheSize](./get_maxfontscachesize/)() const | Максимальное количество шрифтов в кэше шрифтов. Значение по умолчанию — 10. |
| [get_MaxSymbolsCacheSize](./get_maxsymbolscachesize/)() const | Максимальное количество символов в кэше символов. Значение по умолчанию — 100. |
| [get_OptimizeDimensions](./get_optimizedimensions/)() const | Получает режим оптимизации размеров. |
| [get_ScaleImagesToFitPageWidth](./get_scaleimagestofitpagewidth/)() const | Получает значение, используемое для масштабирования всех изображений на странице до ширины страницы. |
| [get_SystemFontsNativeRendering](./get_systemfontsnativerendering/)() const | Получает режим, при котором системные шрифты отображаются нативно. |
| [get_UseFontHinting](./get_usefonthinting/)() const | Использование этого флага включает механизм хинтинга шрифтов. Хинтинг шрифтов — это использование математических инструкций для корректировки отображения контурного шрифта. В некоторых случаях включение этого флага может решить проблемы с читаемостью текста. В текущий момент использование этого флага может оказывать эффект только для шрифтов TTF, если эти шрифты используются в исходном документе. |
| [get_UseNewImagingEngine](./get_usenewimagingengine/)() const | Получает флаг, определяющий, используется ли новый движок визуализации или нет. |
| [get_WidthExtraUnits](./get_widthextraunits/)() const | Получает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |
| [RenderingOptions](./renderingoptions/)() | Инициализирует новый экземпляр объекта [RenderingOptions](./). |
| [set_AnalyzeFonts](./set_analyzefonts/)(bool) | Заменяет шрифты по мере необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов следует этим шагам: |
| [set_BarcodeOptimization](./set_barcodeoptimization/)(bool) | Устанавливает режим оптимизации штрихкода. |
| [set_ConvertFontsToUnicodeTTF](./set_convertfontstounicodettf/)(bool) | Указывает, что все шрифты будут преобразованы в версии TTF Unicode. Это полезно по соображениям совместимости и для оптимизации использования шрифтов, поскольку каждый новый шрифт TTF будет содержать не все символы исходного шрифта, а только те, которые используются в тексте. |
| [set_DefaultFontName](./set_defaultfontname/)(const System::String\&) | Получает/устанавливает имя шрифта по умолчанию, используемого для замены отсутствующих шрифтов. |
| [set_HeightExtraUnits](./set_heightextraunits/)(float) | Устанавливает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Устанавливает индикатор, указывающий, что ошибки, связанные с отсутствием шрифта, будут игнорироваться. true — означает, что ошибки отсутствия шрифта будут игнорироваться. Сегменты [Text](../../aspose.pdf.text/), ссылающиеся на некорректные ресурсы, будут пропускаться при обработке. По умолчанию false. |
| [set_InterpolationHighQuality](./set_interpolationhighquality/)(bool) | Устанавливает режим высокого качества для интерполяции. |
| [set_MaxFontsCacheSize](./set_maxfontscachesize/)(int32_t) | Максимальное количество шрифтов в кэше шрифтов. Значение по умолчанию — 10. |
| [set_MaxSymbolsCacheSize](./set_maxsymbolscachesize/)(int32_t) | Максимальное количество символов в кэше символов. Значение по умолчанию — 100. |
| [set_OptimizeDimensions](./set_optimizedimensions/)(bool) | Устанавливает режим оптимизации размеров. |
| [set_ScaleImagesToFitPageWidth](./set_scaleimagestofitpagewidth/)(bool) | Устанавливает значение, используемое для масштабирования всех изображений на странице до ширины страницы. |
| [set_SystemFontsNativeRendering](./set_systemfontsnativerendering/)(bool) | Устанавливает режим, при котором системные шрифты отображаются нативно. |
| [set_UseFontHinting](./set_usefonthinting/)(bool) | Использование этого флага включает механизм хинтинга шрифтов. Хинтинг шрифтов — это использование математических инструкций для корректировки отображения контурного шрифта. В некоторых случаях включение этого флага может решить проблемы с читаемостью текста. В текущий момент использование этого флага может оказывать эффект только для шрифтов TTF, если эти шрифты используются в исходном документе. |
| [set_UseNewImagingEngine](./set_usenewimagingengine/)(bool) | Устанавливает флаг, определяющий, используется ли новый движок визуализации или нет. |
| [set_WidthExtraUnits](./set_widthextraunits/)(float) | Устанавливает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
