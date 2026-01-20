---
title: System::Xml::XPath::XPathNavigator::ValueAs method
linktitle: ValueAs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::ValueAs method. Returns the current node''s value as the Type specified, using the IXmlNamespaceResolver object specified to resolve namespace prefixes in C++.'
type: docs
weight: 8100
url: /cpp/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs method


Returns the current node's value as the Type specified, using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const TypeInfo\& | The Type to return the current node's value as. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### ReturnValue

The value of the current node as the Type requested.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
