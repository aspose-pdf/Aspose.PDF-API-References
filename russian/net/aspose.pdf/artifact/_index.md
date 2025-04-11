---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Artifact. Класс представляет объект PDF Артефакт
type: docs
weight: 2770
url: /ru/net/aspose.pdf/artifact/
---
## Класс Артефакт

Класс представляет объект PDF Артефакт.

```csharp
public class Artifact : IDisposable
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Конструктор артефакта с указанным типом и подтипом |
| [Artifact](artifact/#constructor_1)(string, string) | Конструктор артефакта с указанным типом и подтипом |

## Свойства

| Название | Описание |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Горизонтальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Вертикальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Нижний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Получает коллекцию внутренних операторов артефакта. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Получает имя подтипа артефакта. Может использоваться, если подтип артефакта не является стандартным. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Получает имя типа артефакта. Может использоваться, если тип артефакта нестандартный. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Получает XForm артефакта (если используется XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Получает изображение артефакта (если присутствует). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Если true, артефакт размещен за содержимым страницы. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Левый отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Строки многострочного текстового артефакта. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Получает или устанавливает непрозрачность артефакта. Возможные значения в диапазоне 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Получает или устанавливает позицию артефакта. Если это свойство указано, то отступы и выравнивания игнорируются. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Получает прямоугольник артефакта. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Правый отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Получает или устанавливает угол поворота артефакта. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Получает подтип артефакта. Если артефакт имеет нестандартный подтип, имя подтипа может быть прочитано через CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Получает текст артефакта. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Состояние текста для текста артефакта. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Верхний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Получает тип артефакта. |

## Методы

| Название | Описание |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Начать отложенные обновления. Используйте эту функцию, если вам нужно внести несколько изменений в один и тот же артефакт для повышения производительности. Обычно операторы артефакта изменяются каждый раз, когда изменяется свойство артефакта. Это вызывает изменение содержимого страницы каждый раз, когда артефакт изменяется. Чтобы избежать этого эффекта, поместите все обновления артефакта между вызовами StartUpdates/SaveUpdates. Это позволяет изменить содержимое страницы только один раз. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Удаляет артефакт. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Получает пользовательское значение артефакта. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Удаляет пользовательское значение из артефакта. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Сохраняет все обновления в артефакте, которые были сделаны после вызова BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Устанавливает изображение артефакта. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Устанавливает изображение артефакта. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Устанавливает текст и свойства текста артефакта. Позволяет указать несколько строк. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Устанавливает, какая строка будет заменена номером страницы. Значение по умолчанию - #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Устанавливает PDF-страницу, которая размещена на странице документа в качестве артефакта. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Устанавливает текст артефакта. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Устанавливает текст и свойства текста артефакта. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Устанавливает пользовательское значение артефакта. |

## Другие Члены

| Название | Описание |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Перечисление возможных подтипов артефактов. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Перечисление возможных типов артефактов. |

### См. Также

* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)