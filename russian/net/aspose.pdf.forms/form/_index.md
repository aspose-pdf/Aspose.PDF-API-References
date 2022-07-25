---
title: Form
second_title: Aspose.PDF для справочника API .NET
description: Класс представляющий объект формы.
type: docs
weight: 3020
url: /ru/net/aspose.pdf.forms/form/
---
## Form class

Класс, представляющий объект формы.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | Если установлено, все поля формы будут пересчитываться при изменении любого поля. Значение по умолчанию — истина. Установите значение false, чтобы повысить производительность при заполнении формы с большим количеством вычисляемых полей. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | Если установлено, отсутствующие поля формы будут созданы автоматически, если они присутствуют в аннотациях. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Позволяет задать порядок расчета полей. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Получает количество полей в этой форме. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Получает или задает внешний вид формы по умолчанию (объект, который описывает шрифт по умолчанию, размер текста и цвет для полей в форме). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Получает ресурсы по умолчанию, размещенные в этой форме. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | Если это свойство истинно, то для необходимых элементов Xfa exclGroup будут нарисованы дополнительные красные прямоугольники. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | Получает список всех полей на самом низком уровне иерархической формы. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | Если это свойство истинно, значение ключа NeedsRendering будет игнорироваться при преобразовании формы XFA в стандартную форму. По умолчанию это ложь. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Возвращает true, если объект потокобезопасен. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Получает поле формы по имени поля. Выдает исключение, если поле не найдено. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | Если для этого свойства установлено значение true, словарь "Perms" будет удален из pdf-документа после преобразования динамических документов в стандартные. Словарь "Perms" может содержать правила, препятствующие отображению выбора обязательных полей в Adobe Acrobat reader. По умолчанию установлено значение false. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | Если установлено, документ содержит подписи, которые могут быть признаны недействительными, если файл сохраняется (записывается) таким образом, что изменяется его предыдущее содержимое, в отличие от добавочного обновления. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | Если установлено, документ содержит как минимум одно поле для подписи. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Возвращает объект синхронизации. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Получает тип формы. Возможные значения: Стандартный, Статический, Динамический. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Получает данные XFA формы (если есть). |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Добавляет поле в форму. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Добавляет поле в форму. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Добавляет в форму новое поле; Если это поле уже размещено на другой или этой форме, создается копия поля. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Добавляет дополнительный вид поля на указанную страницу документа в указанном месте. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Устанавливает XFA формы на указанное значение. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Копирует поля формы в массив. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Удалить поле из формы. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Удаляет поле из формы по его имени. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Удаляет все поля формы и размещает их значения прямо на странице. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Получает перечисление полей формы. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Возвращает поля внутри указанного прямоугольника. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Проверить, есть ли в форме уже указанное поле. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Определяет, добавлено ли уже поле с указанным именем в форму. |

## Поля

| Имя | Описание |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | Формы могут содержать информацию о подписи, т.е. могут быть подписаны или не подписаны. И вид формы иногда должен зависеть от того, подписана форма или нет. Это свойство сообщает конвертеру формы (например, при преобразовании формы XFA в стандартную форму) должен отображаться как подписанный или как неподписанный. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Класс, описывающий настройки процедуры выравнивания формы. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | Формы могут содержать информацию о подписи и могут быть подписанными или неподписанными. Иногда вид форм во вьювере должен зависеть от того, подписана форма или нет. Это перечисление перечисляет возможные режимы рендеринга при преобразовании типа формы в отношении знака. |

### Смотрите также

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* пространство имен [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* сборка [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
