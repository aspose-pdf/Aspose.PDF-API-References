---
title: HeaderArtifact
second_title: Aspose.PDF для справочника API .NET
description: Класс описывает артефакт заголовка. Этот артефакт может быть использован для установки заголовка страницы.
type: docs
weight: 3340
url: /ru/net/aspose.pdf/headerartifact/
---
## HeaderArtifact class

Класс описывает артефакт заголовка. Этот артефакт может быть использован для установки заголовка страницы.

```csharp
public class HeaderArtifact : Artifact
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HeaderArtifact](headerartifact)() | Создает экземпляр артефакта заголовка. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | Горизонтальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | Вертикальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | Нижнее поле артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | Получает коллекцию внутренних операторов артефакта. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | Получает имя подтипа артефакта. Может использоваться, если подтип артефакта не является стандартным подтипом. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | Получает имя типа артефакта. Может использоваться, если тип артефакта нестандартный. |
| [Form](../../aspose.pdf/artifact/form) { get; } | Получает XForm артефакта (если используется XForm). |
| [Image](../../aspose.pdf/artifact/image) { get; } | Получает изображение артефакта (если присутствует). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | Если true Артефакт размещается за содержимым страницы. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | Левое поле артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | Строки многострочного текстового артефакта. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | Получает или задает непрозрачность артефакта. Возможные значения находятся в диапазоне 0..1. |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | Получает или задает позицию артефакта. Если это свойство указано, поля и выравнивание игнорируются. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | Получает прямоугольник артефакта. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | Правый край артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | Получает или задает угол поворота артефакта. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | Получает подтип артефакта. Если артефакт имеет нестандартный подтип, имя подтипа можно прочитать через CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | Получает текст артефакта. |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | Текстовое состояние для текста артефакта. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | Верхнее поле артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | Получает тип артефакта. |

## Методы

| Имя | Описание |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | Начать отложенные обновления. Используйте эту функцию, если вам нужно внести несколько изменений в один и тот же артефакт для повышения производительности. Обычно операторы артефакта меняются каждый раз, когда изменяется свойство артефакта. Это приводит к изменению содержимого страницы каждый раз при изменении артефакта. Чтобы избежать этого эффекта, поместите все обновления артефактов между вызовами StartUpdates/SaveUpdates. Это позволяет изменить содержимое страницы только один раз. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | Утилизировать артефакт. |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | Получает пользовательское значение артефакта. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | Удалить пользовательское значение из артефакта. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | Сохраняет в артефакте все обновления, сделанные после вызова BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage)(Stream) | Задает изображение артефакта. |
| [SetImage](../../aspose.pdf/artifact/setimage)(string) | Задает изображение артефакта. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | Установить текст и текстовые свойства артефакта. Позволяет указать несколько строк. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | Устанавливает страницу PDF, которая помещается на страницу документа как артефакт. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | Задает текст артефакта. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | Установить текст и текстовые свойства артефакта. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | Устанавливает пользовательское значение артефакта. |

### Смотрите также

* class [Artifact](../artifact)
* пространство имен [Aspose.Pdf](../../aspose.pdf)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
