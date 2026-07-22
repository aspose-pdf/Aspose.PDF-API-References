---
title: "System::Xml::Xsl::XsltContext-klass"
linktitle: "XsltContext"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XsltContext-klass. Inkapslar den aktuella exekveringskontexten för Extensible Stylesheet Language for Transformations (XSLT)-processorn, vilket möjliggör att XML Path Language (XPath) kan lösa funktioner, parametrar och namnrymder inom XPath‑uttryck i C++."
type: docs
weight: 500
url: /sv/cpp/system.xml.xsl/xsltcontext/
---
## XsltContext class


Inkapslar den aktuella exekveringskontexten för Extensible Stylesheet Language for Transformations (XSLT)-processorn, vilket möjliggör att XML Path Language ([XPath](../../system.xml.xpath/)) kan lösa funktioner, parametrar och namnrymder inom [XPath](../../system.xml.xpath/)-uttryck.

```cpp
class XsltContext : public System::Xml::XmlNamespaceManager
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CompareDocument](./comparedocument/)(String, String) | När den åsidosätts i en avledd klass jämför den de grundläggande Uniform Resource Identifiers (URIs) för två dokument baserat på den ordning dokumenten laddades av XSLT-processorn (det vill säga [XslTransform](../xsltransform/)-klassen). |
| virtual [get_Whitespace](./get_whitespace/)() | När den åsidosätts i en avledd klass får den ett värde som indikerar om blankstegsnoder ska inkluderas i utdata. |
| virtual [PreserveWhitespace](./preservewhitespace/)(SharedPtr\<System::Xml::XPath::XPathNavigator\>) | När den åsidosätts i en avledd klass utvärderar den om blankstegsnoder ska bevaras eller tas bort för den givna kontexten. |
| virtual [ResolveFunction](./resolvefunction/)(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) | När den åsidosätts i en avledd klass löser den en funktionsreferens och returnerar ett [IXsltContextFunction](../ixsltcontextfunction/) som representerar funktionen. [IXsltContextFunction](../ixsltcontextfunction/) används vid exekvering för att hämta funktionsvärdet. |
| virtual [ResolveVariable](./resolvevariable/)(String, String) | När den åsidosätts i en avledd klass löser den en variabelreferens och returnerar ett [IXsltContextVariable](../ixsltcontextvariable/) som representerar variabeln. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
