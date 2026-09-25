---
title: "FormEditor Class"
linktitle: "FormEditor"
articleTitle: "FormEditor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.FormEditor class. Class for editing forms (ading/deleting field etc)"
type: docs
weight: 220
url: "/net/aspose.pdf.facades/formeditor/"
keywords: "FormEditor, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FormEditor class

Class for editing forms (ading/deleting field etc)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [FormEditor](./formeditor/#constructor) | Constructor for FormEditor. |
| [FormEditor](./formeditor/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`FormEditor`](../../aspose.pdf.lowcode/formeditor/) object on base of the *document*. |
| [FormEditor](./formeditor/#constructor_2)(*Stream, Stream*) | Constructor for FormEditor. |
| [FormEditor](./formeditor/#constructor_3)(*string, string*) | Constructor for FormEditor. |
| [FormEditor](./formeditor/#constructor_4)(*[Document](../../aspose.pdf/document/), string*) | Initializes new [`FormEditor`](../../aspose.pdf.lowcode/formeditor/) object on base of the *document*. |
| [FormEditor](./formeditor/#constructor_5)(*[Document](../../aspose.pdf/document/), Stream*) | Initializes new [`FormEditor`](../../aspose.pdf.lowcode/formeditor/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertTo](./convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. |
| [DestFileName](./destfilename/) { get; set; } | Gets or sets destination file name. |
| [DestStream](./deststream/) { get; set; } | Gets or sets destination stream. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [ExportItems](./exportitems/) { get; set; } | Sets options for combo box with export values. |
| [Facade](./facade/) { get; set; } | Sets visual attributes of the field. |
| [Items](./items/) { get; set; } | Sets items which will be added t onewly created list box or combo box. |
| [RadioButtonItemSize](./radiobuttonitemsize/) { get; set; } | Gets or sets size of radio button item size (when new radio button field is added). |
| [RadioGap](./radiogap/) { get; set; } | The member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [RadioHoriz](./radiohoriz/) { get; set; } | The flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [SrcFileName](./srcfilename/) { get; set; } | Gets or sets name of source file. |
| [SrcStream](./srcstream/) { get; set; } | Gets or sets source stream. |
| [SubmitFlag](./submitflag/) { get; set; } | Set the submit button's submission flags. |

## Methods

| Name | Description |
| --- | --- |
| [AddField](./addfield/)(*FieldType, string, int, float, float, float, float*) | Add field of specified type to the form. |
| [AddField](./addfield/)(*FieldType, string, string, int, float, float, float, float*) | Add field of specified type to the form. |
| [AddFieldScript](./addfieldscript/)(*string, string*) | Add JavaScript for a PushButton field. If old event exists, new event is added after it. |
| [AddListItem](./addlistitem/)(*string, string*) | Adds new item to the list box. |
| [AddListItem](./addlistitem/)(*string, string[]*) | Add a new item with Export value to the existing list box field, only for AcroForm combo box field. |
| [AddSubmitBtn](./addsubmitbtn/)(*string, int, string, string, float, float, float, float*) | Add submit button on the form. |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string*) | Initializes the facade. *(Inherited from Facade)* |
| [Close](./close/) | Closes the facade. |
| [CopyInnerField](./copyinnerfield/)(*string, string, int*) | Copies an existing field to the same position in specified page number. |
| [CopyInnerField](./copyinnerfield/)(*string, string, int, float, float*) | Copies an existing field to a new position specified by both page number and ordinates. |
| [CopyOuterField](./copyouterfield/)(*string, string*) | Copies an existing field from one PDF document to another document with original page number and ordinates. |
| [CopyOuterField](./copyouterfield/)(*string, string, int*) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. |
| [CopyOuterField](./copyouterfield/)(*string, string, int, float, float*) | Copies an existing field from one PDF document to another document with specified page number and ordinates. |
| [DecorateField](./decoratefield/) | Changes visual attributes of all fields in the PDF document. |
| [DecorateField](./decoratefield/)(*string*) | Changes visual attributes of the specified field. |
| [DecorateField](./decoratefield/)(*FieldType*) | Changes visual attributes of all fields with the specified field type. |
| [DelListItem](./dellistitem/)(*string, string*) | Delete item from the list field. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [GetFieldAppearance](./getfieldappearance/)(*string*) | Get field flags. |
| [MoveField](./movefield/)(*string, float, float, float, float*) | Set new position of field. |
| [RemoveField](./removefield/)(*string*) | Remove field from the form. |
| [RemoveFieldAction](./removefieldaction/)(*string*) | Remove submit action of the field. |
| [RenameField](./renamefield/)(*string, string*) | Change name of the field. |
| [ResetFacade](./resetfacade/) | Reset all visual attribtues to empty value. |
| [ResetInnerFacade](./resetinnerfacade/) | Reset all visual attribtues of inner facade to empty value. |
| [Save](./save/) | Saves changes into destination file. |
| [Save](../../aspose.pdf.facades/saveablefacade/save/)(*string*) | Saves the PDF document to the specified file. *(Inherited from SaveableFacade)* |
| [SetFieldAlignment](./setfieldalignment/)(*string, int*) | Set the alignment style of a text field. |
| [SetFieldAlignmentV](./setfieldalignmentv/)(*string, int*) | Set the vertical alignment style of a text field. |
| [SetFieldAppearance](./setfieldappearance/)(*string, AnnotationFlags*) | Set field flags. |
| [SetFieldAttribute](./setfieldattribute/)(*string, PropertyFlag*) | Set attributes of field. |
| [SetFieldCombNumber](./setfieldcombnumber/)(*string, int*) | Sets number of combs for a regular single-line text field (the field is. |
| [SetFieldLimit](./setfieldlimit/)(*string, int*) | Sets maximum character count of the text field. |
| [SetFieldScript](./setfieldscript/)(*string, string*) | Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one. |
| [SetSubmitFlag](./setsubmitflag/)(*string, SubmitFormFlag*) | Set submit flag of submit button. |
| [SetSubmitUrl](./setsubmiturl/)(*string, string*) | Sets URL of the button. |
| [Single2Multiple](./single2multiple/)(*string*) | Change a single-lined text field to a multiple-lined one. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

