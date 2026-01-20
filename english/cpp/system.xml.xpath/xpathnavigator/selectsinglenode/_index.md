---
title: System::Xml::XPath::XPathNavigator::SelectSingleNode method
linktitle: SelectSingleNode
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::SelectSingleNode method. Selects a single node in the XPathNavigator using the specified XPathExpression object in C++.'
type: docs
weight: 7500
url: /cpp/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) method


Selects a single node in the [XPathNavigator](../) using the specified [XPathExpression](../../xpathexpression/) object.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


| Parameter | Type | Description |
| --- | --- | --- |
| expression | SharedPtr\<XPathExpression\> | An [XPathExpression](../../xpathexpression/) object containing the compiled [XPath](../../) query. |

### ReturnValue

An [XPathNavigator](../) object that contains the first matching node for the [XPath](../../) query specified; otherwise **nullptr** if there are no query results.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String) method


Selects a single node in the [XPathNavigator](../) using the specified [XPath](../../) query.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | String | A [String](../../../system/string/) representing an [XPath](../../) expression. |

### ReturnValue

An [XPathNavigator](../) object that contains the first matching node for the [XPath](../../) query specified; otherwise, **nullptr** if there are no query results.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) method


Selects a single node in the [XPathNavigator](../) object using the specified [XPath](../../) query with the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | String | A [String](../../../system/string/) representing an [XPath](../../) expression. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes in the [XPath](../../) query. |

### ReturnValue

An [XPathNavigator](../) object that contains the first matching node for the [XPath](../../) query specified; otherwise **nullptr** if there are no query results.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
