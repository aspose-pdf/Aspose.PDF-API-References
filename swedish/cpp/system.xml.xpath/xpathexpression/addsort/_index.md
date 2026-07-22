---
title: "System::Xml::XPath::XPathExpression::AddSort metod"
linktitle: "AddSort"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathExpression::AddSort metod. När den åsidosätts i en avledd klass sorterar den noderna som valts av XPath‑uttrycket enligt det specificerade IComparer‑objektet i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) method


När den åsidosätts i en avledd klass sorterar den noderna som valts av [XPath](../../)-uttrycket enligt det specificerade IComparer‑objektet.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | SharedPtr\<Object\> | Ett objekt som representerar sorteringsnyckeln. Detta kan vara **string**‑värdet för noden eller ett [XPathExpression](../)-objekt med ett kompilerat [XPath](../../)-uttryck. |
| jämförare | SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\> | Ett IComparer‑objekt som tillhandahåller specifika datatypjämförelser för att jämföra två objekt för ekvivalens. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) method


När den åsidosätts i en avledd klass sorterar den noderna som valts av [XPath](../../)-uttrycket enligt de medföljande parametrarna.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expr | SharedPtr\<Object\> | Ett objekt som representerar sorteringsnyckeln. Detta kan vara **string**‑värdet för noden eller ett [XPathExpression](../)-objekt med ett kompilerat [XPath](../../)-uttryck. |
| order | XmlSortOrder | Ett [XmlSortOrder](../../xmlsortorder/) värde som anger sorteringsordningen. |
| caseOrder | XmlCaseOrder | Ett [XmlCaseOrder](../../xmlcaseorder/) värde som anger hur man sorterar versaler och gemener. |
| lang | String | Språket som ska användas för jämförelse. Använder klassen [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) som kan skickas till metoden [String::Compare](../../../system/string/compare/) för språktyper, till exempel "us-en" för amerikansk engelska. Om en tom sträng anges används systemmiljön för att bestämma [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | XmlDataType | Ett [XmlDataType](../../xmldatatype/) värde som anger sorteringsordningen för datatypen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Class [String](../../../system/string/)
* Enum [XmlDataType](../../xmldatatype/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.PDF for C++](../../../)
