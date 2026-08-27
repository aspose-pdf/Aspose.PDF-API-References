---
title: "Класс Graph"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Drawing.Graph. Представляет график, генератор графики абзаца"
type: docs
weight: 4060
url: /ru/net/aspose.pdf.drawing/graph/
---
## Graph class

Представляет граф — абзац генератора графики.

```csharp
public sealed class Graph : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | Инициализирует новый экземпляр класса `Graph`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | Получает или задает границу. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | Получает или задает объект [`GraphInfo`](./graphinfo/), который указывает информацию о графике, такую как цвет, ширина линии и т.д. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Получает или задает значение типа float, указывающее высоту графика. Единица измерения — пункт. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Получает или задает изменение текущей позиции после обработки абзаца. (по умолчанию true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Получает или задает левую координату таблицы. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Получает или задает коллекцию [`Shapes`](./shapes/), которая указывает все фигуры в графике. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Получает или задает строковое значение, указывающее заголовок графика. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Получает или задает верхнюю координату таблицы. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Получает или задает значение типа float, указывающее ширину графика. Единица измерения — пункт. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Клонировать график. |

### См. также

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)


