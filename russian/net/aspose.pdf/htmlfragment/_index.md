---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.HtmlFragment. Представляет html фрагмент
type: docs
weight: 5520
url: /ru/net/aspose.pdf/htmlfragment/
---
## Класс HtmlFragment

Представляет html фрагмент.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Инициализирует новый экземпляр класса HtmlFragment. |

## Свойства

| Название | Описание |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Получает или задает HtmlLoadOptions, которые будут использоваться для загрузки (и рендеринга) HTML в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо использовать конкретные настройки для импорта HTML для этого или того экземпляра (например, когда этот или тот экземпляр должен использовать конкретный BasePath для импортированного HTML или должен использовать конкретный загрузчик внешних ресурсов). Если параметр по умолчанию (null), то будут использоваться стандартные параметры загрузки HTML. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для генератора pdf). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Получает или задает разбиение слов |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, которое указывает, будет ли этот абзац в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, которое указывает, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Получает или задает, имеет ли абзац стандартный отступ, в противном случае отступ равен 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации pdf) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Получает прямоугольник HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Получает или задает шрифт |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, которое указывает порядок Z графика. График с большим ZIndex будет размещен над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен позади текста на странице. |

## Методы

| Название | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Клонирует html фрагмент. |

### См. также

* класс [FormattedFragment](../formattedfragment/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)