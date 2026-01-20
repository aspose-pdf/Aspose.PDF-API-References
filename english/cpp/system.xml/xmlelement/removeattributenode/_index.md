---
title: System::Xml::XmlElement::RemoveAttributeNode method
linktitle: RemoveAttributeNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement::RemoveAttributeNode method. Removes the specified XmlAttribute in C++.'
type: docs
weight: 2100
url: /cpp/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) method


Removes the specified [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| oldAttr | SharedPtr\<XmlAttribute\> | The [XmlAttribute](../../xmlattribute/) node to remove. If the removed attribute has a default value, it is immediately replaced. |

### ReturnValue

The removed [XmlAttribute](../../xmlattribute/) or **nullptr** if **oldAttr** is not an attribute node of the [XmlElement](../).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::RemoveAttributeNode(String, String) method


Removes the [XmlAttribute](../../xmlattribute/) specified by the local name and namespace URI. (If the removed attribute has a default value, it is immediately replaced).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

The removed [XmlAttribute](../../xmlattribute/) or **nullptr** if the [XmlElement](../) does not have a matching attribute node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
