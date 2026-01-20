---
title: System::Xml::Xsl::IXsltContextVariable::Evaluate method
linktitle: Evaluate
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::IXsltContextVariable::Evaluate method. Evaluates the variable at runtime and returns an object that represents the value of the variable in C++.'
type: docs
weight: 100
url: /cpp/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate method


Evaluates the variable at runtime and returns an object that represents the value of the variable.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| xsltContext | SharedPtr\<XsltContext\> | An [XsltContext](../../xsltcontext/) representing the execution context of the variable. |

### ReturnValue

An [Object](../../../system/object/) representing the value of the variable. Possible return types include number, string, [Boolean](../../../system/boolean/), document fragment, or node set.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XsltContext](../../xsltcontext/)
* Class [IXsltContextVariable](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
