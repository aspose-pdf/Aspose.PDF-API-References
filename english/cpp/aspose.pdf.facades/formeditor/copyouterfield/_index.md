---
title: Aspose::Pdf::Facades::FormEditor::CopyOuterField method
linktitle: CopyOuterField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormEditor::CopyOuterField method. Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box) in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/formeditor/copyouterfield/
---
## FormEditor::CopyOuterField(System::String, System::String) method


Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(System::String srcFileName, System::String fieldName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | The name of PDF document which containes the field to be copied. |
| fieldName | System::String | The original fully qualified field name. |

## See Also

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(System::String, System::String, int32_t) method


Copies an existing field from one PDF document to another document with specified page number and original ordinates. Notice: Only for AcroForm fields (excluding radio box).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(System::String srcFileName, System::String fieldName, int32_t pageNum)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | The name of PDF document which containes the field to be copied. |
| fieldName | System::String | The original fully qualified field name. |
| pageNum | int32_t | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |

## See Also

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyOuterField(System::String, System::String, int32_t, float, float) method


Copies an existing field from one PDF document to another document with specified page number and ordinates. Notice: Only for AcroForm fields (excluding radio box).

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyOuterField(System::String srcFileName, System::String fieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | System::String | The name of PDF document which containes the field to be copied. |
| fieldName | System::String | The original fully qualified field name. |
| pageNum | int32_t | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | float | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | float | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

## See Also

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
