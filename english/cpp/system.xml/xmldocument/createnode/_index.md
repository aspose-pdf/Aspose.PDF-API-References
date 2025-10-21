---
title: System::Xml::XmlDocument::CreateNode method
linktitle: CreateNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlDocument::CreateNode method. Creates an XmlNode with the specified node type, XmlDocument::get_Name, and XmlNode::get_NamespaceURI in C++.'
type: docs
weight: 1100
url: /cpp/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method


Creates an [XmlNode](../../xmlnode/) with the specified node type, [XmlDocument::get_Name](../get_name/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const String\& | [String](../../../system/string/) version of the [XmlNodeType](../../xmlnodetype/) of the new node. This parameter must be one of the values listed in the table below. |
| name | const String\& | The qualified name of the new node. If the name contains a colon, it is parsed into [XmlNode::get_Prefix](../../xmlnode/get_prefix/) and [XmlDocument::get_LocalName](../get_localname/) components. |
| namespaceURI | const String\& | The namespace URI of the new node. |

### ReturnValue

The new [XmlNode](../../xmlnode/).
## Remarks



The **nodeTypeString** parameter is case sensitive and must be one of the values in the following table: |||
|-|-|
|nodeTypeString|XmlNodeType|
|attribute|Attribute|
|cdatasection|CDATA |
|comment|Comment |
|document|Document |
|documentfragment|DocumentFragment |
|documenttype|DocumentType |
|element|Element |
|entityreference|EntityReference |
|processinginstruction|ProcessingInstruction |
|significantwhitespace|SignificantWhitespace |
|text|Text|
|whitespace|Whitespace |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) method


Creates an [XmlNode](../../xmlnode/) with the specified [XmlNodeType](../../xmlnodetype/), [XmlDocument::get_Name](../get_name/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XmlNodeType | The [XmlNodeType](../../xmlnodetype/) of the new node. |
| name | const String\& | The qualified name of the new node. If the name contains a colon then it is parsed into [XmlNode::get_Prefix](../../xmlnode/get_prefix/) and [XmlDocument::get_LocalName](../get_localname/) components. |
| namespaceURI | const String\& | The namespace URI of the new node. |

### ReturnValue

The new [XmlNode](../../xmlnode/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method


Creates a [XmlNode](../../xmlnode/) with the specified [XmlNodeType](../../xmlnodetype/), [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/), and [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | XmlNodeType | The [XmlNodeType](../../xmlnodetype/) of the new node. |
| prefix | const String\& | The prefix of the new node. |
| name | const String\& | The local name of the new node. |
| namespaceURI | const String\& | The namespace URI of the new node. |

### ReturnValue

The new [XmlNode](../../xmlnode/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
