---
title: System::Xml::Xsl::IXsltContextVariable class
linktitle: IXsltContextVariable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::IXsltContextVariable class. Provides an interface to a given variable that is defined in the style sheet during runtime execution in C++.'
type: docs
weight: 200
url: /cpp/system.xml.xsl/ixsltcontextvariable/
---
## IXsltContextVariable class


Provides an interface to a given variable that is defined in the style sheet during runtime execution.

```cpp
class IXsltContextVariable : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XsltContext\>) | Evaluates the variable at runtime and returns an object that represents the value of the variable. |
| virtual [get_IsLocal](./get_islocal/)() | Returns a value indicating whether the variable is local. |
| virtual [get_IsParam](./get_isparam/)() | Returns a value indicating whether the variable is an Extensible Stylesheet Language Transformations (XSLT) parameter. This can be a parameter to a style sheet or a template. |
| virtual [get_VariableType](./get_variabletype/)() | Returns the XPathResultType representing the XML Path Language ([XPath](../../system.xml.xpath/)) type of the variable. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
