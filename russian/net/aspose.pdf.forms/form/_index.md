---
title: "Класс Form"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Forms.Form. Класс, представляющий объект формы"
type: docs
weight: 5190
url: /ru/net/aspose.pdf.forms/form/
---
## Form class

Класс, представляющий объект формы.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Если установлено, все поля формы будут пересчитываться при изменении любого поля. Значение по умолчанию — true. Установите false, чтобы повысить производительность при заполнении формы большим количеством вычисляемых полей. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Если установлено, отсутствующие поля формы будут автоматически созданы, если они присутствуют в аннотациях. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Позволяет задать порядок вычисления полей. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Получает количество полей в этой форме. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Получает или задает внешний вид формы по умолчанию (объект, описывающий шрифт, размер текста и цвет полей формы по умолчанию). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Получает ресурсы по умолчанию, размещённые в этой форме. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Если это свойство равно true, то для требуемых контейнеров элементов Xfa exclGroup будут нарисованы дополнительные красные границы. Это свойство было введено из‑за отсутствия аналогов exclGroup при конвертации представления Xfa форм в стандарт. По умолчанию false. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Получает список всех полей на самом нижнем уровне иерархической формы. |
| [HasXfa](../../aspose.pdf.forms/form/hasxfa/) { get; } | Получает значение, указывающее, содержит ли документ форму XFA. Это свойство было введено для определения, следует ли использовать [`IgnoreNeedsRendering`](./ignoreneedsrendering/) для удаления формы XFA в случаях, когда форма XFA присутствует и [`NeedsRendering`](./needsrendering/) равно false. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Если это свойство равно true, значение ключа NeedsRendering будет игнорироваться при конвертации формы XFA в стандартную форму. По умолчанию false. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Возвращает true, если объект потокобезопасен. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Получает поле формы по имени поля. Выбрасывает исключение, если поле не найдено. (2 индексатора) |
| [NeedsRendering](../../aspose.pdf.forms/form/needsrendering/) { get; } | Получает значение, указывающее, требуется ли удаление динамической формы XFA из document. Это свойство было введено для определения, следует ли использовать [`IgnoreNeedsRendering`](./ignoreneedsrendering/) для удаления формы XFA в случаях, когда форма XFA присутствует и [`NeedsRendering`](./needsrendering/) равно false. |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Если это свойство истинно, словарь "Perms" будет удалён из pdf document после преобразования динамических документов в стандартные. Словарь "Perms" может содержать правила, которые нарушают отображение выбора обязательных полей в Adobe Acrobat reader. По умолчанию значение ложно. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Если установлено, document содержит подписи, которые могут быть аннулированы, если файл сохраняется (записывается) способом, изменяющим его прежнее содержимое, в отличие от incremental update. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Если установлено, document содержит как минимум одно поле подписи. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Возвращает объект синхронизации. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Получает тип формы. Возможные значения: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Получает данные XFA формы (если присутствуют). |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Добавляет поле в форму. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Добавляет поле в форму. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Добавляет новое поле в форму; если это поле уже размещено в другой или в этой форме, создаётся копия поля. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Добавляет дополнительное отображение поля на указанную страницу документа в заданное место. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Устанавливает XFA формы в указанное значение. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Копирует поля, размещённые в форме, в массив. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Удалить поле из формы. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Удаляет поле из формы по его имени. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Экспортирует поля PDF‑формы в формат JSON и записывает результат в предоставленный поток. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Экспортирует поля PDF‑формы в формат JSON и записывает результат в указанный файл. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Удаляет все поля формы и размещает их значения непосредственно на page. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Получает перечисление полей формы. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Возвращает поля внутри указанного rectangle. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Проверьте, содержит ли форма уже указанное поле. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Определяет, добавлено ли поле с указанным именем уже в форму. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Определяет, добавлено ли поле с указанным именем уже в форму, с возможностью просматривать иерархию дочерних полей. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Импортирует поля PDF‑формы из формата JSON, предоставленного в потоке. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Импортирует поля PDF‑формы из формата JSON, предоставленного в указанном файле. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Делает аннотации полей формы независимыми. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Удаляет отображение поля по указанному индексу. Если остаётся только одно дочернее отображение, метод внедряет его в поле. |

## Поля

| Имя | Описание |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Формы могут содержать информацию о подписи, т.е. могут быть подписаны или не подписаны. И отображение формы иногда должно зависеть от того, подписана форма или нет. Это свойство сообщает конвертеру формы (например, при преобразовании XFA‑формы в стандартную форму), должна ли результирующая форма отображаться как подписанная или как неподписанная. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Класс, описывающий настройки процедуры уплощения формы. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Формы могут содержать информацию о подписи и могут быть подписаны или не подписаны. Иногда отображение форм в просмотрщике должно зависеть от того, подписана форма или нет. Этот перечислимый тип перечисляет возможные режимы рендеринга при преобразовании типа формы с учётом подписи. |

### См. также

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


