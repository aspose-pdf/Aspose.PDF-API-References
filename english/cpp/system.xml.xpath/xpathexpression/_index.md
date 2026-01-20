---
title: System::Xml::XPath::XPathExpression class
linktitle: XPathExpression
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::XPath::XPathExpression class. Provides a typed class that represents a compiled XPath expression in C++.'
type: docs
weight: 300
url: /cpp/system.xml.xpath/xpathexpression/
---
## XPathExpression class


Provides a typed class that represents a compiled [XPath](../) expression.

```cpp
class XPathExpression : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) | When overridden in a derived class, sorts the nodes selected by the [XPath](../) expression according to the specified IComparer object. |
| virtual [AddSort](./addsort/)(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) | When overridden in a derived class, sorts the nodes selected by the [XPath](../) expression according to the supplied parameters. |
| virtual [Clone](./clone/)() | When overridden in a derived class, returns a clone of this [XPathExpression](./). |
| static [Compile](./compile/)(const String\&) | Compiles the [XPath](../) expression specified and returns an [XPathExpression](./) object representing the [XPath](../) expression. |
| static [Compile](./compile/)(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) | Compiles the specified [XPath](../) expression, with the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified for namespace resolution, and returns an [XPathExpression](./) object that represents the [XPath](../) expression. |
| virtual [get_Expression](./get_expression/)() | When overridden in a derived class, gets a **string** representation of the [XPathExpression](./). |
| virtual [get_ReturnType](./get_returntype/)() | When overridden in a derived class, gets the result type of the [XPath](../) expression. |
| virtual [SetContext](./setcontext/)(SharedPtr\<XmlNamespaceManager\>) | When overridden in a derived class, specifies the [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) object to use for namespace resolution. |
| virtual [SetContext](./setcontext/)(SharedPtr\<IXmlNamespaceResolver\>) | When overridden in a derived class, specifies the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object to use for namespace resolution. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
