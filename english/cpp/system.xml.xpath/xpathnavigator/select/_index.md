---
title: System::Xml::XPath::XPathNavigator::Select method
linktitle: Select
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::Select method. Selects a node set using the specified XPathExpression in C++.'
type: docs
weight: 7100
url: /cpp/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(SharedPtr\<XPathExpression\>) method


Selects a node set using the specified [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | An [XPathExpression](../../xpathexpression/) object containing the compiled [XPath](../../) query. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that points to the selected node set.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String) method


Selects a node set, using the specified [XPath](../../) expression.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | String | A [String](../../../system/string/) representing an [XPath](../../) expression. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) pointing to the selected node set.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) method


Selects a node set using the specified [XPath](../../) expression with the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | String | A [String](../../../system/string/) representing an [XPath](../../) expression. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes. |

### ReturnValue

An [XPathNodeIterator](../../xpathnodeiterator/) that points to the selected node set.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
