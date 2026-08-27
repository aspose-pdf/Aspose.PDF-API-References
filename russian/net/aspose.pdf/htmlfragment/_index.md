---
title: "Класс HtmlFragment"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.HtmlFragment класс. Представляет html fragment"
type: docs
weight: 5650
url: /ru/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

Представляет HTML‑фрагмент.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Инициализирует новый экземпляр класса HtmlFragment. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Получает или задает HtmlLoadOptions, которые будут использоваться для загрузки (и рендеринга) HTML в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо применить конкретные настройки импорта HTML для того или иного экземпляра (например, когда тот или иной экземпляр должен использовать определённый BasePath для импортированного HTML или должен использовать определённый загрузчик внешних ресурсов). Если параметр имеет значение по умолчанию (null), будут использованы стандартные параметры загрузки HTML. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Получает или задает разрыв слов |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Получает или задает, имеет ли абзац отступ по умолчанию, иначе отступ равен 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Получает прямоугольник HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Получает или задает шрифт |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Клонирует html fragment. |

### См. также

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


