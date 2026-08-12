---
title: "Aspose::Pdf::Artifact class"
linktitle: "Артефакт"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Artifact class. Класс представляет объект PDF Artifact в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.pdf/artifact/
---
## Artifact class


Класс представляет объект PDF [Artifact](./).

```cpp
class Artifact : public System::IDisposable
```

## Enums

| Перечисление | Описание |
| --- | --- |
| [ArtifactSubtype](./artifactsubtype/) | Перечисление возможных подтипов артефактов. |
| [ArtifactType](./artifacttype/) | Перечисление возможных типов артефактов. |
## Методы

| Метод | Описание |
| --- | --- |
| [Artifact](./artifact/)(const System::String\&, const System::String\&) | Конструктор артефакта с указанным типом и подтипом. |
| [Artifact](./artifact/)(Artifact::ArtifactType, Artifact::ArtifactSubtype) | Конструктор артефакта с указанным типом и подтипом. |
| [BeginUpdates](./beginupdates/)() | Начать отложенные обновления. Используйте эту функцию, если необходимо выполнить несколько изменений одного и того же артефакта для повышения производительности. Обычно операторы артефакта изменяются каждый раз, когда изменяется свойство артефакта. Это приводит к изменению содержимого страницы каждый раз при изменении артефакта. Чтобы избежать этого эффекта, поместите все обновления артефакта между вызовами StartUpdates/SaveUpdates. Это позволяет изменить содержимое страницы только один раз. |
| [Dispose](./dispose/)() override | Освободить артефакт. |
| [get_ArtifactHorizontalAlignment](./get_artifacthorizontalalignment/)() const | Горизонтальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [get_ArtifactVerticalAlignment](./get_artifactverticalalignment/)() const | Вертикальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [get_BottomMargin](./get_bottommargin/)() const | Нижний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [get_Contents](./get_contents/)() | Получает коллекцию внутренних операторов артефакта. |
| [get_CustomSubtype](./get_customsubtype/)() | Получает имя подтипа артефакта. Может использоваться, если подтип артефакта не является стандартным. |
| [get_CustomType](./get_customtype/)() | Получает имя типа артефакта. Может использоваться, если тип артефакта не является стандартным. |
| [get_Form](./get_form/)() | Получает [XForm](../xform/) артефакта (если используется [XForm](../xform/)). |
| [get_Image](./get_image/)() | Получает изображение артефакта (если присутствует). |
| [get_IsBackground](./get_isbackground/)() const | Если true, [Artifact](./) размещается за содержимым страницы. |
| [get_LeftMargin](./get_leftmargin/)() const | [Left](../left/) отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [get_Lines](./get_lines/)() | Строки многострочного текстового артефакта. |
| [get_Opacity](./get_opacity/)() const | Получает непрозрачность артефакта. Возможные значения находятся в диапазоне 0..1. |
| [get_Position](./get_position/)() const | Получает позицию артефакта. Если это свойство указано, то отступы и выравнивания игнорируются. |
| [get_Rectangle](./get_rectangle/)() | Получает прямоугольник артефакта. |
| [get_RightMargin](./get_rightmargin/)() const | [Right](../right/) отступ справа артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [get_Rotation](./get_rotation/)() | Получает угол поворота артефакта. |
| [get_Subtype](./get_subtype/)() | Получает подтип артефакта. Если у артефакта нестандартный подтип, его название можно получить через CustomSubtype. |
| [get_Text](./get_text/)() | Получает текст артефакта. |
| [get_TextState](./get_textstate/)() | [Text](../../aspose.pdf.text/) состояние текста артефакта. |
| [get_TopMargin](./get_topmargin/)() const | Верхний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [get_Type](./get_type/)() | Получает тип артефакта. |
| [GetValue](./getvalue/)(const System::String\&) | Получает пользовательское значение артефакта. |
| [RemoveValue](./removevalue/)(const System::String\&) | Удалить пользовательское значение из артефакта. |
| [SaveUpdates](./saveupdates/)() | Сохраняет все изменения артефакта, сделанные после вызова [BeginUpdates()](./beginupdates/). |
| [set_ArtifactHorizontalAlignment](./set_artifacthorizontalalignment/)(HorizontalAlignment) | Горизонтальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [set_ArtifactVerticalAlignment](./set_artifactverticalalignment/)(VerticalAlignment) | Вертикальное выравнивание артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [set_BottomMargin](./set_bottommargin/)(double) | Нижний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [set_CustomSubtype](./set_customsubtype/)(const System::String\&) | Получает имя подтипа артефакта. Может использоваться, если подтип артефакта не является стандартным. |
| [set_CustomType](./set_customtype/)(const System::String\&) | Получает имя типа артефакта. Может использоваться, если тип артефакта не является стандартным. |
| [set_IsBackground](./set_isbackground/)(bool) | Если true, [Artifact](./) размещается за содержимым страницы. |
| [set_LeftMargin](./set_leftmargin/)(double) | [Left](../left/) отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [set_Opacity](./set_opacity/)(double) | Устанавливает непрозрачность артефакта. Возможные значения находятся в диапазоне 0..1. |
| [set_Position](./set_position/)(const System::SharedPtr\<Point\>\&) | Устанавливает позицию артефакта. Если это свойство указано, то отступы и выравнивания игнорируются. |
| [set_RightMargin](./set_rightmargin/)(double) | [Right](../right/) отступ справа артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [set_Rotation](./set_rotation/)(double) | Устанавливает угол поворота артефакта. |
| [set_Subtype](./set_subtype/)(Artifact::ArtifactSubtype) | Получает подтип артефакта. Если у артефакта нестандартный подтип, его название можно получить через CustomSubtype. |
| [set_Text](./set_text/)(const System::String\&) | Получает текст артефакта. |
| [set_TextState](./set_textstate/)(const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | [Text](../../aspose.pdf.text/) состояние текста артефакта. |
| [set_TopMargin](./set_topmargin/)(double) | Верхний отступ артефакта. Если позиция указана явно (в свойстве Position), это значение игнорируется. |
| [set_Type](./set_type/)(Artifact::ArtifactType) | Получает тип артефакта. |
| [SetImage](./setimage/)(const System::SharedPtr\<System::IO::Stream\>\&) | Устанавливает изображение артефакта. |
| [SetImage](./setimage/)(const System::String\&) | Устанавливает изображение артефакта. |
| [SetLinesAndState](./setlinesandstate/)(const System::ArrayPtr\<System::String\>\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Устанавливает текст и свойства текста артефакта. Позволяет задавать несколько строк. |
| [SetPageNumberReplacementString](./setpagenumberreplacementstring/)(const System::String\&) | Устанавливает, какая строка будет заменена номером страницы. Значение по умолчанию — #. |
| [SetPdfPage](./setpdfpage/)(const System::SharedPtr\<Page\>\&) | Устанавливает страницу PDF, которая размещается на странице документа как артефакт. |
| [SetText](./settext/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Устанавливает текст артефакта. |
| [SetTextAndState](./settextandstate/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Устанавливает текст и свойства текста артефакта. |
| [SetValue](./setvalue/)(const System::String\&, const System::String\&) | Устанавливает пользовательское значение артефакта. |
## См. также

* Class [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
