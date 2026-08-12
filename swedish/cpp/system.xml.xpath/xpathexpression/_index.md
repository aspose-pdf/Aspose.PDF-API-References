---
title: "System::Xml::XPath::XPathExpression class"
linktitle: "XPathExpression"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathExpression class. Tillhandahåller en typad klass som representerar ett kompilerat XPath-uttryck i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml.xpath/xpathexpression/
---
## XPathExpression class


Tillhandahåller en typad klass som representerar ett kompilerat [XPath](../) uttryck.

```cpp
class XPathExpression : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) | När den åsidosätts i en avledd klass sorteras noderna som valts av [XPath](../) uttrycket enligt det specificerade IComparer-objektet. |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) | När den åsidosätts i en avledd klass sorteras noderna som valts av [XPath](../) uttrycket enligt de angivna parametrarna. |
| virtual [Clone](./clone/)() | När den åsidosätts i en avledd klass returneras en klon av detta [XPathExpression](./). |
| static [Compile](./compile/)(const String\&) | Kompilerar det specificerade [XPath](../) uttrycket och returnerar ett [XPathExpression](./) objekt som representerar [XPath](../) uttrycket. |
| static [Compile](./compile/)(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) | Kompilerar det specificerade [XPath](../) uttrycket, med det specificerade [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) objektet för namnrymdslösning, och returnerar ett [XPathExpression](./) objekt som representerar [XPath](../) uttrycket. |
| virtual [get_Expression](./get_expression/)() | När den åsidosätts i en avledd klass får den en **string** representation av [XPathExpression](./). |
| virtual [get_ReturnType](./get_returntype/)() | När den åsidosätts i en avledd klass får den resultattypen för [XPath](../) uttrycket. |
| virtual [SetContext](./setcontext/)(SharedPtr\<XmlNamespaceManager\>) | När den åsidosätts i en avledd klass specificerar den [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) objektet att använda för namnrymdslösning. |
| virtual [SetContext](./setcontext/)(SharedPtr\<IXmlNamespaceResolver\>) | När den åsidosätts i en avledd klass specificerar den [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) objektet att använda för namnrymdslösning. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
