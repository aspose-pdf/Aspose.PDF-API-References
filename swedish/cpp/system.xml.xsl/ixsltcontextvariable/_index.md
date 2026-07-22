---
title: "System::Xml::Xsl::IXsltContextVariable-klass"
linktitle: "IXsltContextVariable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::IXsltContextVariable-klass. Tillhandahåller ett gränssnitt till en given variabel som definieras i stilmallen under körningstid i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.xsl/ixsltcontextvariable/
---
## IXsltContextVariable class


Tillhandahåller ett gränssnitt till en given variabel som definieras i stilmallen under körning.

```cpp
class IXsltContextVariable : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Evaluate](./evaluate/)(SharedPtr\<XsltContext\>) | Utvärderar variabeln vid körning och returnerar ett objekt som representerar variabelns värde. |
| virtual [get_IsLocal](./get_islocal/)() | Returnerar ett värde som indikerar om variabeln är lokal. |
| virtual [get_IsParam](./get_isparam/)() | Returnerar ett värde som indikerar om variabeln är en Extensible Stylesheet Language Transformations (XSLT)-parameter. Detta kan vara en parameter till en stilmall eller en mall. |
| virtual [get_VariableType](./get_variabletype/)() | Returnerar XPathResultType som representerar XML Path Language ([XPath](../../system.xml.xpath/))-typen för variabeln. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
