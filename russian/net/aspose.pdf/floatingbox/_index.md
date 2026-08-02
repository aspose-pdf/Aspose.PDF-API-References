---
title: "Класс FloatingBox"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.FloatingBox."
type: docs
weight: 4990
url: /ru/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Создаёт новый экземпляр класса `FloatingBox`. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Создаёт новый экземпляр класса `FloatingBox` с указанными шириной и высотой. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Получает или задаёт объект [`Color`](../color/), указывающий цвет фона плавающего блока. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Получает или задаёт фоновое изображение для страницы (только для генератора, не заполняется при чтении документа). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Получает или задаёт объект [`BorderInfo`](../borderinfo/), указывающий информацию о границе плавающего блока. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Получает или задаёт информацию о колонке |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Получает или задаёт значение типа float, указывающее высоту плавающего блока. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Получает или задает горизонтальное выравнивание абзаца |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или задает гиперссылку фрагмента (для pdf‑генератора). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или задает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для pdf‑генерации) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или задает, является ли абзац встроенным. По умолчанию false. (для pdf‑генерации) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или задает логическое значение, принуждающее этот абзац генерироваться на новой Page. По умолчанию false. (для pdf‑генерации) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или задает логическое значение, указывающее, остаётся ли текущий абзац на той же Page вместе со следующим абзацем. По умолчанию false. (для pdf‑генерации) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Получает или задаёт значение типа bool, указывающее, нужно ли повторять абзац на следующей странице. Значение по умолчанию — false. Атрибут действителен только тогда, когда сам абзац и объект, на который ссылается его ReferenceParagraphID, оба включены в RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Получает или задает левую координату таблицы. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или задает внешний отступ для абзаца (для генерации PDF) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Получает или задаёт объект [`MarginInfo`](../margininfo/), указывающий отступы плавающего блока. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Получает или задаёт коллекцию [`Paragraphs`](./paragraphs/), содержащую все абзацы в ячейке. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Указывает вариант определения расположения FloatingBox на странице. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Получает или задает верхнюю координату таблицы. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или задает вертикальное выравнивание абзаца. |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Получает или задаёт значение типа float, указывающее ширину плавающего блока. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или задает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещён над графиком с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещён позади текста на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Создаёт клон нового объекта `FloatingBox`. Абзацы в плавающем блоке не клонируются. |

### См. также

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


