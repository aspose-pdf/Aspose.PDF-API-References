---
title: System::Xml::Xsl::IXsltContextFunction::Invoke method
linktitle: Invoke
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::IXsltContextFunction::Invoke method. Provides the method to invoke the function with the given arguments in the given context in C++.'
type: docs
weight: 500
url: /cpp/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke method


Provides the method to invoke the function with the given arguments in the given context.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| xsltContext | SharedPtr\<XsltContext\> | The XSLT context for the function call. |
| args | ArrayPtr\<SharedPtr\<Object\>\> | The arguments of the function call. Each argument is an element in the array. |
| docContext | SharedPtr\<System::Xml::XPath::XPathNavigator\> | The context node for the function call. |

### ReturnValue

An [Object](../../../system/object/) representing the return value of the function.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
