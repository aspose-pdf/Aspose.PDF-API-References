---
title: Aspose::Pdf::Facades::FormEditor::CopyInnerField method
linktitle: CopyInnerField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormEditor::CopyInnerField method. Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.facades/formeditor/copyinnerfield/
---
## FormEditor::CopyInnerField(System::String, System::String, int32_t) method


Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(System::String fieldName, System::String newFieldName, int32_t pageNum)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The old fully qualified field name. |
| newFieldName | System::String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int32_t | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |

## See Also

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyInnerField(System::String, System::String, int32_t, float, float) method


Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field.

```cpp
void Aspose::Pdf::Facades::FormEditor::CopyInnerField(System::String fieldName, System::String newFieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The old fully qualified field name. |
| newFieldName | System::String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int32_t | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | float | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | float | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

## See Also

* Class [String](../../../system/string/)
* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
