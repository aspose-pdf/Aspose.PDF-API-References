---
title: System::Xml::XmlNode::SelectSingleNode method
linktitle: SelectSingleNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNode::SelectSingleNode method. Selects the first XmlNode that matches the XPath expression in C++.'
type: docs
weight: 3900
url: /cpp/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) method


Selects the first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) expression.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const String\& | The [XPath](../../../system.xml.xpath/) expression. |

### ReturnValue

The first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) query or **nullptr** if no matching node is found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Selects the first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) expression. Any prefixes found in the [XPath](../../../system.xml.xpath/) expression are resolved using the supplied [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const String\& | The [XPath](../../../system.xml.xpath/) expression. |
| nsmgr | const SharedPtr\<XmlNamespaceManager\>\& | An [XmlNamespaceManager](../../xmlnamespacemanager/) to use for resolving namespaces for prefixes in the [XPath](../../../system.xml.xpath/) expression. |

### ReturnValue

The first [XmlNode](../) that matches the [XPath](../../../system.xml.xpath/) query or **nullptr** if no matching node is found.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
