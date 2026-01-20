---
title: Aspose::Pdf::CollectionItem::TryGetTextValue method
linktitle: TryGetTextValue
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionItem::TryGetTextValue method. Tries to get the text value with the specified name from the collection item in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/collectionitem/trygettextvalue/
---
## CollectionItem::TryGetTextValue method


Tries to get the text value with the specified name from the collection item.

```cpp
bool Aspose::Pdf::CollectionItem::TryGetTextValue(System::String name, System::SharedPtr<CollectionItem::Value<System::String>> &value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | System::String | The name of the text value. |
| value | System::SharedPtr\<CollectionItem::Value\<System::String\>\>\& | When this method returns, contains the text value associated with the specified name, if the name is found; otherwise, null. |

### ReturnValue

true if the text value with the specified name is found; otherwise, false.

## See Also

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Value](../value/)
* Class [CollectionItem](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
