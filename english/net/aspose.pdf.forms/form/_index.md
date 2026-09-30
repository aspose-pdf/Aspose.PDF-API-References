---
title: "Form Class"
linktitle: "Form"
articleTitle: "Form"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Forms.Form class. Class representing form object."
type: docs
weight: 140
url: "/net/aspose.pdf.forms/form/"
keywords: "Form, Aspose.Pdf.Forms, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Form class

Class representing form object.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Properties

| Name | Description |
| --- | --- |
| [AutoRecalculate](./autorecalculate/) { get; set; } | If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields. |
| [AutoRestoreForm](./autorestoreform/) { get; set; } | If set, absent form fields will be automatically created if they present in annotations. |
| [CalculatedFields](./calculatedfields/) { set; } | Allows to set order of field calculation. |
| [Count](./count/) { get; } | Gets number of the fields on this form. |
| [DefaultAppearance](./defaultappearance/) { get; set; } | Gets or sets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [DefaultResources](./defaultresources/) { get; } | Gets default resources placed on this form. |
| [EmulateRequierdGroups](./emulaterequierdgroups/) { get; set; } | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogues for the exclGroup during conversion Xfa representation of forms to standard. It is false by default. |
| [Fields](./fields/) { get; } | Gets list of all fields in lowest level of hierarhical form. |
| [HasXfa](./hasxfa/) { get; } | Gets a value indicating whether the document contains XFA form. This property was introduced to determine if `IgnoreNeedsRendering` should be used to remove the XFA form in cases where the XFA form is present and `NeedsRendering` is false. |
| [IgnoreNeedsRendering](./ignoreneedsrendering/) { get; set; } | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default. |
| [IsSynchronized](./issynchronized/) { get; } | Returns true if object is thread-safe. |
| [Item](./item/) { get; } | Gets field of the form by field name. Throws excpetion if the field was not found. (2 indexers) |
| [NeedsRendering](./needsrendering/) { get; } | Gets a value indicating whether the document requires the removal of the dynamic XFA form. This property was introduced to determine if `IgnoreNeedsRendering` should be used to remove the XFA form in cases where the XFA form is present and `NeedsRendering` is false. |
| [RemovePermission](./removepermission/) { get; set; } | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default. |
| [SignaturesAppendOnly](./signaturesappendonly/) { get; set; } | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [SignaturesExist](./signaturesexist/) { get; set; } | If set, the document contains at least one signature field. |
| [SyncRoot](./syncroot/) { get; } | Returns synchronization object. |
| [Type](./type/) { get; set; } | Gets type of the form. Possible values are: Standard, Static, Dynamic. |
| [XFA](./xfa/) { get; } | Gets XFA data of the form (if presents). |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(Field) | Adds field on the form. |
| [Add](./add/)(Field, int) | Adds field on the form. |
| [Add](./add/)(Field, string, int) | Adds new field to the form; If this field is already placed on other or this form, the copy of field is created. |
| [AddFieldAppearance](./addfieldappearance/)(Field, int, Rectangle) | Adds additional appearance of the field to specified page of the document in the specified location. |
| [AssignXfa](./assignxfa/)(XmlDocument) | Sets XFA of the form to specified value. |
| [CopyTo](./copyto/)(Field[], int) | Copies fields placed on the form into array. |
| [Delete](./delete/)(Field) | Delete field from the form. |
| [Delete](./delete/)(string) | Deletes field from the form by its name. |
| [ExportToJson](./exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exports the PDF form fields to JSON format and writes the result to the provided stream. |
| [ExportToJson](./exporttojson/)(string, ExportFieldsToJsonOptions) | Exports the PDF form fields to JSON format and writes the result to the specified file. |
| [Flatten](./flatten/)() | Removes all form fields and place their values directly on the page. |
| [GetEnumerator](./getenumerator/)() | Gets enumeration of form fields. |
| [GetFieldsInRect](./getfieldsinrect/)(Rectangle) | Returns fields inside of specified rectangle. |
| [HasField](./hasfield/)(Field) | Check if the form already has specified field. |
| [HasField](./hasfield/)(string) | Determines if the field with specified name already added to the Form. |
| [HasField](./hasfield/)(string, bool) | Determines if the field with specified name already added to the Form, with ability to look into children hierarchy of fields. |
| [ImportFromJson](./importfromjson/)(Stream) | Imports the PDF form fields from JSON format provided in the stream. |
| [ImportFromJson](./importfromjson/)(string) | Imports the PDF form fields from JSON format provided in the specified file. |
| [MakeFormAnnotationsIndependent](./makeformannotationsindependent/)(Page) | Makes form fields annotations independent. |
| [RemoveFieldAppearance](./removefieldappearance/)(Field, int) | Removes appearance of the field at specified index. If only one child appearance left, method embeds it into the field. |

## Fields

| Name | Description |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](./signdependentelementsrenderingmodewhenconverted/) | Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned. |

## Other Members

| Name | Description |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Class which describes settings for Form flattening procedure. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Forms can contain signing information and can be signed or unsigned. Sometimes view of forms in viewer must depend on whether form is signed or not. This enum enumerates possible rendering modes during convertion of form type in regard to sign. |

### See Also

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)

