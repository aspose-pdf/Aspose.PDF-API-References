---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.TeXFragment. Представляет фрагмент TeX
type: docs
weight: 10360
url: /ru/net/aspose.pdf/texfragment/
---
## Класс TeXFragment

Представляет фрагмент TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | Инициализирует новый экземпляр класса HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | Инициализирует новый экземпляр класса HtmlFragment. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации pdf) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и рендеринга) LaTeX в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать конкретные настройки для импорта LaTeX для этого или того экземпляра (например, когда этот или тот экземпляр должен использовать конкретный BasePath для импортированного LaTeX или должен использовать конкретный загрузчик внешних ресурсов). Если параметр по умолчанию (null), то будут использоваться стандартные параметры загрузки LaTeX. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Клонирует фрагмент. |

### См. также

* класс [FormattedFragment](../formattedfragment/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)