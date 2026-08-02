---
title: "Класс TeXFragment"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.TeXFragment. Представляет фрагмент TeX"
type: docs
weight: 10540
url: /ru/net/aspose.pdf/texfragment/
---
## TeXFragment class

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
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Получает или задает TeXLoadOptions, которые будут использоваться для загрузки (и отрисовки) LaTeX в этот экземпляр класса. Пожалуйста, используйте его, когда необходимо применить специфические настройки импорта LaTeX для того или иного экземпляра (например, когда данный экземпляр должен использовать определённый BasePath для импортированного LaTeX или использовать определённый загрузчик внешних ресурсов). Если параметр имеет значение по умолчанию (null), будут использованы стандартные параметры загрузки LaTeX. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Клонирует фрагмент. |

### См. также

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


