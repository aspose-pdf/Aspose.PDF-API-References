---
title: "System::Xml::XPath::XPathDocument klass"
linktitle: "XPathDocument"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XPath::XPathDocument klass. Tillhandahåller en snabb, skrivskyddad, minnesbaserad representation av ett XML-dokument genom att använda XPath‑datamodellen i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.xpath/xpathdocument/
---
## XPathDocument class


Tillhandahåller en snabb, skrivskyddad, minnesbaserad representation av ett XML-dokument genom att använda [XPath](../)‑datamodellen.

```cpp
class XPathDocument : public System::Xml::XPath::IXPathNavigable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateNavigator](./createnavigator/)() override | Initierar ett skrivskyddat [XPathNavigator](../xpathnavigator/)‑objekt för att navigera genom noder i detta [XPathDocument](./). |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&) | Initierar en ny instans av [XPathDocument](./)‑klassen från XML‑data som finns i det angivna [XmlReader](../../system.xml/xmlreader/)‑objektet. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<XmlReader\>\&, XmlSpace) | Initierar en ny instans av [XPathDocument](./)‑klassen från XML‑data som finns i det angivna [XmlReader](../../system.xml/xmlreader/)‑objektet med den angivna hanteringen av blanksteg. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::TextReader\>\&) | Initierar en ny instans av [XPathDocument](./)‑klassen från XML‑data som finns i det angivna TextReader‑objektet. |
| [XPathDocument](./xpathdocument/)(const SharedPtr\<IO::Stream\>\&) | Initierar en ny instans av [XPathDocument](./)‑klassen från XML‑data i det angivna Stream‑objektet. |
| [XPathDocument](./xpathdocument/)(const String\&) | Initierar en ny instans av [XPathDocument](./)‑klassen från XML‑data i den angivna filen. |
| [XPathDocument](./xpathdocument/)(const String\&, XmlSpace) | Initierar en ny instans av [XPathDocument](./)‑klassen från XML‑data i den fil som angivits med den specificerade hanteringen av blanksteg. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [IXPathNavigable](../ixpathnavigable/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.PDF for C++](../../)
