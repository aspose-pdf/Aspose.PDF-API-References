---
title: System::Xml::XmlElement::RemoveAttributeAt method
linktitle: RemoveAttributeAt
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement::RemoveAttributeAt method. Removes the attribute node with the specified index from the element. (If the removed attribute has a default value, it is immediately replaced) in C++.'
type: docs
weight: 2000
url: /cpp/system.xml/xmlelement/removeattributeat/
---
## XmlElement::RemoveAttributeAt method


Removes the attribute node with the specified index from the element. (If the removed attribute has a default value, it is immediately replaced).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlElement::RemoveAttributeAt(int32_t i)
```


| Parameter | Type | Description |
| --- | --- | --- |
| i | int32_t | The index of the node to remove. The first node has index 0. |

### ReturnValue

The attribute node removed or **nullptr** if there is no node at the given index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
