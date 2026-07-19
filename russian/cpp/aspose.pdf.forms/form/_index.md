---
title: "Aspose::Pdf::Forms::Form class"
linktitle: "Form"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::Form class. Класс, представляющий объект формы в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf.forms/form/
---
## Form class


Класс, представляющий объект формы.

```cpp
class Form : public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Nested classes

* Class [FlattenSettings](./flattensettings/)
## Enums

| Перечисление | Описание |
| --- | --- |
| [SignDependentElementsRenderingModes](./signdependentelementsrenderingmodes/) | [Forms](../) могут содержать информацию о подписи и могут быть подписаны или не подписаны. Иногда отображение форм в просмотрщике должно зависеть от того, подписана форма или нет. Этот перечислимый тип перечисляет возможные режимы отображения при конвертации типа формы относительно подписи. |
## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Field\>\&, int32_t) | Добавляет поле в форму. |
| [Add](./add/)(const System::SharedPtr\<Field\>\&) | Добавляет поле в форму. |
| [Add](./add/)(System::SharedPtr\<Field\>, const System::String\&, int32_t) | Добавляет новое поле в форму; если это поле уже размещено в другой или этой форме, создаётся копия поля. |
| [AddFieldAppearance](./addfieldappearance/)(const System::SharedPtr\<Field\>\&, int32_t, const System::SharedPtr\<Rectangle\>\&) | Добавляет дополнительное отображение поля на указанную страницу документа в заданное место. |
| [AssignXfa](./assignxfa/)(const System::SharedPtr\<System::Xml::XmlDocument\>\&) | Устанавливает [XFA](../xfa/) формы в указанное значение. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<Field\>\>\&, int32_t) | Копирует поля, размещённые в форме, в массив. |
| [Delete](./delete/)(const System::SharedPtr\<Field\>\&) | Удалить поле из формы. |
| [Delete](./delete/)(const System::String\&) | Удаляет поле из формы по его имени. |
| [Flatten](./flatten/)() | Удаляет все поля формы и размещает их значения непосредственно на странице. |
| [get_AutoRecalculate](./get_autorecalculate/)() const | Если установлено, все поля формы будут пересчитываться при изменении любого поля. Значение по умолчанию — true. Установите false, чтобы повысить производительность при заполнении формы большим количеством вычисляемых полей. |
| [get_AutoRestoreForm](./get_autorestoreform/)() const | Если установлено, отсутствующие поля формы будут автоматически созданы, если они присутствуют в аннотациях. |
| [get_Count](./get_count/)() const override | Получает количество полей в этой форме. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Получает внешний вид формы по умолчанию (объект, описывающий шрифт, размер текста и цвет полей формы по умолчанию). |
| [get_DefaultResources](./get_defaultresources/)() | Получает ресурсы по умолчанию, размещённые в этой форме. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | Если это свойство истинно, то для контейнеров обязательных элементов Xfa exclGroup будут нарисованы дополнительные красные ограничивающие прямоугольники. Это свойство было введено из‑за отсутствия аналогов exclGroup при конвертации представления Xfa форм в стандарт. По умолчанию — false. |
| [get_Fields](./get_fields/)() | Получает список всех полей на самом нижнем уровне иерархической формы. |
| [get_HasXfa](./get_hasxfa/)() | Получает значение, указывающее, содержит ли документ форму [XFA](../xfa/). Это свойство было введено для определения, следует ли использовать [IgnoreNeedsRendering](../) для удаления формы [XFA](../xfa/) в случаях, когда форма [XFA](../xfa/) присутствует и [NeedsRendering](../) равно false. |
| [get_IgnoreNeedsRendering](./get_ignoreneedsrendering/)() const | Если это свойство истинно, значение ключа NeedsRendering будет игнорироваться при конвертации формы [XFA](../xfa/) в стандартную форму. По умолчанию — false. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если объект потокобезопасен. |
| [get_NeedsRendering](./get_needsrendering/)() | Получает значение, указывающее, требует ли документ удаления динамической формы [XFA](../xfa/). Это свойство было введено для определения, следует ли использовать [IgnoreNeedsRendering](../) для удаления формы [XFA](../xfa/) в случаях, когда форма [XFA](../xfa/) присутствует и [NeedsRendering](../) равно false. |
| [get_RemovePermission](./get_removepermission/)() const | Если это свойство истинно, словарь "Perms" будет удалён из PDF‑документа после конвертации динамических документов в стандартные. Словарь "Perms" может содержать правила, мешающие отображению выбора обязательных полей в Adobe Acrobat Reader. По умолчанию — false. |
| [get_SignaturesAppendOnly](./get_signaturesappendonly/)() | Если установлено, документ содержит подписи, которые могут быть аннулированы, если файл сохраняется (записывается) способом, изменяющим его прежнее содержимое, в отличие от инкрементного обновления. |
| [get_SignaturesExist](./get_signaturesexist/)() | Если установлено, документ содержит как минимум одно поле подписи. |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект синхронизации. |
| [get_Type](./get_type/)() | Получает тип формы. Возможные значения: Standard, Static, Dynamic. |
| [get_XFA](./get_xfa/)() const | Получает данные [XFA](../xfa/) формы (если присутствуют). |
| [GetEnumerator](./getenumerator/)() override | Получает перечисление полей формы. |
| [GetFieldsInRect](./getfieldsinrect/)(const System::SharedPtr\<Rectangle\>\&) | Возвращает поля внутри указанного прямоугольника. |
| [HasField](./hasfield/)(const System::SharedPtr\<Field\>\&) | Проверьте, есть ли у формы указанное поле. |
| [HasField](./hasfield/)(const System::String\&) | Определяет, было ли поле с указанным именем уже добавлено в [Form](./). |
| [HasField](./hasfield/)(const System::String\&, bool) | Определяет, было ли поле с указанным именем уже добавлено в [Form](./), с возможностью просматривать иерархию дочерних полей. |
| [idx_get](./idx_get/)(const System::String\&) | Получает поле формы по имени поля. Выбрасывает исключение, если поле не найдено. |
| [idx_get](./idx_get/)(int32_t) | Получает поле формы по индексу поля. |
| [MakeFormAnnotationsIndependent](./makeformannotationsindependent/)(const System::SharedPtr\<Page\>\&) | Делает аннотации полей формы независимыми. |
| [RemoveFieldAppearance](./removefieldappearance/)(const System::SharedPtr\<Field\>\&, int32_t) | Удаляет внешний вид поля по указанному индексу. Если остаётся только один дочерний внешний вид, метод встраивает его в поле. |
| [set_AutoRecalculate](./set_autorecalculate/)(bool) | Если установлено, все поля формы будут пересчитываться при изменении любого поля. Значение по умолчанию — true. Установите false, чтобы повысить производительность при заполнении формы большим количеством вычисляемых полей. |
| [set_AutoRestoreForm](./set_autorestoreform/)(bool) | Если установлено, отсутствующие поля формы будут автоматически созданы, если они присутствуют в аннотациях. |
| [set_CalculatedFields](./set_calculatedfields/)(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<Field\>\>\>\&) | Позволяет задать порядок вычисления полей. |
| [set_DefaultAppearance](./set_defaultappearance/)(const System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>\&) | Устанавливает внешний вид формы по умолчанию (объект, описывающий шрифт, размер текста и цвет полей формы по умолчанию). |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | Если это свойство истинно, то для контейнеров обязательных элементов Xfa exclGroup будут нарисованы дополнительные красные ограничивающие прямоугольники. Это свойство было введено из‑за отсутствия аналогов exclGroup при конвертации представления Xfa форм в стандарт. По умолчанию — false. |
| [set_IgnoreNeedsRendering](./set_ignoreneedsrendering/)(bool) | Если это свойство истинно, значение ключа NeedsRendering будет игнорироваться при конвертации формы [XFA](../xfa/) в стандартную форму. По умолчанию — false. |
| [set_RemovePermission](./set_removepermission/)(bool) | Если это свойство истинно, словарь "Perms" будет удалён из PDF‑документа после конвертации динамических документов в стандартные. Словарь "Perms" может содержать правила, мешающие отображению выбора обязательных полей в Adobe Acrobat Reader. По умолчанию — false. |
| [set_SignaturesAppendOnly](./set_signaturesappendonly/)(bool) | Если установлено, документ содержит подписи, которые могут быть аннулированы, если файл сохраняется (записывается) способом, изменяющим его прежнее содержимое, в отличие от инкрементного обновления. |
| [set_SignaturesExist](./set_signaturesexist/)(bool) | Если установлено, документ содержит как минимум одно поле подписи. |
| [set_Type](./set_type/)(FormType) | Получает тип формы. Возможные значения: Standard, Static, Dynamic. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
