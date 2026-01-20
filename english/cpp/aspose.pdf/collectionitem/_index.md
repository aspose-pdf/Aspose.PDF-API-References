---
title: Aspose::Pdf::CollectionItem class
linktitle: CollectionItem
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::CollectionItem class. Represents a collection item class. The collection item contains the data described by the collection schema in C++.'
type: docs
weight: 2500
url: /cpp/aspose.pdf/collectionitem/
---
## CollectionItem class


Represents a collection item class. The collection item contains the data described by the collection schema.

```cpp
class CollectionItem : public System::Object
```

## Nested classes

* Class [Value](./value/)
## Methods

| Method | Description |
| --- | --- |
| [get_AllNames](./get_allnames/)() | Gets a collection of all the names of collection item values. |
| [get_IsEmpty](./get_isempty/)() | Gets a value indicating whether the collection item is empty. |
| [HasName](./hasname/)(System::String) | Checks if the given name exists in the collection item. |
| [TryGetDateTimeValue](./trygetdatetimevalue/)(System::String, System::SharedPtr\<CollectionItem::Value\<System::DateTime\>\>\&) | Tries to get the value of type DateTime from the collection item by the specified name. |
| [TryGetDoubleValue](./trygetdoublevalue/)(System::String, System::SharedPtr\<CollectionItem::Value\<double\>\>\&) | Tries to get the double value for the specified name from the collection item. |
| [TryGetIntValue](./trygetintvalue/)(System::String, System::SharedPtr\<CollectionItem::Value\<int32_t\>\>\&) | Tries to get the integer value for a specified name from the collection item. |
| [TryGetTextValue](./trygettextvalue/)(System::String, System::SharedPtr\<CollectionItem::Value\<System::String\>\>\&) | Tries to get the text value with the specified name from the collection item. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
