---
title: Form
second_title: Aspose.PDF for .NET API Reference
description: Class representing form object.
type: docs
weight: 3060
url: /net/aspose.pdf.forms/form/
---
## Form class

Class representing form object.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Properties

| Name | Description |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | If set, absent form fields will be automatically created if they present in annotations. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Allows to set order of field calculation. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Gets number of the fields on this form. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Gets or sets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Gets default resources placed on this form. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogues for the exclGroup during conversion Xfa representation of forms to standard. It is false by default. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | Gets list of all fields in lowest level of hierarhical form. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Returns true if object is thread-safe. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Gets field of the form by field name. Throws excpetion if the field was not found. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | If set, the document contains at least one signature field. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Returns synchronization object. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Gets type of the form. Possible values are: Standard, Static, Dynamic. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Gets XFA data of the form (if presents). |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Adds field on the form. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Adds field on the form. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Adds new field to the form; If this field is already placed on other or this form, the copy of field is created. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Adds additional appearance of the field to specified page of the document in the specified location. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Sets XFA of the form to specified value. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Copies fields placed on the form into array. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Delete field from the form. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Deletes field from the form by its name. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Removes all form fields and place their values directly on the page. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Gets enumeration of form fields. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Returns fields inside of specified rectangle. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Check if the form already has specified field. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Determines if the field with specified name already added to the Form. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_2)(string, bool) | Determines if the field with specified name already added to the Form, with ability to look into children hierarchy of fields. |

## Fields

| Name | Description |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned. |

## Other Members

| Name | Description |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Class which describes settings for Form flattening procedure. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | Forms can contain signing information and can be signed or unsigned. Sometimes view of forms in viewer must depend on whether form is signed or not. This enum enumerates possible rendering modes during convertion of form type in regard to sign. |

### See Also

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
