---
title: "System::Xml::Xsl::XsltContext::ResolveVariable method"
linktitle: "ResolveVariable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XsltContext::ResolveVariable method. Cuando se sobrescribe en una clase derivada, resuelve una referencia de variable y devuelve un IXsltContextVariable que representa la variable en C++."
type: docs
weight: 500
url: /es/cpp/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable method


Cuando se sobrescribe en una clase derivada, resuelve una referencia de variable y devuelve un [IXsltContextVariable](../../ixsltcontextvariable/) que representa la variable.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | String | El prefijo de la variable tal como aparece en la expresión [XPath](../../../system.xml.xpath/). |
| nombre | String | El nombre de la variable. |

### ReturnValue

Un [IXsltContextVariable](../../ixsltcontextvariable/) que representa la variable en tiempo de ejecución.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXsltContextVariable](../../ixsltcontextvariable/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
