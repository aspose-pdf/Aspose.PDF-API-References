---
title: "System::Xml::Xsl::XsltContext::CompareDocument‑metod"
linktitle: "CompareDocument"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltContext::CompareDocument‑metod. När den åsidosätts i en avledd klass jämför den de grundläggande Uniform Resource Identifiers (URIs) för två dokument baserat på den ordning i vilken dokumenten laddades av XSLT‑processorn (det vill säga XslTransform‑klassen) i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument method


När den åsidosätts i en avledd klass jämför den de grundläggande Uniform Resource Identifiers (URIs) för två dokument baserat på den ordning i vilken dokumenten laddades av XSLT‑processorn (det vill säga [XslTransform](../../xsltransform/)‑klassen).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseUri | String | Den grund‑URI:n för det första dokumentet att jämföra. |
| nextbaseUri | String | Den grund‑URI:n för det andra dokumentet att jämföra. |

### ReturnValue

Ett heltalsvärde som beskriver den relativa ordningen för de två grund‑URI:erna: -1 om **baseUri** förekommer före **nextbaseUri**; 0 om de två grund‑URI:erna är identiska; och 1 om **baseUri** förekommer efter **nextbaseUri**.

## Se även

* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.PDF for C++](../../../)
