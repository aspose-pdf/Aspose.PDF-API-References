---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Forms.Form. Класс, представляющий объект формы
type: docs
weight: 5070
url: /ru/net/aspose.pdf.forms/form/
---
## Класс Формы

Класс, представляющий объект формы.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Свойства

| Название | Описание |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Если установлено, все поля формы будут пересчитаны при изменении любого поля. Значение по умолчанию - true. Установите в false, чтобы повысить производительность при заполнении формы с большим количеством вычисляемых полей. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Если установлено, отсутствующие поля формы будут автоматически созданы, если они присутствуют в аннотациях. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Позволяет установить порядок вычисления полей. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Получает количество полей в этой форме. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Получает или устанавливает внешний вид формы по умолчанию (объект, который описывает шрифт по умолчанию, размер текста и цвет для полей на форме). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Получает ресурсы по умолчанию, размещенные на этой форме. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Если это свойство истинно, то дополнительные красные границы будут нарисованы для контейнеров обязательных элементов Xfa exclGroup. Это свойство было введено из-за отсутствия аналогов для exclGroup при конвертации представления форм Xfa в стандартное. По умолчанию оно равно false. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Получает список всех полей на самом низком уровне иерархической формы. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Если это свойство истинно, значение ключа NeedsRendering будет игнорироваться при конвертации формы XFA в стандартную форму. По умолчанию оно равно false. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Возвращает true, если объект потокобезопасен. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Получает поле формы по имени поля. Вызывает исключение, если поле не найдено. (2 индексатора) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Если это свойство истинно, словарь "Perms" будет удален из PDF-документа после конвертации динамических документов в стандартные. Словарь "Perms" может содержать правила, которые мешают отображению выбора обязательных полей в Adobe Acrobat Reader. По умолчанию оно равно false. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Если установлено, документ содержит подписи, которые могут быть недействительными, если файл сохранен (записан) таким образом, что изменяет его предыдущие содержимое, в отличие от инкрементального обновления. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Если установлено, документ содержит хотя бы одно поле подписи. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Возвращает объект синхронизации. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Получает тип формы. Возможные значения: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Получает данные XFA формы (если присутствуют). |

## Методы

| Название | Описание |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Добавляет поле на форму. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Добавляет поле на форму. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Добавляет новое поле в форму; если это поле уже размещено на другой или этой форме, создается копия поля. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Добавляет дополнительный внешний вид поля на указанной странице документа в указанном месте. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Устанавливает XFA формы на указанное значение. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Копирует поля, размещенные на форме, в массив. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Удаляет поле из формы. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Удаляет поле из формы по его имени. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Экспортирует поля PDF формы в формат JSON и записывает результат в предоставленный поток. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Экспортирует поля PDF формы в формат JSON и записывает результат в указанный файл. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Удаляет все поля формы и помещает их значения непосредственно на страницу. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Получает перечисление полей формы. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Возвращает поля внутри указанного прямоугольника. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Проверяет, есть ли в форме указанное поле. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Определяет, добавлено ли поле с указанным именем в форму. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Определяет, добавлено ли поле с указанным именем в форму, с возможностью просматривать иерархию дочерних полей. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Импортирует поля PDF формы из формата JSON, предоставленного в потоке. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Импортирует поля PDF формы из формата JSON, предоставленного в указанном файле. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Делает аннотации полей формы независимыми. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Удаляет внешний вид поля по указанному индексу. Если остался только один дочерний внешний вид, метод встраивает его в поле. |

## Поля

| Название | Описание |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Формы могут содержать информацию о подписании, т.е. могут быть подписанными или неподписанными. И вид формы иногда должен зависеть от того, подписана форма или нет. Это свойство сообщает конвертеру формы (например, при конвертации формы XFA в стандартную форму), должен ли результат формы отображаться как подписанный или неподписанный. |

## Другие Члены

| Название | Описание |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Класс, который описывает настройки для процедуры уплощения формы. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Формы могут содержать информацию о подписании и могут быть подписанными или неподписанными. Иногда вид форм в просмотрщике должен зависеть от того, подписана форма или нет. Этот перечисляемый тип перечисляет возможные режимы рендеринга при конвертации типа формы в отношении подписи. |

### См. Также

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)