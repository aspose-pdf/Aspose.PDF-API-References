---
title: "System::Xml::XmlValidatingReader::XmlValidatingReader konstruktor"
linktitle: "XmlValidatingReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlValidatingReader::XmlValidatingReader konstruktor. Initierar en ny instans av XmlValidatingReader-klassen med de angivna värdena i C++."
type: docs
weight: 100
url: /sv/cpp/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initierar en ny instans av klassen [XmlValidatingReader](../) med de angivna värdena.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFragment | const SharedPtr\<IO::Stream\>\& | Strömmen som innehåller XML‑fragmentet att tolka. |
| fragType | XmlNodeType | Den [XmlNodeType](../../xmlnodetype/) för XML-fragmentet. Detta bestämmer vad fragmentet kan innehålla (se tabellen nedan). |
| context | const SharedPtr\<XmlParserContext\>\& | Den [XmlParserContext](../../xmlparsercontext/) i vilken XML-fragmentet ska parsas. Detta inkluderar [XmlNameTable](../../xmlnametable/) att använda, kodning, namnrymdsomfattning, aktuellt **xml:lang**, och **xml:space** omfattning. |
## Anmärkningar



Följande tabell listar giltiga värden för **fragType** och hur läsaren tolkar varje av de olika nodtyperna. |||
|-|-|
| XmlNodeType | Fragment kan innehålla |
| Element | Allt giltigt elementinnehåll (till exempel en kombination av element, kommentarer, processinstruktioner, cdata, text och entitetsreferenser). |
| Attribute | Värdet på ett attribut (delen inom citationstecknen). |
| Document | Innehållet i ett helt XML-dokument; detta upprätthåller dokumentnivåregler. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


Initierar en ny instans av klassen [XmlValidatingReader](../) som validerar innehållet som returneras från den angivna [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | const SharedPtr\<XmlReader\>\& | [XmlReader](../../xmlreader/) att läsa från under validering. Den nuvarande implementationen stödjer endast [XmlTextReader](../../xmltextreader/). |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Initierar en ny instans av klassen [XmlValidatingReader](../) med de angivna värdena.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlFragment | const String\& | Strängen som innehåller XML‑fragmentet att analysera. |
| fragType | XmlNodeType | Den [XmlNodeType](../../xmlnodetype/) för XML-fragmentet. Detta bestämmer också vad fragmentsträngen kan innehålla (se tabellen nedan). |
| context | const SharedPtr\<XmlParserContext\>\& | Den [XmlParserContext](../../xmlparsercontext/) i vilken XML-fragmentet ska parsas. Detta inkluderar [NameTable](../../nametable/) att använda, kodning, namnrymdsomfattning, aktuellt **xml:lang**, och **xml:space** omfattning. |
## Anmärkningar



Följande tabell listar giltiga värden för **fragType** och hur läsaren tolkar varje av de olika nodtyperna. |||
|-|-|
| XmlNodeType | Fragment kan innehålla |
| Element | Allt giltigt elementinnehåll (till exempel en kombination av element, kommentarer, processinstruktioner, cdata, text och entitetsreferenser). |
| Attribute | Värdet på ett attribut (delen inom citationstecknen). |
| Document | Innehållet i ett helt XML-dokument; detta upprätthåller dokumentnivåregler. |

## Se även

* Class [String](../../../system/string/)
* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
