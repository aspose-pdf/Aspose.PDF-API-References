---
title: Aspose::Pdf::Facades::PdfXmpMetadata::Remove method
linktitle: Remove
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfXmpMetadata::Remove method. Removes key/value pair from the collection in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf.facades/pdfxmpmetadata/remove/
---
## PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Removes key/value pair from the collection.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Key/value pair to be removed. |

### ReturnValue

true if pair was found and removed.

## See Also

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../../aspose.pdf/xmpvalue/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(const System::String\&) method


Removes key from the dictionary.

```cpp
bool Aspose::Pdf::Facades::PdfXmpMetadata::Remove(const System::String &key) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | Key which will be removed. |

### ReturnValue

True - if key removed; otherwise, false.


## See Also

* Class [String](../../../system/string/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfXmpMetadata::Remove(DefaultMetadataProperties) method


Removes element with specified key.

```cpp
void Aspose::Pdf::Facades::PdfXmpMetadata::Remove(DefaultMetadataProperties key)
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | Key of the element which will be deleted. |

## See Also

* Enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* Class [PdfXmpMetadata](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
