---
title: System::Xml::XmlNamedNodeMap::GetNamedItem method
linktitle: GetNamedItem
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamedNodeMap::GetNamedItem method. Retrieves a node with the matching XmlNode::get_LocalName and XmlNode::get_NamespaceURI values in C++.'
type: docs
weight: 700
url: /cpp/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String, String) method


Retrieves a node with the matching [XmlNode::get_LocalName](../../xmlnode/get_localname/) and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) values.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| localName | String | The local name of the node to retrieve. |
| namespaceURI | String | The namespace Uniform Resource Identifier (URI) of the node to retrieve. |

### ReturnValue

An [XmlNode](../../xmlnode/) with the matching local name and namespace URI or **nullptr** if a matching node was not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNamedNodeMap::GetNamedItem(String) method


Retrieves an [XmlNode](../../xmlnode/) specified by name.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The qualified name of the node to retrieve. It is matched against the [XmlNode::get_Name](../../xmlnode/get_name/) value of the matching node. |

### ReturnValue

An [XmlNode](../../xmlnode/) with the specified name or **nullptr** if a matching node is not found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
