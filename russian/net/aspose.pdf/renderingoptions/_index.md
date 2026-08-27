---
title: "Класс RenderingOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.RenderingOptions. Представляет параметры рендеринга"
type: docs
weight: 9910
url: /ru/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

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
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Заменяет шрифты при необходимости, чтобы обеспечить отображение всех символов в тексте. Алгоритм подстановки шрифтов выполняет следующие шаги: 1. Если пользователь явно задает свойство DefaultFontName, проверяется, может ли указанный шрифт отображать требуемые символы. 2. Если пользовательский шрифт не задан, производится поиск шрифтов, добавленных через !:FontRepository.Sources. 3. Анализируется текст для определения его алфавита или письменности и предлагаются соответствующие названия шрифтов. Пытается найти и использовать эти шрифты в системе. 4. В качестве резервного варианта ищется любой шрифт в системе, способный отображать необходимые символы. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Получает или задает режим оптимизации штрихкода. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Указывает, что все шрифты будут преобразованы в версии TTF Unicode. Это полезно по соображениям совместимости и для оптимизации использования шрифтов, поскольку каждый новый шрифт TTF будет содержать не все символы исходного шрифта, а только те, которые используются в тексте. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Получает/задает имя шрифта по умолчанию, используемого для замены отсутствующих шрифтов. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Получает или задает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Получает или задает индикатор, указывающий, что ошибки, связанные с отсутствием шрифта, будут игнорироваться. true — означает, что ошибки отсутствия шрифта будут игнорироваться. Сегменты текста, ссылающиеся на некорректные ресурсы, будут пропущены во время обработки. false по умолчанию. |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Получает или задает режим высокого качества для интерполяции. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Максимальное количество шрифтов в кэше шрифтов. Значение по умолчанию — 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Максимальное количество символов в кэше символов. Значение по умолчанию — 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Получает или задает режим оптимизации размеров. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Получает или задает режим, при котором системные шрифты рендерятся нативно. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Использование этого флага включает механизм хинтинга шрифтов. Хинтинг шрифтов — это применение математических инструкций для корректировки отображения контурного шрифта. В некоторых случаях включение этого флага может решить проблемы с читаемостью текста. На данный момент использование этого флага оказывает влияние только на шрифты TTF, если эти шрифты используются в исходном документе. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Получает или задает значение, используемое для увеличения или уменьшения ширины прямоугольника для оператора AppendRectangle. |

### См. также

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


