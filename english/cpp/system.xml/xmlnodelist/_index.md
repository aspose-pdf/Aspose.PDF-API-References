---
title: System::Xml::XmlNodeList class
linktitle: XmlNodeList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNodeList class. Represents an ordered collection of nodes in C++.'
type: docs
weight: 2700
url: /cpp/system.xml/xmlnodelist/
---
## XmlNodeList class


Represents an ordered collection of nodes.

```cpp
class XmlNodeList : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>,
                    public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_Count](./get_count/)() | Returns the number of nodes in the [XmlNodeList](./). |
| virtual [GetEnumerator](./getenumerator/)() | Provides support for iteration over the collection of nodes in the [XmlNodeList](./). |
| virtual [idx_get](./idx_get/)(int32_t) | Returns a node at the given index. |
| virtual [Item](./item/)(int32_t) | Retrieves a node at the given index. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
