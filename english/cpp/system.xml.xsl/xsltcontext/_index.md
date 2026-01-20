---
title: System::Xml::Xsl::XsltContext class
linktitle: XsltContext
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltContext class. Encapsulates the current execution context of the Extensible Stylesheet Language for Transformations (XSLT) processor allowing XML Path Language (XPath) to resolve functions, parameters, and namespaces within XPath expressions in C++.'
type: docs
weight: 500
url: /cpp/system.xml.xsl/xsltcontext/
---
## XsltContext class


Encapsulates the current execution context of the Extensible Stylesheet Language for Transformations (XSLT) processor allowing XML Path Language ([XPath](../../system.xml.xpath/)) to resolve functions, parameters, and namespaces within [XPath](../../system.xml.xpath/) expressions.

```cpp
class XsltContext : public System::Xml::XmlNamespaceManager
```

## Methods

| Method | Description |
| --- | --- |
| virtual [CompareDocument](./comparedocument/)(String, String) | When overridden in a derived class, compares the base Uniform Resource Identifiers (URIs) of two documents based upon the order the documents were loaded by the XSLT processor (that is, the [XslTransform](../xsltransform/) class). |
| virtual [get_Whitespace](./get_whitespace/)() | When overridden in a derived class, gets a value indicating whether to include white space nodes in the output. |
| virtual [PreserveWhitespace](./preservewhitespace/)(SharedPtr\<System::Xml::XPath::XPathNavigator\>) | When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context. |
| virtual [ResolveFunction](./resolvefunction/)(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) | When overridden in a derived class, resolves a function reference and returns an [IXsltContextFunction](../ixsltcontextfunction/) representing the function. The [IXsltContextFunction](../ixsltcontextfunction/) is used at execution time to get the return value of the function. |
| virtual [ResolveVariable](./resolvevariable/)(String, String) | When overridden in a derived class, resolves a variable reference and returns an [IXsltContextVariable](../ixsltcontextvariable/) representing the variable. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
