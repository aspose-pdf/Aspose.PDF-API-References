---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.FreeTextAnnotation. Представляет аннотацию свободного текста, которая отображает текст непосредственно на странице. В отличие от обычной текстовой аннотации, аннотация свободного текста не имеет открытого или закрытого состояния; вместо того чтобы отображаться в всплывающем окне, текст всегда виден.
type: docs
weight: 1810
url: /ru/net/aspose.pdf.annotations/freetextannotation/
---
## Класс FreeTextAnnotation

Представляет аннотацию свободного текста, которая отображает текст непосредственно на странице. В отличие от обычной текстовой аннотации, аннотация свободного текста не имеет открытого или закрытого состояния; вместо того чтобы отображаться в всплывающем окне, текст всегда виден.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Конструктор для использования с Генератором. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | Создает новую аннотацию FreeText на указанной странице. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Получает список действий аннотации. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Получает или устанавливает текущее состояние внешнего вида аннотации. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | Получает тип аннотации. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Получает словарь внешнего вида аннотации. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Получает или устанавливает характеристики границы аннотации. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | Массив точек, указывающий линию вызова. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Получает характеристики аннотации. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Получает или устанавливает цвет аннотации. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Получает или устанавливает текст аннотации. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Получает дату и время, когда была создана аннотация. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | Получает или устанавливает строку внешнего вида по умолчанию, которая будет использоваться для форматирования текста. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | Объект, представляющий внешний вид по умолчанию аннотации FreeText. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | Получает или устанавливает строку стиля по умолчанию. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | Получает или устанавливает стиль окончания линии для точки окончания линии. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Флаги аннотации. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Получает полное квалифицированное имя аннотации. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Получает или устанавливает высоту аннотации. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Получает или устанавливает гиперссылку фрагмента (для генератора pdf). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | Ссылка на аннотацию, на которую эта аннотация "отвечает". Обе аннотации должны находиться на одной странице документа. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | Получает или устанавливает намерение аннотации свободного текста. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Получает или устанавливает логическое значение, указывающее, будет ли этот абзац в следующей колонке. По умолчанию false. (для генерации pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Получает или устанавливает, является ли абзац встроенным. По умолчанию false. (для генерации pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Получает или устанавливает логическое значение, которое заставляет этот абзац генерироваться на новой странице. По умолчанию false. (для генерации pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Получает или устанавливает логическое значение, указывающее, остается ли текущий абзац на той же странице вместе с следующим абзацем. По умолчанию false. (для генерации pdf) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Получает или устанавливает код, указывающий форму выравнивания (оправдания), которая будет использоваться для отображения текста аннотации. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Получает или устанавливает внешний отступ для абзаца (для генерации pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Получает или устанавливает дату и время, когда аннотация была недавно изменена. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Получает или устанавливает имя аннотации на странице. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Получает или устанавливает постоянное значение непрозрачности, которое будет использоваться при рисовании аннотации. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Получает индекс страницы, содержащей аннотацию. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Всплывающая аннотация для ввода или редактирования текста, связанного с этой аннотацией. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Получает или устанавливает прямоугольник аннотации. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | Строка, указывающая отношение (тип "ответа") между этой аннотацией и одной, указанной в InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Получает или устанавливает строку с богатым текстом, которая будет отображаться во всплывающем окне, когда аннотация будет открыта. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Угол поворота аннотации. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | Получает или устанавливает стиль окончания линии для точки окончания линии. Это свойство устарело, пожалуйста, используйте EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Получает словарь внешнего вида аннотации. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Получает текст, представляющий описание объекта. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Получает или устанавливает выравнивание текста для аннотации. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | Прямоугольник, описывающий числовые различия между двумя прямоугольниками: запись Rect аннотации и прямоугольник, содержащийся внутри этого прямоугольника. Внутренний прямоугольник - это место, где должен отображаться текст аннотации. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | Получает или устанавливает стиль текста во внешнем виде. Когда стиль текста изменяется, внешний вид текста обновляется. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Получает или устанавливает текст, который будет отображаться в заголовке аннотации. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Получает или устанавливает вертикальное выравнивание абзаца. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Получает или устанавливает ширину аннотации. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Получает или устанавливает целочисленное значение, указывающее порядок Z графика. График с большим ZIndex будет размещен поверх графика с меньшим ZIndex. ZIndex может быть отрицательным. График с отрицательным ZIndex будет размещен за текстом на странице. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Принимает объект посетителя для обработки аннотации. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Обновляет параметры и внешний вид в соответствии с матричным преобразованием. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Очищает состояние и модель состояния для аннотации. Например, очищает статус обзора для аннотации. Обратите внимание, что состояние хранится в другой текстовой аннотации, которая имеет ключи состояния и модели состояния. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Клонирует этот экземпляр. Виртуальный метод. Всегда возвращает null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Размещает содержимое аннотации непосредственно на странице, объект аннотации будет удален. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Возвращает прямоугольник аннотации с учетом поворота страницы. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Получает состояние аннотации. Обратите внимание, что состояние хранится в другой текстовой аннотации, которая имеет ключи состояния и модели состояния. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Получает модель состояния аннотации. Обратите внимание, что состояние хранится в другой текстовой аннотации, которая имеет ключи состояния и модели состояния. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Устанавливает отмеченное и неотмеченное состояние для аннотации. Обратите внимание, что состояние хранится в другой текстовой аннотации, которая имеет ключи состояния и модели состояния. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Устанавливает состояние обзора для аннотации. Отмеченные и неотмеченные состояния игнорируются, так как они не относятся к модели состояния обзора. Состояние устанавливается пользователем, который создал целевую аннотацию. Значение берется из свойства Title целевой аннотации. Обратите внимание, что состояние хранится в другой текстовой аннотации, которая имеет ключи состояния и модели состояния. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Устанавливает состояние обзора для аннотации. Отмеченные и неотмеченные состояния игнорируются, так как они не относятся к модели состояния обзора. Обратите внимание, что состояние хранится в другой текстовой аннотации, которая имеет ключи состояния и модели состояния. |

### См. также

* класс [MarkupAnnotation](../markupannotation/)
* пространство имен [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* сборка [Aspose.PDF](../../)