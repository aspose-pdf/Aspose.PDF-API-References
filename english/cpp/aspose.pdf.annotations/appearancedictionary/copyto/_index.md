---
title: Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo method. Copies the elements of the ICollection to an Array, starting at a particular Array index in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.annotations/appearancedictionary/copyto/
---
## AppearanceDictionary::CopyTo(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\>, int32_t) method


Copies the elements of the ICollection to an Array, starting at a particular Array index.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo(System::ArrayPtr<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XForm>>> array, int32_t arrayIndex) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\> | The one-dimensional Array that is the destination of the elements copied from ICollection. The Array must have zero-based indexing. |
| arrayIndex | int32_t | The zero-based index in array at which copying begins. |
## Remarks



No bounds checking is performed.
## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
## AppearanceDictionary::CopyTo(System::ArrayPtr\<System::SharedPtr\<XForm\>\>, int32_t) method


Copies the elements of the dictionary to an Array, starting at a particular Array index.

```cpp
void Aspose::Pdf::Annotations::AppearanceDictionary::CopyTo(System::ArrayPtr<System::SharedPtr<XForm>> array, int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | System::ArrayPtr\<System::SharedPtr\<XForm\>\> | Array where items must be copied. |
| index | int32_t | Index where items must be copied. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XForm](../../../aspose.pdf/xform/)
* Class [AppearanceDictionary](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
