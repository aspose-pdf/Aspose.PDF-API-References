---
title: System::Xml::XmlNode::SelectNodes method
linktitle: SelectNodes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNode::SelectNodes method. Selects a list of nodes matching the XPath expression in C++.'
type: docs
weight: 3800
url: /cpp/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method


Selects a list of nodes matching the [XPath](../../../system.xml.xpath/) expression.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const String\& | The [XPath](../../../system.xml.xpath/) expression. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a collection of nodes matching the [XPath](../../../system.xml.xpath/) query.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Selects a list of nodes matching the [XPath](../../../system.xml.xpath/) expression. Any prefixes found in the [XPath](../../../system.xml.xpath/) expression are resolved using the supplied [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const String\& | The [XPath](../../../system.xml.xpath/) expression. |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | An [XmlNamespaceManager](../../xmlnamespacemanager/) to use for resolving namespaces for prefixes in the [XPath](../../../system.xml.xpath/) expression. |

### ReturnValue

An [XmlNodeList](../../xmlnodelist/) containing a collection of nodes matching the [XPath](../../../system.xml.xpath/) query.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
