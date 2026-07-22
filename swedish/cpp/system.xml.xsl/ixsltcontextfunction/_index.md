---
title: "System::Xml::Xsl::IXsltContextFunction-klass"
linktitle: "IXsltContextFunction"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::IXsltContextFunction-klass. Tillhandahåller ett gränssnitt till en given funktion som definieras i Extensible Stylesheet Language for Transformations (XSLT)-stilmallen under körningstid i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml.xsl/ixsltcontextfunction/
---
## IXsltContextFunction class


Tillhandahåller ett gränssnitt till en given funktion som definieras i Extensible Stylesheet Language for Transformations (XSLT)-stilmallen under körning.

```cpp
class IXsltContextFunction : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_ArgTypes](./get_argtypes/)() | Returnerar de angivna XML Path Language ([XPath](../../system.xml.xpath/))-typerna för funktionens argumentlista. Denna information kan användas för att upptäcka funktionens signatur, vilket gör det möjligt att skilja mellan överlagrade funktioner. |
| virtual [get_Maxargs](./get_maxargs/)() | Returnerar det maximala antalet argument för funktionen. Detta gör det möjligt för användaren att skilja mellan överlagrade funktioner. |
| virtual [get_Minargs](./get_minargs/)() | Returnerar det minsta antalet argument för funktionen. Detta gör det möjligt för användaren att skilja mellan överlagrade funktioner. |
| virtual [get_ReturnType](./get_returntype/)() | Returnerar XPathResultType som representerar den [XPath](../../system.xml.xpath/)-typ som returneras av funktionen. |
| virtual [Invoke](./invoke/)(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) | Tillhandahåller metoden för att anropa funktionen med de angivna argumenten i den givna kontexten. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
