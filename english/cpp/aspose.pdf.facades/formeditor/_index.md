---
title: Aspose::Pdf::Facades::FormEditor class
linktitle: FormEditor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormEditor class. Class for editing forms (ading/deleting field etc) in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.facades/formeditor/
---
## FormEditor class


Class for editing forms (ading/deleting field etc)

```cpp
class FormEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [AddField](./addfield/)(FieldType, const System::String\&, int32_t, float, float, float, float) | Add field of specified type to the form. |
| [AddField](./addfield/)(FieldType, const System::String\&, const System::String\&, int32_t, float, float, float, float) | Add field of specified type to the form. |
| [AddFieldScript](./addfieldscript/)(const System::String\&, const System::String\&) | Add JavaScript for a PushButton field. If old event exists, new event is added after it. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::String\&) | Adds new item to the list box. |
| [AddListItem](./addlistitem/)(const System::String\&, const System::ArrayPtr\<System::String\>\&) | Add a new item with Export value to the existing list box field, only for AcroForm combo box field. |
| [AddSubmitBtn](./addsubmitbtn/)(const System::String\&, int32_t, const System::String\&, const System::String\&, float, float, float, float) | Add submit button on the form. |
| [Close](./close/)() override | Closes the facade. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t) | Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field. |
| [CopyInnerField](./copyinnerfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field. |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&) | Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [CopyOuterField](./copyouterfield/)(const System::String\&, const System::String\&, int32_t, float, float) | Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box). |
| [DecorateField](./decoratefield/)(const System::String\&) | Changes visual attributes of the specified field. |
| [DecorateField](./decoratefield/)(FieldType) | Changes visual attributes of all fields with the specified field type. |
| [DecorateField](./decoratefield/)() | Changes visual attributes of all fields in the PDF document. |
| [DelListItem](./dellistitem/)(const System::String\&, const System::String\&) | Delete item from the list field. |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Constructor for [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::String\&, const System::String\&) | Constructor for [FormEditor](./). |
| [FormEditor](./formeditor/)() | Constructor for [FormEditor](./). |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initializes new [FormEditor](./) object on base of the *document* . |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Initializes new [FormEditor](./) object on base of the *document* . |
| [FormEditor](./formeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Initializes new [FormEditor](./) object on base of the *document* . |
| [FormEditor](./formeditor/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Creates [FormEditor](./) which will save result into HttpResponse object. |
| [FormEditor](./formeditor/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Creates [FormEditor](./) which will save result into HttpResponse object. |
| [get_AttachmentName](./get_attachmentname/)() const | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [get_DestFileName](./get_destfilename/)() const | Gets destination file name. |
| [get_DestStream](./get_deststream/)() const | Gets destination stream. |
| [get_ExportItems](./get_exportitems/)() const | Sets options for combo box with export values. |
| [get_Facade](./get_facade/)() const | Sets visual attributes of the field. |
| [get_Items](./get_items/)() const | Sets items which will be added t onewly created list box or combo box. |
| [get_RadioButtonItemSize](./get_radiobuttonitemsize/)() const | Gets size of radio button item size (when new radio button field is added). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField([FieldType.Radio](../fieldtype/), "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [get_RadioGap](./get_radiogap/)() | The member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [get_RadioHoriz](./get_radiohoriz/)() const | The flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [get_Response](./get_response/)() const | Gets Response object where result of operation will be stored. |
| [get_SaveOptions](./get_saveoptions/)() const | Gets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Gets name of source file. |
| [get_SrcStream](./get_srcstream/)() const | Gets source stream. |
| [get_SubmitFlag](./get_submitflag/)() const | Set the submit button's submission flags. |
| [GetFieldAppearance](./getfieldappearance/)(const System::String\&) | Get field flags. |
| [MoveField](./movefield/)(const System::String\&, float, float, float, float) | Set new position of field. |
| [RemoveField](./removefield/)(const System::String\&) | Remove field from the form. |
| [RemoveFieldAction](./removefieldaction/)(const System::String\&) | Remove submit action of the field. |
| [RenameField](./renamefield/)(const System::String\&, const System::String\&) | Change name of the field. |
| [ResetFacade](./resetfacade/)() | Reset all visual attribtues to empty value. |
| [ResetInnerFacade](./resetinnerfacade/)() | Reset all visual attribtues of inner facade to empty value. |
| [Save](./save/)() | Saves changes into destination file. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [set_DestFileName](./set_destfilename/)(const System::String\&) | Sets destination file name. |
| [set_DestStream](./set_deststream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sets destination stream. |
| [set_ExportItems](./set_exportitems/)(const System::ArrayPtr\<System::ArrayPtr\<System::String\>\>\&) | Sets options for combo box with export values. |
| [set_Facade](./set_facade/)(const System::SharedPtr\<FormFieldFacade\>\&) | Sets visual attributes of the field. |
| [set_Items](./set_items/)(const System::ArrayPtr\<System::String\>\&) | Sets items which will be added t onewly created list box or combo box. |
| [set_RadioButtonItemSize](./set_radiobuttonitemsize/)(double) | Sets size of radio button item size (when new radio button field is added). ** formEditor = new [Aspose.Pdf.Facades.FormEditor](./)("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.RadioGap = 4; formEditor.RadioHoriz = false; formEditor.RadioButtonItemSize = 20; formEditor.Items = new string[] { "First", "Second", "Third" }; formEditor.AddField([FieldType.Radio](../fieldtype/), "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.Save(); ** |
| [set_RadioGap](./set_radiogap/)(float) | The member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [set_RadioHoriz](./set_radiohoriz/)(bool) | The flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Sets Response object where result of operation will be stored. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Sets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(const System::String\&) | Sets name of source file. |
| [set_SrcStream](./set_srcstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Sets source stream. |
| [set_SubmitFlag](./set_submitflag/)(SubmitFormFlag) | Set the submit button's submission flags. |
| [SetFieldAlignment](./setfieldalignment/)(const System::String\&, int32_t) | Set the alignment style of a text field. |
| [SetFieldAlignmentV](./setfieldalignmentv/)(const System::String\&, int32_t) | Set the vertical alignment style of a text field. |
| [SetFieldAppearance](./setfieldappearance/)(const System::String\&, Annotations::AnnotationFlags) | Set field flags. |
| [SetFieldAttribute](./setfieldattribute/)(const System::String\&, PropertyFlag) | Set attributes of field. |
| [SetFieldCombNumber](./setfieldcombnumber/)(const System::String\&, int32_t) | Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter). |
| [SetFieldLimit](./setfieldlimit/)(const System::String\&, int32_t) | Sets maximum character count of the text field. |
| [SetFieldScript](./setfieldscript/)(const System::String\&, const System::String\&) | Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one. |
| [SetSubmitFlag](./setsubmitflag/)(const System::String\&, SubmitFormFlag) | Set submit flag of submit button. |
| [SetSubmitUrl](./setsubmiturl/)(const System::String\&, const System::String\&) | Sets URL of the button. |
| [Single2Multiple](./single2multiple/)(const System::String\&) | Change a single-lined text field to a multiple-lined one. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
