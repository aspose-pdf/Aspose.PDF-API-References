---
title: "System::Xml::Xsl::XslCompiledTransform class"
linktitle: "XslCompiledTransform"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XslCompiledTransform class. Transformerar XML-data med en XSLT-stilmall i C++."
type: docs
weight: 300
url: /sv/cpp/system.xml.xsl/xslcompiledtransform/
---
## XslCompiledTransform class


Transformerar XML-data med en XSLT-stilmall.

```cpp
class XslCompiledTransform : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_OutputSettings](./get_outputsettings/)() | Returnerar ett [XmlWriterSettings](../../system.xml/xmlwritersettings/)-objekt som innehåller utdatainformation hämtad från **xsl:output**-elementet i stilmallen. |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Kompilerar stilmallen som finns i [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Kompilerar XSLT-stilmallen som finns i [XmlReader](../../system.xml/xmlreader/). [XmlResolver](../../system.xml/xmlresolver/) löser eventuella XSLT **import**- eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilmallen. |
| [Load](./load/)(const String\&) | Laddar och kompilerar stilmallen som finns på den angivna URI:n. |
| [Load](./load/)(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) | Laddar och kompilerar XSLT-stilmallen som anges av URI:n. [XmlResolver](../../system.xml/xmlresolver/) löser alla XSLT **import** eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilmallen. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Kompilerar stilmallen som finns i IXPathNavigable-objektet. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) | Kompilerar XSLT-stilmallen som finns i IXPathNavigable. [XmlResolver](../../system.xml/xmlresolver/) löser alla XSLT **import** eller **include**-element och XSLT-inställningarna bestämmer behörigheterna för stilmallen. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en TextWriter. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Utför transformeringen med inmatningsdokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en ström. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en TextWriter. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Utför transformeringen med inmatningsdokumentet som anges av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en ström. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XmlWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av URI:n och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av URI:n och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Utför transformeringen med inmatningsdokumentet som anges av URI:n och skriver ut resultaten till en TextWriter. |
| [Transform](./transform/)(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Utför transformeringen med inmatningsdokumentet som anges av URI:n och skriver ut resultaten till en ström. [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument. |
| [Transform](./transform/)(const String\&, const String\&) | Utför transformeringen med inmatningsdokumentet som anges av URI:n och skriver ut resultaten till en fil. |
| [Transform](./transform/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Utför transformeringen med inmatningsdokumentet som anges av [XmlReader](../../system.xml/xmlreader/)-objektet och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument och [XmlResolver](../../system.xml/xmlresolver/) löser XSLT **document()**-funktionen. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) | Utför transformeringen genom att använda inmatningsdokumentet som anges av IXPathNavigable-objektet och skriver ut resultaten till en [XmlWriter](../../system.xml/xmlwriter/). [XsltArgumentList](../xsltargumentlist/) tillhandahåller ytterligare körargument och [XmlResolver](../../system.xml/xmlresolver/) löser XSLT **document()**-funktionen. |
| [XslCompiledTransform](./xslcompiledtransform/)() | Initierar en ny instans av klassen [XslCompiledTransform](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.PDF for C++](../../)
