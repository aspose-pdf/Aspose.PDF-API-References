---
title: "Класс FooterArtifact"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.FooterArtifact. Описывает артефакт нижнего колонтитула. Может использоваться для установки нижнего колонтитула страницы."
type: docs
weight: 5050
url: /ru/net/aspose.pdf/footerartifact/
---
## FooterArtifact class

Описывает артефакт нижнего колонтитула. Это может использоваться для установки нижнего колонтитула страницы.

```csharp
public class FooterArtifact : Artifact
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FooterArtifact](footerartifact/)() | Создаёт экземпляр Footer Artifact. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Горизонтальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Вертикальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Нижний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Получает коллекцию внутренних операторов артефакта. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Получает имя подтипа артефакта. Может использоваться, если подтип артефакта не является стандартным. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Получает имя типа артефакта. Может использоваться, если тип артефакта нестандартный. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Получает XForm артефакта (если используется XForm). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Получает изображение артефакта (если присутствует). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Если true, артефакт размещается за содержимым страницы. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Левый отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Строки многострочного текстового артефакта. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Получает или задает непрозрачность артефакта. Возможные значения находятся в диапазоне 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Получает или задает позицию артефакта. Если это свойство указано, отступы и выравнивания игнорируются. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Получает прямоугольник артефакта. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Правый отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Получает или задает угол поворота артефакта. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Получает подтип артефакта. Если у артефакта нестандартный подтип, имя подтипа можно прочитать через CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Получает текст артефакта. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Состояние текста для текста артефакта. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Верхний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Получает тип артефакта. |

## Методы

| Имя | Описание |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Начинает отложенные обновления. Используйте эту функцию, если необходимо выполнить несколько изменений одного и того же артефакта для повышения производительности. Обычно операторы артефакта изменяются каждый раз, когда меняется свойство артефакта. Это приводит к изменению содержимого страницы каждый раз, когда артефакт изменяется. Чтобы избежать этого эффекта, разместите все обновления артефакта между вызовами StartUpdates/SaveUpdates. Это позволяет изменить содержимое страницы только один раз. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Освободите артефакт. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Получает пользовательское значение артефакта. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Удаляет пользовательское значение из артефакта. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Сохраняет все обновления артефакта, выполненные после вызова BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Устанавливает изображение артефакта. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Устанавливает изображение артефакта. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Устанавливает текст и свойства текста артефакта. Позволяет задавать несколько строк. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Устанавливает строку, которая будет заменена номером страницы. Значение по умолчанию — #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Устанавливает страницу PDF, которая размещается на странице документа в виде артефакта. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Устанавливает текст артефакта. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Устанавливает текст и свойства текста артефакта. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Устанавливает пользовательское значение артефакта. |

### См. также

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


