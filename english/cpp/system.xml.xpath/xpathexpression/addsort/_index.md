---
title: System::Xml::XPath::XPathExpression::AddSort method
linktitle: AddSort
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathExpression::AddSort method. When overridden in a derived class, sorts the nodes selected by the XPath expression according to the specified IComparer object in C++.'
type: docs
weight: 100
url: /cpp/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) method


When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the specified IComparer object.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| expr | SharedPtr\<Object\> | An object representing the sort key. This can be the **string** value of the node or an [XPathExpression](../) object with a compiled [XPath](../../) expression. |
| comparer | SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\> | An IComparer object that provides the specific data type comparisons for comparing two objects for equivalence. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) method


When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the supplied parameters.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| expr | SharedPtr\<Object\> | An object representing the sort key. This can be the **string** value of the node or an [XPathExpression](../) object with a compiled [XPath](../../) expression. |
| order | XmlSortOrder | An [XmlSortOrder](../../xmlsortorder/) value indicating the sort order. |
| caseOrder | XmlCaseOrder | An [XmlCaseOrder](../../xmlcaseorder/) value indicating how to sort uppercase and lowercase letters. |
| lang | String | The language to use for comparison. Uses the [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) class that can be passed to the [String::Compare](../../../system/string/compare/) method for the language types, for example, "us-en" for U.S. English. If an empty string is specified, the system environment is used to determine the [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | XmlDataType | An [XmlDataType](../../xmldatatype/) value indicating the sort order for the data type. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Class [String](../../../system/string/)
* Enum [XmlDataType](../../xmldatatype/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
