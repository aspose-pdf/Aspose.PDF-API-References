---
title: System::Xml::XPath::XPathNavigator::Evaluate method
linktitle: Evaluate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathNavigator::Evaluate method. Evaluates the XPathExpression and returns the typed result in C++.'
type: docs
weight: 1200
url: /cpp/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) method


Evaluates the [XPathExpression](../../xpathexpression/) and returns the typed result.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```


| Parameter | Type | Description |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | An [XPathExpression](../../xpathexpression/) that can be evaluated. |

### ReturnValue

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) method


Uses the supplied context to evaluate the [XPathExpression](../../xpathexpression/), and returns the typed result.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```


| Parameter | Type | Description |
| --- | --- | --- |
| expr | SharedPtr\<XPathExpression\> | An [XPathExpression](../../xpathexpression/) that can be evaluated. |
| context | SharedPtr\<XPathNodeIterator\> | An [XPathNodeIterator](../../xpathnodeiterator/) that points to the selected node set that the evaluation is to be performed on. |

### ReturnValue

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(String) method


Evaluates the specified [XPath](../../) expression and returns the typed result.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | String | A string representing an [XPath](../../) expression that can be evaluated. |

### ReturnValue

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) method


Evaluates the specified [XPath](../../) expression and returns the typed result, using the [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes in the [XPath](../../) expression.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


| Parameter | Type | Description |
| --- | --- | --- |
| xpath | String | A string representing an [XPath](../../) expression that can be evaluated. |
| resolver | SharedPtr\<IXmlNamespaceResolver\> | The [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) object used to resolve namespace prefixes in the [XPath](../../) expression. |

### ReturnValue

The result of the expression ([Boolean](../../../system/boolean/), number, string, or node set). This maps to [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), or [XPathNodeIterator](../../xpathnodeiterator/) objects respectively.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
