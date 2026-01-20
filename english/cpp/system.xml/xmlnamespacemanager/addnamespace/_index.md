---
title: System::Xml::XmlNamespaceManager::AddNamespace method
linktitle: AddNamespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XmlNamespaceManager::AddNamespace method. Adds the given namespace to the collection in C++.'
type: docs
weight: 200
url: /cpp/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace method


Adds the given namespace to the collection.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix to associate with the namespace being added. Use [String::Empty](../../../system/string/empty/) to add a default namespace. If the [XmlNamespaceManager](../) will be used for resolving namespaces in an XML Path Language ([XPath](../../../system.xml.xpath/)) expression, a prefix must be specified. If an [XPath](../../../system.xml.xpath/) expression does not include a prefix, it is assumed that the namespace Uniform Resource Identifier (URI) is the empty namespace. For more information about [XPath](../../../system.xml.xpath/) expressions and the [XmlNamespaceManager](../), refer to the XmlNode::SelectNodes(String) and XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) methods. |
| uri | String | The namespace to add. |

## See Also

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
