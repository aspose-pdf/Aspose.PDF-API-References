---
title: System::Xml::Xsl::IXsltContextFunction class
linktitle: IXsltContextFunction
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::IXsltContextFunction class. Provides an interface to a given function defined in the Extensible Stylesheet Language for Transformations (XSLT) style sheet during runtime execution in C++.'
type: docs
weight: 100
url: /cpp/system.xml.xsl/ixsltcontextfunction/
---
## IXsltContextFunction class


Provides an interface to a given function defined in the Extensible Stylesheet Language for Transformations (XSLT) style sheet during runtime execution.

```cpp
class IXsltContextFunction : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [get_ArgTypes](./get_argtypes/)() | Returns the supplied XML Path Language ([XPath](../../system.xml.xpath/)) types for the function's argument list. This information can be used to discover the signature of the function which allows you to differentiate between overloaded functions. |
| virtual [get_Maxargs](./get_maxargs/)() | Returns the maximum number of arguments for the function. This enables the user to differentiate between overloaded functions. |
| virtual [get_Minargs](./get_minargs/)() | Returns the minimum number of arguments for the function. This enables the user to differentiate between overloaded functions. |
| virtual [get_ReturnType](./get_returntype/)() | Returns the XPathResultType representing the [XPath](../../system.xml.xpath/) type returned by the function. |
| virtual [Invoke](./invoke/)(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) | Provides the method to invoke the function with the given arguments in the given context. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
