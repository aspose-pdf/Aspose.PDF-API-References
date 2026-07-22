---
title: "System::Xml::Xsl::XslTransform-klass"
linktitle: "XslTransform"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Xsl::XslTransform-klass. Transformerar XML-data med en Extensible Stylesheet Language for Transformations (XSLT)-stilark i C++."
type: docs
weight: 700
url: /sv/cpp/system.xml.xsl/xsltransform/
---
## XslTransform class


Transformerar XML-data med en Extensible Stylesheet Language for Transformations (XSLT)-stilmall.

```cpp
class XslTransform : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&) | Laddar XSLT-stilarket som finns i [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Laddar XSLT-stilarket som finns i [XmlReader](../../system.xml/xmlreader/). |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) | Laddar XSLT-stilarket som finns i IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Laddar XSLT-stilarket som finns i IXPathNavigable. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) | Laddar XSLT-stilarket som finns i XPathNavigator. |
| [Load](./load/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Laddar XSLT-stilarket som finns i XPathNavigator. |
| [Load](./load/)(const String\&) | Laddar XSLT-stilarket som anges av en URL. |
| [Load](./load/)(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Laddar XSLT-stilarket som anges av en URL. |
| [set_XmlResolver](./set_xmlresolver/)(const SharedPtr\<System::Xml::XmlResolver\>\&) | Ställer in [XmlResolver](../../system.xml/xmlresolver/) som används för att lösa externa resurser när metoden [XslTransform::Transform](./transform/) anropas. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) | Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i XPathNavigator med de angivna args och skriver ut resultatet till en [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Transformerar XML-data i XPathNavigator med de angivna args och skriver ut resultatet till en [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Transformerar XML-data i XPathNavigator med de angivna **args** och skriver ut resultatet till en TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlReader](../../system.xml/xmlreader/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en TextWriter. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en Stream. |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) | Transformerar XML-data i IXPathNavigable med de angivna **args** och skriver ut resultatet till en [XmlWriter](../../system.xml/xmlwriter/). |
| [Transform](./transform/)(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) | Transformerar XML-data i indatafilen och skriver ut resultatet till en utdatafil. |
| [Transform](./transform/)(const String\&, const String\&) | Transformerar XML-data i indatafilen och skriver ut resultatet till en utdatafil. |
| [XslTransform](./xsltransform/)() | Initierar en ny instans av klassen [XslTransform](./). |
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
