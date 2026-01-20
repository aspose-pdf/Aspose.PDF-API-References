---
title: Aspose::Pdf::Metadata::Contains method
linktitle: Contains
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Metadata::Contains method. Checks does specified key-value pair is contained in the dictionary in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/metadata/contains/
---
## Metadata::Contains(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) const method


Checks does specified key-value pair is contained in the dictionary.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\& | Key-value pair. |

### ReturnValue

true if this pauir was found.

## See Also

* Class [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Contains(const System::String\&) const method


Checks does key is contained in metadata.

```cpp
bool Aspose::Pdf::Metadata::Contains(const System::String &key) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | The key of entry to find. |

### ReturnValue

True if key is contained in the metadata.

## See Also

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
