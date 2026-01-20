---
title: Aspose::Pdf::Vector::GraphicElementCollection class
linktitle: GraphicElementCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Vector::GraphicElementCollection class. Represents GraphicElement collection in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.vector/graphicelementcollection/
---
## GraphicElementCollection class


Represents [GraphicElement](../graphicelement/) collection.

```cpp
class GraphicElementCollection : public System::Collections::Generic::ICollection<System::SharedPtr<GraphicElement>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<GraphicElement\>\&) override | Adds a new [GraphicElement](../graphicelement/) to the collection. All items in the collection must have the same [GraphicElement::Parent](../). |
| [Clear](./clear/)() override | Clears the collection. |
| [Contains](./contains/)(const System::SharedPtr\<GraphicElement\>\&) const override | Determines whether an element is in the collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<GraphicElement\>\>, int32_t) override | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array. |
| [get_Count](./get_count/)() const override | Gets the number of [GraphicElement](../graphicelement/) object elements actually contained in the collection. |
| [GetEnumerator](./getenumerator/)() override | Returns an enumerator for the entire collection. |
| [GraphicElementCollection](./graphicelementcollection/)() | Initializes the new collection. |
| [idx_get](./idx_get/)(int32_t) | Gets the [GraphicElement](../graphicelement/) element at the specified index. |
| [Remove](./remove/)(const System::SharedPtr\<GraphicElement\>\&) override | Deletes the [GraphicElement](../graphicelement/) element. |
| [ToString](./tostring/)() const override | Gets a string representation of this collection. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Vector](../)
* Library [Aspose.PDF for C++](../../)
