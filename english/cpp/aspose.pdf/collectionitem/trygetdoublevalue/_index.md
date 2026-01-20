---
title: Aspose::Pdf::CollectionItem::TryGetDoubleValue method
linktitle: TryGetDoubleValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionItem::TryGetDoubleValue method. Tries to get the double value for the specified name from the collection item in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf/collectionitem/trygetdoublevalue/
---
## CollectionItem::TryGetDoubleValue method


Tries to get the double value for the specified name from the collection item.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetDoubleValue(System::String name, System::SharedPtr<CollectionItem::Value<double>> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | System::String | The name of the value to retrieve. |
| value | System::SharedPtr\<CollectionItem::Value\<double\>\>\& | When this method returns, contains the double value associated with the specified name, if the name is found; otherwise, null. This parameter is passed uninitialized. |

### ReturnValue

true if the value is successfully retrieved; otherwise, false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
