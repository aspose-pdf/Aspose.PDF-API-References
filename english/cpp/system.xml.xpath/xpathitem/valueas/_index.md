---
title: System::Xml::XPath::XPathItem::ValueAs method
linktitle: ValueAs
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathItem::ValueAs method. Returns the item''s value as the specified type in C++.'
type: docs
weight: 1100
url: /cpp/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) method


Returns the item's value as the specified type.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const TypeInfo\& | The type to return the item value as. |

### ReturnValue

The value of the item as the type requested.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


When overridden in a derived class, returns the item's value as the type specified using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| returnType | const TypeInfo\& | The type to return the item's value as. |
| nsResolver | SharedPtr\<IXmlNamespaceResolver\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### ReturnValue

The value of the item as the type requested.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathItem](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
