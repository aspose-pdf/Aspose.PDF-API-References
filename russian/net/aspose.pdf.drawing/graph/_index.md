---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Drawing.Graph. Представляет графический генератор графиков параграфа
type: docs
weight: 3940
url: /ru/net/aspose.pdf.drawing/graph/
---
## Класс Граф

Представляет граф - графический генератор параграфа.

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
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | Получает или задает значение с плавающей запятой, которое указывает высоту графика. Единица измерения - пункт. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание параграфа |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для генератора pdf). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | Получает или задает изменение текущей позиции после обработки параграфа. (по умолчанию true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, которое указывает, будет ли этот параграф в следующем столбце. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли параграф встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот параграф генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, которое указывает, остается ли текущий параграф на той же странице вместе с следующим параграфом. По умолчанию false. (для генерации pdf) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | Получает или задает левую координату таблицы. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для параграфа (для генерации pdf) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | Получает или задает коллекцию [`Shapes`](./shapes/), которая указывает все фигуры в графике. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | Получает или задает строковое значение, которое указывает заголовок графика. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | Получает или задает верхнюю координату таблицы. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание параграфа |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | Получает или задает значение с плавающей запятой, которое указывает ширину графика. Единица измерения - пункт. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, которое указывает Z- порядок графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | Клонирует график. |

### См. также

* класс [BaseParagraph](../../aspose.pdf/baseparagraph/)
* пространство имен [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* сборка [Aspose.PDF](../../)