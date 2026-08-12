---
title: "System::Xml::Xsl::XsltContext::ResolveVariable‑metod"
linktitle: "ResolveVariable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltContext::ResolveVariable‑metod. När den åsidosätts i en avledd klass löser den en variabelreferens och returnerar ett IXsltContextVariable som representerar variabeln i C++."
type: docs
weight: 500
url: /sv/cpp/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable method


När den åsidosätts i en avledd klass löser den en variabelreferens och returnerar ett [IXsltContextVariable](../../ixsltcontextvariable/) som representerar variabeln.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | String | Prefixet för variabeln som det visas i [XPath](../../../system.xml.xpath/)-uttrycket. |
| namn | String | Namnet på variabeln. |

### ReturnValue

Ett [IXsltContextVariable](../../ixsltcontextvariable/) som representerar variabeln vid körning.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextVariable](../../ixsltcontextvariable/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
