---
title: "System::Xml::Xsl::XsltContext::CompareDocument method"
linktitle: "CompareDocument"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Xml::Xsl::XsltContext::CompareDocument method. Cuando se sobrescribe en una clase derivada, compara los Identificadores Uniformes de Recursos (URI) base de dos documentos según el orden en que los documentos fueron cargados por el procesador XSLT (es decir, la clase XslTransform) en C++."
type: docs
weight: 100
url: /es/cpp/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument method


Cuando se sobrescribe en una clase derivada, compara los Identificadores Uniformes de Recursos (URI) base de dos documentos según el orden en que los documentos fueron cargados por el procesador XSLT (es decir, la clase [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseUri | String | El URI base del primer documento a comparar. |
| nextbaseUri | String | El URI base del segundo documento a comparar. |

### ReturnValue

Un valor entero que describe el orden relativo de los dos URI base: -1 si **baseUri** ocurre antes que **nextbaseUri**; 0 si los dos URI base son idénticos; y 1 si **baseUri** ocurre después de **nextbaseUri**.

## Ver también

* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
