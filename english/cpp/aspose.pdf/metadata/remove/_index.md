---
title: Aspose::Pdf::Metadata::Remove method
linktitle: Remove
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Metadata::Remove method. Removes key/value pair from the colleciton in C++.'
type: docs
weight: 2100
url: /cpp/aspose.pdf/metadata/remove/
---
## Metadata::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XmpValue\>\>\&) method


Removes key/value pair from the colleciton.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<XmpValue>> &item) override
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
* Class [XmpValue](../../xmpvalue/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## Metadata::Remove(const System::String\&) method


Removes entry from metadata.

```cpp
bool Aspose::Pdf::Metadata::Remove(const System::String &key) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | The key of entry to remove. |

### ReturnValue

True - if key removed; otherwise, false.

## See Also

* Class [String](../../../system/string/)
* Class [Metadata](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
