---
title: Aspose::Pdf::Facades::FormEditor::AddField method
linktitle: AddField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormEditor::AddField method. Add field of specified type to the form in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.facades/formeditor/addfield/
---
## FormEditor::AddField(FieldType, System::String, int32_t, float, float, float, float) method


Add field of specified type to the form.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, System::String fieldName, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Type of the field which must be added. |
| fieldName | System::String | Name of the field whic must be added. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) number where new field must be placed. |
| llx | float | Abscissa of the lower-left corner of the field. |
| lly | float | Ordinate of the lower-left corner of the field. |
| urx | float | Abscissa of the upper-right corner of the field. |
| ury | float | Ordinate of the upper-right corner of the field. |

### ReturnValue

true if field was successfully added.

## See Also

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::AddField(FieldType, System::String, System::String, int32_t, float, float, float, float) method


Add field of specified type to the form.

```cpp
bool Aspose::Pdf::Facades::FormEditor::AddField(FieldType fieldType, System::String fieldName, System::String initValue, int32_t pageNum, float llx, float lly, float urx, float ury)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Type of the field which must be added. |
| fieldName | System::String | Name of the field whic must be added. |
| initValue | System::String | Initial value of the field. |
| pageNum | int32_t | [Page](../../../aspose.pdf/page/) number where new field must be placed. |
| llx | float | Abscissa of the lower-left corner of the field. |
| lly | float | Ordinate of the lower-left corner of the field. |
| urx | float | Abscissa of the upper-right corner of the field. |
| ury | float | Ordinate of the upper-right corner of the field. |

### ReturnValue

true if field was successfully added.
## Remarks



/// 
## See Also

* Enum [FieldType](../../fieldtype/)
* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
