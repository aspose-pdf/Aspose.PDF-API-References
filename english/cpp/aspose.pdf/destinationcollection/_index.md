---
title: Aspose::Pdf::DestinationCollection class
linktitle: DestinationCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DestinationCollection class. Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document in C++.'
type: docs
weight: 3700
url: /cpp/aspose.pdf/destinationcollection/
---
## DestinationCollection class


Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document.

```cpp
class DestinationCollection : public System::Collections::Generic::ICollection<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Object>>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Adds the specified item. [Collection](../collection/) is read-only. Always throws NotSupportedException exception. |
| [Clear](./clear/)() override | [Collection](../collection/) is read-only. Always throws NotSupportedException exception. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) const override | Determines whether this instance contains the object. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\>, int32_t) override | Copies the elements of the collection to an Array, starting at a particular Array index. |
| [get_Count](./get_count/)() const override | Gets the number of elements contained in the collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the collection is read-only. |
| [GetEnumerator](./getenumerator/)() override | Returns the enumerator. |
| [GetExplicitDestination](./getexplicitdestination/)(System::String, bool) | Returns the explicit destination by the name. |
| [GetPageNumber](./getpagenumber/)(System::String, bool) | Returns the page number of destination by the name. |
| [idx_get](./idx_get/)(int32_t) | Gets the destination object by index. |
| [IndexOf](./indexof/)(System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>) const | Returns the index of destination in collection. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<System::Object\>\>\&) override | Removes the specified item. [Collection](../collection/) is read-only. Always throws NotSupportedException exception. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
