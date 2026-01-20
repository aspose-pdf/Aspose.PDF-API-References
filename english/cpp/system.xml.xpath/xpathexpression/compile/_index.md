---
title: System::Xml::XPath::XPathExpression::Compile method
linktitle: Compile
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathExpression::Compile method. Compiles the XPath expression specified and returns an XPathExpression object representing the XPath expression in C++.'
type: docs
weight: 600
url: /cpp/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method


Compiles the [XPath](../../) expression specified and returns an [XPathExpression](../) object representing the [XPath](../../) expression.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const String\& | An [XPath](../../) expression. |

### ReturnValue

An [XPathExpression](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method


Compiles the specified [XPath](../../) expression, with the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified for namespace resolution, and returns an [XPathExpression](../) object that represents the [XPath](../../) expression.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const String\& | An [XPath](../../) expression. |
| nsResolver | const SharedPtr\<IXmlNamespaceResolver\>\& | An object that implements the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) interface for namespace resolution. |

### ReturnValue

An [XPathExpression](../) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
