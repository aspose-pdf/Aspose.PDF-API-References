---
title: Aspose::Pdf::Forms::Form class
linktitle: Form
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Form class. Class representing form object in C++.'
type: docs
weight: 1100
url: /cpp/aspose.pdf.forms/form/
---
## Form class


Class representing form object.

```cpp
class Form : public System::Collections::Generic::ICollection<System::SharedPtr<Annotations::WidgetAnnotation>>
```

## Nested classes

* Class [FlattenSettings](./flattensettings/)
## Enums

| Enum | Description |
| --- | --- |
| [SignDependentElementsRenderingModes](./signdependentelementsrenderingmodes/) | [Forms](../) can contain signing information and can be signed or unsigned. Sometimes view of forms in viewer must depend on whether form is signed or not. This enum enumerates possible rendering modes during convertion of form type in regard to sign. |
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Field\>, int32_t) | Adds field on the form. |
| [Add](./add/)(const System::SharedPtr\<Field\>\&) | Adds field on the form. |
| [Add](./add/)(System::SharedPtr\<Field\>, System::String, int32_t) | Adds new field to the form; If this field is already placed on other or this form, the copy of field is created. |
| [AddFieldAppearance](./addfieldappearance/)(System::SharedPtr\<Field\>, int32_t, System::SharedPtr\<Rectangle\>) | Adds additional appearance of the field to specified page of the document in the specified location. |
| [AssignXfa](./assignxfa/)(System::SharedPtr\<System::Xml::XmlDocument\>) | Sets [XFA](../xfa/) of the form to specified value. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Field\>\>, int32_t) | Copies fields placed on the form into array. |
| [Delete](./delete/)(System::SharedPtr\<Field\>) | Delete field from the form. |
| [Delete](./delete/)(System::String) | Deletes field from the form by its name. |
| [Flatten](./flatten/)() | Removes all form fields and place their values directly on the page. |
| [get_AutoRecalculate](./get_autorecalculate/)() const | If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields. |
| [get_AutoRestoreForm](./get_autorestoreform/)() const | If set, absent form fields will be automatically created if they present in annotations. |
| [get_Count](./get_count/)() const override | Gets number of the fields on this form. |
| [get_DefaultAppearance](./get_defaultappearance/)() | Gets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [get_DefaultResources](./get_defaultresources/)() | Gets default resources placed on this form. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogues for the exclGroup during conversion Xfa representation of forms to standard. It is false by default. |
| [get_Fields](./get_fields/)() | Gets list of all fields in lowest level of hierarhical form. |
| [get_HasXfa](./get_hasxfa/)() | Gets a value indicating whether the document contains [XFA](../xfa/) form. This property was introduced to determine if [IgnoreNeedsRendering](../) should be used to remove the [XFA](../xfa/) form in cases where the [XFA](../xfa/) form is present and [NeedsRendering](../) is false. |
| [get_IgnoreNeedsRendering](./get_ignoreneedsrendering/)() const | If this property is true the value of NeedsRendering key will be ignored during conversion [XFA](../xfa/) form to Standard form. It is false by default. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true if object is thread-safe. |
| [get_NeedsRendering](./get_needsrendering/)() | Gets a value indicating whether the document requires the removal of the dynamic [XFA](../xfa/) form. This property was introduced to determine if [IgnoreNeedsRendering](../) should be used to remove the [XFA](../xfa/) form in cases where the [XFA](../xfa/) form is present and [NeedsRendering](../) is false. |
| [get_RemovePermission](./get_removepermission/)() const | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default. |
| [get_SignaturesAppendOnly](./get_signaturesappendonly/)() | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [get_SignaturesExist](./get_signaturesexist/)() | If set, the document contains at least one signature field. |
| [get_SyncRoot](./get_syncroot/)() const | Returns synchronization object. |
| [get_Type](./get_type/)() | Gets type of the form. Possible values are: Standard, Static, Dynamic. |
| [get_XFA](./get_xfa/)() const | Gets [XFA](../xfa/) data of the form (if presents). |
| [GetEnumerator](./getenumerator/)() override | Gets enumeration of form fields. |
| [GetFieldsInRect](./getfieldsinrect/)(System::SharedPtr\<Rectangle\>) | Returns fields inside of specified rectangle. |
| [HasField](./hasfield/)(System::SharedPtr\<Field\>) | Check if the form already has specified field. |
| [HasField](./hasfield/)(System::String) | Determines if the field with specified name already added to the [Form](./). |
| [HasField](./hasfield/)(System::String, bool) | Determines if the field with specified name already added to the [Form](./), with ability to look into children hierarchy of fields. |
| [idx_get](./idx_get/)(System::String) | Gets field of the form by field name. Throws excpetion if the field was not found. |
| [idx_get](./idx_get/)(int32_t) | Gets field of the form by field index. |
| [MakeFormAnnotationsIndependent](./makeformannotationsindependent/)(System::SharedPtr\<Page\>) | Makes form fields annotations independent. |
| [RemoveFieldAppearance](./removefieldappearance/)(System::SharedPtr\<Field\>, int32_t) | Removes appearance of the field at specified index. If only one child appearance left, method embeds it into the field. |
| [set_AutoRecalculate](./set_autorecalculate/)(bool) | If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields. |
| [set_AutoRestoreForm](./set_autorestoreform/)(bool) | If set, absent form fields will be automatically created if they present in annotations. |
| [set_CalculatedFields](./set_calculatedfields/)(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<Field\>\>\>) | Allows to set order of field calculation. |
| [set_DefaultAppearance](./set_defaultappearance/)(System::SharedPtr\<Aspose::Pdf::Annotations::DefaultAppearance\>) | Sets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogues for the exclGroup during conversion Xfa representation of forms to standard. It is false by default. |
| [set_IgnoreNeedsRendering](./set_ignoreneedsrendering/)(bool) | If this property is true the value of NeedsRendering key will be ignored during conversion [XFA](../xfa/) form to Standard form. It is false by default. |
| [set_RemovePermission](./set_removepermission/)(bool) | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default. |
| [set_SignaturesAppendOnly](./set_signaturesappendonly/)(bool) | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [set_SignaturesExist](./set_signaturesexist/)(bool) | If set, the document contains at least one signature field. |
| [set_Type](./set_type/)(FormType) | Gets type of the form. Possible values are: Standard, Static, Dynamic. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
