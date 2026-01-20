---
title: System::Xml::Xsl::XsltContext::PreserveWhitespace method
linktitle: PreserveWhitespace
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::Xsl::XsltContext::PreserveWhitespace method. When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context in C++.'
type: docs
weight: 300
url: /cpp/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace method


When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| node | SharedPtr\<System::Xml::XPath::XPathNavigator\> | The white space node that is to be preserved or stripped in the current context. |

### ReturnValue

**true** if the white space is to be preserved; **false** if the white space is to be stripped.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
