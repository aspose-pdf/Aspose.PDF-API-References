---
title: System::Xml::XmlNamedNodeMap::RemoveNamedItem method
linktitle: RemoveNamedItem
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamedNodeMap::RemoveNamedItem method. Removes a node with the matching XmlNode::get_LocalName and XmlNode::get_NamespaceURI values in C++.'
type: docs
weight: 900
url: /cpp/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String, String) method


Removes a node with the matching [XmlNode::get_LocalName](../../xmlnode/get_localname/) and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the node to remove. |
| namespaceURI | String | The namespace URI of the node to remove. |

### ReturnValue

The [XmlNode](../../xmlnode/) removed or **nullptr** if a matching node was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNamedNodeMap::RemoveNamedItem(String) method


Removes the node from the [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the node to remove. The name is matched against the [XmlNode::get_Name](../../xmlnode/get_name/) value of the matching node. |

### ReturnValue

The [XmlNode](../../xmlnode/) removed from this [XmlNamedNodeMap](../) or **nullptr** if a matching node was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
