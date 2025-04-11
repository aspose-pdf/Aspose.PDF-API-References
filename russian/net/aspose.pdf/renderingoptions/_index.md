---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.RenderingOptions. Представляет параметры рендеринга
type: docs
weight: 9760
url: /ru/net/aspose.pdf/renderingoptions/
---
## Класс RenderingOptions

Представляет параметры рендеринга.

```csharp
public sealed class RenderingOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Заменяет шрифты по мере необходимости, чтобы гарантировать, что все символы в тексте могут быть отображены. Алгоритм замены шрифтов выполняет следующие шаги: 1. Если пользователь явно устанавливает свойство DefaultFontName, проверьте, может ли указанный шрифт отображать желаемые символы. 2. Если шрифт, заданный пользователем, не установлен, ищите шрифты, добавленные через !:FontRepository.Sources. 3. Анализируйте текст, чтобы определить его алфавит или письменность и предложить имена шрифтов соответственно. Попытайтесь найти и использовать эти шрифты из системы. 4. В качестве резервного варианта ищите в системе любой шрифт, способный отображать необходимые символы. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Получает или устанавливает режим оптимизации штрих-кодов. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Указывает, что все шрифты будут конвертированы в версии TTF unicode. Это полезно по причинам совместимости и для оптимизации использования шрифтов, так как каждый новый шрифт TTF будет содержать не все символы из исходного шрифта, а только символы, которые используются в тексте. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Получает/устанавливает имя шрифта по умолчанию, используемое для замены отсутствующих шрифтов. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Получает или устанавливает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Получает или устанавливает указание на то, что ошибки, связанные с отсутствием шрифта, будут игнорироваться. true - означает, что ошибки отсутствия шрифта будут игнорироваться. Сегменты текста, которые ссылаются на некорректные ресурсы, будут пропущены во время обработки. по умолчанию false |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Получает или устанавливает режим высокого качества для интерполяции. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Максимальное количество шрифтов в кэше шрифтов. Значение по умолчанию - 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Максимальное количество символов в кэше символов. Значение по умолчанию - 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Получает или устанавливает режим оптимизации размеров. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Получает или устанавливает режим, в котором системные шрифты рендерятся нативно. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Использование этого флага включает механизм подсказки шрифтов. Подсказка шрифтов - это использование математических инструкций для настройки отображения шрифта с контуром. В некоторых случаях включение этого флага может решить проблемы с читаемостью текста. В данный момент использование этого флага может дать эффект только для шрифтов TTF, если эти шрифты используются в исходном документе. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Получает или устанавливает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |

### См. также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)