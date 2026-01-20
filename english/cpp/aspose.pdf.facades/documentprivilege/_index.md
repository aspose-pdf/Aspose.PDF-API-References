---
title: Aspose::Pdf::Facades::DocumentPrivilege class
linktitle: DocumentPrivilege
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::DocumentPrivilege class. Represents the privileges for accessing Pdf file. Refer toPdfFileSecurity. There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3 in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class


Represents the privileges for accessing [Pdf](../../aspose.pdf/) file. Refer to[PdfFileSecurity](../pdffilesecurity/). There are 4 ways using this class: 1.Using predefined privilege directly. 2.Based on a predefined privilege and change some specifical permissions. 3.Based on a predefined privilege and change some specifical Adobe Professional permissions combination. 4.Mixes the way2 and way3.

```cpp
class DocumentPrivilege : public System::IComparable<System::SharedPtr<System::Object>>
```

## Methods

| Method | Description |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<System::Object\>) override | Compares two [DocumentPrivilege](./) objects. |
| static [get_AllowAll](./get_allowall/)() | All allowed. |
| [get_AllowAssembly](./get_allowassembly/)() | Sets the permission which allow assembly or not. true is allow and false is forbidden. |
| [get_AllowCopy](./get_allowcopy/)() | Sets the permission which allow copy or not. true is allow and false is forbidden. |
| [get_AllowDegradedPrinting](./get_allowdegradedprinting/)() | Sets the permission which allow degraded printing or not. true is allow and false is forbidden. |
| [get_AllowFillIn](./get_allowfillin/)() | Sets the permission which allow fill in forms or not. true is allow and false is forbidden. |
| [get_AllowModifyAnnotations](./get_allowmodifyannotations/)() | Sets the permission which allow modify annotations or not. true is allow and false is forbidden. |
| [get_AllowModifyContents](./get_allowmodifycontents/)() | Sets the permission which allow modify contents or not. true is allow and false is forbidden. |
| [get_AllowPrint](./get_allowprint/)() | Sets the permission which allow print or not. true is allow and false is forbidden. |
| [get_AllowScreenReaders](./get_allowscreenreaders/)() | Sets the permission which allow screen readers or not. true is allow and false is forbidden. |
| static [get_Assembly](./get_assembly/)() | Allows assemblying file. |
| [get_ChangeAllowLevel](./get_changeallowlevel/)() | Gets and sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages. |
| static [get_Copy](./get_copy/)() | Allows copying file. |
| [get_CopyAllowLevel](./get_copyallowlevel/)() | Gets and sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content. |
| static [get_DegradedPrinting](./get_degradedprinting/)() | Allows degraded printing. |
| static [get_FillIn](./get_fillin/)() | Allows filling forms in file. |
| static [get_ForbidAll](./get_forbidall/)() | All Forbidded. |
| static [get_ModifyAnnotations](./get_modifyannotations/)() | Allows modifying annotations of file. |
| static [get_ModifyContents](./get_modifycontents/)() | Allows modifying file. |
| static [get_Print](./get_print/)() | Allows printing file. |
| [get_PrintAllowLevel](./get_printallowlevel/)() | Gets and sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution. |
| static [get_ScreenReaders](./get_screenreaders/)() | Allows to reader on screen only. |
| [set_AllowAssembly](./set_allowassembly/)(bool) | Sets the permission which allow assembly or not. true is allow and false is forbidden. |
| [set_AllowCopy](./set_allowcopy/)(bool) | Sets the permission which allow copy or not. true is allow and false is forbidden. |
| [set_AllowDegradedPrinting](./set_allowdegradedprinting/)(bool) | Sets the permission which allow degraded printing or not. true is allow and false is forbidden. |
| [set_AllowFillIn](./set_allowfillin/)(bool) | Sets the permission which allow fill in forms or not. true is allow and false is forbidden. |
| [set_AllowModifyAnnotations](./set_allowmodifyannotations/)(bool) | Sets the permission which allow modify annotations or not. true is allow and false is forbidden. |
| [set_AllowModifyContents](./set_allowmodifycontents/)(bool) | Sets the permission which allow modify contents or not. true is allow and false is forbidden. |
| [set_AllowPrint](./set_allowprint/)(bool) | Sets the permission which allow print or not. true is allow and false is forbidden. |
| [set_AllowScreenReaders](./set_allowscreenreaders/)(bool) | Sets the permission which allow screen readers or not. true is allow and false is forbidden. |
| [set_ChangeAllowLevel](./set_changeallowlevel/)(int32_t) | Gets and sets the change level of document's privilege. Just as the Adobe Professional's Changes Allowed settings. 0: None. 1: Inserting, Deleting and Rotating pages. 2: Filling in form fields and signing existing signature fields. 3: Commenting, filling in form fields, and signing existing signature fields. 4: Any except extracting pages. |
| [set_CopyAllowLevel](./set_copyallowlevel/)(int32_t) | Gets and sets the copy level of document's privilege. Just as the Adobe Professional's permission settings. 0: None. 1: Enable text access for screen reader devices for the visually impaired. 2: Enable copying of text, images and other content. |
| [set_PrintAllowLevel](./set_printallowlevel/)(int32_t) | Gets and sets the print level of document's privilege. Just as the Adobe Professional's Printing Allowed settings. 0: None. 1: Low Resolution (150 dpi). 2: High Resolution. |
## See Also

* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
