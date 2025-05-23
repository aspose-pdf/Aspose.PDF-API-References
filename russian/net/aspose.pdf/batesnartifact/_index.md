---
title: Class BatesNArtifact
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.BatesNArtifact. Класс описывает артефакт нумерации Бейтса
type: docs
weight: 2850
url: /ru/net/aspose.pdf/batesnartifact/
---
## Класс BatesNArtifact

Класс описывает артефакт нумерации Бейтса.

```csharp
public class BatesNArtifact : PaginationArtifact
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BatesNArtifact](batesnartifact/)() | Инициализирует новый экземпляр класса `BatesNArtifact`. Этот конструктор является внутренним и создает экземпляр артефакта заголовка с значениями по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Горизонтальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Вертикальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Нижний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Получает коллекцию внутренних операторов артефакта. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Получает имя подтипа артефакта. Может использоваться, если подтип артефакта не является стандартным. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Получает имя типа артефакта. Может использоваться, если тип артефакта нестандартный. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Получает или задает номер конечной страницы для артефакта. Значение должно быть больше или равно 0. Если установлено значение меньше 0, оно будет скорректировано до 0. Значение по умолчанию 0 означает, что границы конечной страницы отсутствуют. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Получает XForm артефакта (если используется XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Получает изображение артефакта (если присутствует). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Если true, артефакт размещается за содержимым страницы. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Левый отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Строки многострочного текстового артефакта. |
| [NumberOfDigits](../../aspose.pdf/batesnartifact/numberofdigits/) { get; set; } | Получает или задает количество цифр для нумерации Бейтса. Значение должно быть в диапазоне от 3 до 15 включительно. Если установлено значение меньше 3, оно будет скорректировано до 3. Если установлено значение больше 15, оно будет скорректировано до 15. Значение по умолчанию 6. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Получает или задает непрозрачность артефакта. Возможные значения в диапазоне 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Получает или задает позицию артефакта. Если это свойство указано, то отступы и выравнивания игнорируются. |
| [Prefix](../../aspose.pdf/batesnartifact/prefix/) { get; set; } | Получает или задает префикс, который будет добавлен к номеру Бейтса. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Получает прямоугольник артефакта. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Правый отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Получает или задает угол поворота артефакта. |
| [StartNumber](../../aspose.pdf/batesnartifact/startnumber/) { get; set; } | Получает или задает начальный номер для нумерации Бейтса. Значение должно быть больше или равно 1. Если установлено значение меньше 1, оно будет скорректировано до 1. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Получает или задает номер начальной страницы для артефакта. Значение должно быть больше или равно 1. Если установлено значение меньше 1, оно будет скорректировано до 1. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Получает или задает подмножество страниц, к которым применяется артефакт (например, все страницы, четные страницы, нечетные страницы). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Получает подтип артефакта. Если артефакт имеет нестандартный подтип, имя подтипа может быть прочитано через CustomSubtype. |
| [Suffix](../../aspose.pdf/batesnartifact/suffix/) { get; set; } | Получает или задает суффикс, который будет добавлен к номеру Бейтса. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Получает текст артефакта. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Состояние текста для текста артефакта. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Верхний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Получает тип артефакта. |

## Методы

| Имя | Описание |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Начать отложенные обновления. Используйте эту функцию, если вам нужно внести несколько изменений в один и тот же артефакт для повышения производительности. Обычно операторы артефакта изменяются каждый раз, когда изменяется свойство артефакта. Это вызывает изменение содержимого страницы каждый раз, когда артефакт изменяется. Чтобы избежать этого эффекта, поместите все обновления артефакта между вызовами StartUpdates/SaveUpdates. Это позволяет изменить содержимое страницы только один раз. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Освобождает артефакт. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Получает пользовательское значение артефакта. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Удаляет пользовательское значение из артефакта. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Сохраняет все обновления в артефакте, которые были сделаны после вызова BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Устанавливает изображение артефакта. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Устанавливает изображение артефакта. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Устанавливает текст и свойства текста артефакта. Позволяет указать несколько строк. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Устанавливает, какая строка будет заменена номером страницы. Значение по умолчанию - #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Устанавливает PDF-страницу, которая размещается на странице документа в качестве артефакта. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Устанавливает текст артефакта. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Устанавливает текст и свойства текста артефакта. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Устанавливает пользовательское значение артефакта. |

### См. также

* класс [PaginationArtifact](../paginationartifact/)
* пространство имен [Aspose.Pdf](../../aspose.pdf/)
* сборка [Aspose.PDF](../../)