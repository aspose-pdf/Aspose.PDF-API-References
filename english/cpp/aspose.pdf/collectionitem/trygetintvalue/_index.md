---
title: Aspose::Pdf::CollectionItem::TryGetIntValue method
linktitle: TryGetIntValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionItem::TryGetIntValue method. Tries to get the integer value for a specified name from the collection item in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/collectionitem/trygetintvalue/
---
## CollectionItem::TryGetIntValue method


Tries to get the integer value for a specified name from the collection item.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetIntValue(System::String name, System::SharedPtr<CollectionItem::Value<int32_t>> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | System::String | The name of the value to retrieve. |
| value | System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\& | When this method returns, contains the value associated with the specified name, if the name is found; otherwise, null. |

### ReturnValue

true if the value associated with the specified name is found; otherwise, false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
