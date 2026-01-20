---
title: System::Xml::XmlElement::SetAttributeNode method
linktitle: SetAttributeNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement::SetAttributeNode method. Adds the specified XmlAttribute in C++.'
type: docs
weight: 2700
url: /cpp/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) method


Adds the specified [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newAttr | SharedPtr\<XmlAttribute\> | The [XmlAttribute](../../xmlattribute/) node to add to the attribute collection for this element. |

### ReturnValue

If the attribute replaces an existing attribute with the same name, the old [XmlAttribute](../../xmlattribute/) is returned; otherwise, **nullptr** is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::SetAttributeNode(String, String) method


Adds the specified [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute. |
| namespaceURI | String | The namespace URI of the attribute. |

### ReturnValue

The [XmlAttribute](../../xmlattribute/) to add.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
