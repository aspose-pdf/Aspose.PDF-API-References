---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.FloatingBox.
type: docs
weight: 4870
url: /ru/net/aspose.pdf/floatingbox/
---
## Класс FloatingBox

```csharp
public class FloatingBox : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Инициализирует новый экземпляр класса `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Инициализирует новый экземпляр класса `FloatingBox` с заданной шириной и высотой. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Получает или задает объект [`Color`](../color/), который указывает цвет фона плавающего блока. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Получает или задает фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Получает или задает объект [`BorderInfo`](../borderinfo/), который указывает информацию о границе плавающего блока. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Получает или задает информацию о колонне |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Получает или задает значение с плавающей запятой, которое указывает высоту плавающего блока. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для генератора pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, которое указывает, будет ли этот абзац в следующей колонне. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, которое указывает, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Получает или задает логическое значение, которое указывает, нужно ли повторять абзац на следующей странице. Значение по умолчанию false. Атрибут действителен только тогда, когда сам абзац и объект, на который ссылается его ReferenceParagraphID, оба включены в RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Получает или задает левую координату таблицы. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации pdf) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Получает или задает объект [`MarginInfo`](../margininfo/), который указывает отступ плавающего блока. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Получает или задает коллекцию [`Paragraphs`](./paragraphs/), которая указывает все абзацы в ячейке. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Указывает вариант для определения местоположения FloatingBox на странице. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Получает или задает верхнюю координату таблицы. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Получает или задает значение с плавающей запятой, которое указывает ширину плавающего блока. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, которое указывает Z-упорядочение графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Клонирует новый объект `FloatingBox`. Абзацы в плавающем блоке не клонируются. |

### См. также

* класс [BaseParagraph](../baseparagraph/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)