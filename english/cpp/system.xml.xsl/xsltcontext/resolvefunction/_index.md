---
title: System::Xml::Xsl::XsltContext::ResolveFunction method
linktitle: ResolveFunction
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltContext::ResolveFunction method. When overridden in a derived class, resolves a function reference and returns an IXsltContextFunction representing the function. The IXsltContextFunction is used at execution time to get the return value of the function in C++.'
type: docs
weight: 400
url: /cpp/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction method


When overridden in a derived class, resolves a function reference and returns an [IXsltContextFunction](../../ixsltcontextfunction/) representing the function. The [IXsltContextFunction](../../ixsltcontextfunction/) is used at execution time to get the return value of the function.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix of the function as it appears in the [XPath](../../../system.xml.xpath/) expression. |
| name | String | The name of the function. |
| ArgTypes | ArrayPtr\<System::Xml::XPath::XPathResultType\> | An array of argument types for the function being resolved. This allows you to select between methods with the same name (for example, overloaded methods). |

### ReturnValue

An [IXsltContextFunction](../../ixsltcontextfunction/) representing the function.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
