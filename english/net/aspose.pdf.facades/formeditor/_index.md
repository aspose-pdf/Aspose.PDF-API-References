---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.FormEditor class. Class for editing forms ading/deleting field etc
type: docs
weight: 4320
url: /net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Class for editing forms (ading/deleting field etc)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Constructor for FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Initializes new `FormEditor` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Sets options for combo box with export values. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Sets visual attributes of the field. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Sets items which will be added t onewly created list box or combo box. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Gets or sets size of radio button item size (when new radio button field is added). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | The member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | The flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Set the submit button's submission flags |

## Methods

| Name | Description |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Add field of specified type to the form. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Add field of specified type to the form. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Add JavaScript for a PushButton field. If old event exists, new event is added after it. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Adds new item to the list box. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Add a new item with Export value to the existing list box field, only for AcroForm combo box field. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Add submit button on the form. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Closes the facade. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Changes visual attributes of all fields in the PDF document. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Changes visual attributes of all fields with the specified field type. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Changes visual attributes of the specified field. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Delete item from the list field. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Get field flags. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Set new position of field. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Remove field from the form. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Remove submit action of the field. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Change name of the field. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Reset all visual attribtues to empty value. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Reset all visual attribtues of inner facade to empty value. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Saves the PDF document to the specified stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Saves the PDF document to the specified file. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Set the alignment style of a text field. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Set the vertical alignment style of a text field. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Set field flags |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Set attributes of field. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Sets maximum character count of the text field. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Set submit flag of submit button. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Sets URL of the button. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Change a single-lined text field to a multiple-lined one. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


