---
title: "System::Xml::XmlParserContext-klass"
linktitle: "XmlParserContext"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlParserContext-klass. Tillhandahåller all kontextinformation som krävs av XmlReader för att tolka ett XML-fragment i C++."
type: docs
weight: 3000
url: /sv/cpp/system.xml/xmlparsercontext/
---
## XmlParserContext class


Tillhandahåller all kontextinformation som krävs av [XmlReader](../xmlreader/) för att tolka ett XML-fragment.

```cpp
class XmlParserContext : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BaseURI](./get_baseuri/)() | Returnerar bas-URI:n. |
| [get_DocTypeName](./get_doctypename/)() | Returnerar namnet på dokumenttypdeklarationen. |
| [get_Encoding](./get_encoding/)() | Returnerar kodningstypen. |
| [get_InternalSubset](./get_internalsubset/)() | Returnerar den interna DTD-undermängden. |
| [get_NamespaceManager](./get_namespacemanager/)() | Returnerar [XmlNamespaceManager](../xmlnamespacemanager/). |
| [get_NameTable](./get_nametable/)() | Returnerar [XmlNameTable](../xmlnametable/) som används för att atomisera strängar. För mer information om atomiserade strängar, se [XmlNameTable](../xmlnametable/). |
| [get_PublicId](./get_publicid/)() | Returnerar den offentliga identifieraren. |
| [get_SystemId](./get_systemid/)() | Returnerar systemidentifieraren. |
| [get_XmlLang](./get_xmllang/)() | Returnerar det aktuella **xml:lang**-omfånget. |
| [get_XmlSpace](./get_xmlspace/)() | Returnerar det aktuella **xml:space**-omfånget. |
| [set_BaseURI](./set_baseuri/)(const String\&) | Ställer in bas-URI:n. |
| [set_DocTypeName](./set_doctypename/)(const String\&) | Ställer in namnet på dokumenttypdeklarationen. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<System::Text::Encoding\>\&) | Ställer in kodningstypen. |
| [set_InternalSubset](./set_internalsubset/)(const String\&) | Ställer in den interna DTD-delmängden. |
| [set_NamespaceManager](./set_namespacemanager/)(const SharedPtr\<XmlNamespaceManager\>\&) | Ställer in [XmlNamespaceManager](../xmlnamespacemanager/). |
| [set_NameTable](./set_nametable/)(const SharedPtr\<XmlNameTable\>\&) | Ställer in [XmlNameTable](../xmlnametable/) som används för att atomisera strängar. För mer information om atomiserade strängar, se [XmlNameTable](../xmlnametable/). |
| [set_PublicId](./set_publicid/)(const String\&) | Ställer in den offentliga identifieraren. |
| [set_SystemId](./set_systemid/)(const String\&) | Ställer in systemidentifieraren. |
| [set_XmlLang](./set_xmllang/)(const String\&) | Ställer in det aktuella **xml:lang**-omfånget. |
| [set_XmlSpace](./set_xmlspace/)(System::Xml::XmlSpace) | Ställer in det aktuella **xml:space**-omfånget. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) | Initierar en ny instans av klassen [XmlParserContext](./) med den angivna [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**- och **xml:space**-värdena. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Initierar en ny instans av klassen [XmlParserContext](./) med den angivna [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space** och kodning. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) | Initierar en ny instans av klassen [XmlParserContext](./) med den angivna [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), bas-URI, **xml:lang**, **xml:space** och dokumenttypvärden. |
| [XmlParserContext](./xmlparsercontext/)(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) | Initierar en ny instans av klassen [XmlParserContext](./) med den angivna [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), bas-URI, **xml:lang**, **xml:space**, kodning och dokumenttypvärden. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
