---
title: System::Xml::XmlElement::HasAttribute method
linktitle: HasAttribute
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlElement::HasAttribute method. Determines whether the current node has an attribute with the specified local name and namespace URI in C++.'
type: docs
weight: 1600
url: /cpp/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String, String) method


Determines whether the current node has an attribute with the specified local name and namespace URI.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the attribute to find. |
| namespaceURI | String | The namespace URI of the attribute to find. |

### ReturnValue

**true** if the current node has the specified attribute; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlElement::HasAttribute(String) method


Determines whether the current node has an attribute with the specified name.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the attribute to find. This is a qualified name. It is matched against the **get_Name** value of the matching node. |

### ReturnValue

**true** if the current node has the specified attribute; otherwise, **false**.

## See Also

* Class [String](../../../system/string/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
