---
title: "System::Xml::Xsl::XsltContext::PreserveWhitespace‑metod"
linktitle: "PreserveWhitespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltContext::PreserveWhitespace‑metod. När den åsidosätts i en avledd klass utvärderar den om blankstegsnoder ska bevaras eller tas bort för den givna kontexten i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace method


När den åsidosätts i en avledd klass utvärderar den om blankstegsnoder ska bevaras eller tas bort för den givna kontexten.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | SharedPtr\<System::Xml::XPath::XPathNavigator\> | Den blankstegsnod som ska bevaras eller tas bort i den aktuella kontexten. |

### ReturnValue

**true** if the white space is to be preserved; **false** if the white space is to be stripped.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
