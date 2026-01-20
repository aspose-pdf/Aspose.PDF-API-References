---
title: System::Xml::Xsl::XsltContext::ResolveVariable method
linktitle: ResolveVariable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltContext::ResolveVariable method. When overridden in a derived class, resolves a variable reference and returns an IXsltContextVariable representing the variable in C++.'
type: docs
weight: 500
url: /cpp/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable method


When overridden in a derived class, resolves a variable reference and returns an [IXsltContextVariable](../../ixsltcontextvariable/) representing the variable.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| prefix | String | The prefix of the variable as it appears in the [XPath](../../../system.xml.xpath/) expression. |
| name | String | The name of the variable. |

### ReturnValue

An [IXsltContextVariable](../../ixsltcontextvariable/) representing the variable at runtime.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextVariable](../../ixsltcontextvariable/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
