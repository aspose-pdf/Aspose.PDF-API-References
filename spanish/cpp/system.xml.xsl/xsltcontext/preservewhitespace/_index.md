---
title: "System::Xml::Xsl::XsltContext::PreserveWhitespace method"
linktitle: "PreserveWhitespace"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XsltContext::PreserveWhitespace method. Cuando se sobrescribe en una clase derivada, evalúa si se deben conservar los nodos de espacio en blanco o eliminarlos para el contexto dado en C++."
type: docs
weight: 300
url: /es/cpp/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace method


Cuando se sobrescribe en una clase derivada, evalúa si se deben conservar los nodos de espacio en blanco o eliminarlos para el contexto dado.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | SharedPtr\<System::Xml::XPath::XPathNavigator\> | El nodo de espacio en blanco que debe conservarse o eliminarse en el contexto actual. |

### ReturnValue

**true** if the white space is to be preserved; **false** if the white space is to be stripped.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
