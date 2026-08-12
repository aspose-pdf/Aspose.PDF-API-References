---
title: "System::Xml::XmlNotation-klass"
linktitle: "XmlNotation"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNotation-klass. Representerar en notationsdeklaration, såsom <!NOTATION... > i C++."
type: docs
weight: 2900
url: /sv/cpp/system.xml/xmlnotation/
---
## XmlNotation class


Representerar en notationsdeklaration, såsom **<!NOTATION... >**.

```cpp
class XmlNotation : public System::Xml::XmlNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en dubblett av denna nod. Notationsnoder kan inte klonas. Att anropa den här metoden på ett [XmlNotation](./)-objekt kastar ett undantag. |
| [get_InnerXml](./get_innerxml/)() override | Returnerar markup som representerar barnen till denna nod. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returnerar ett värde som indikerar om noden är skrivskyddad. |
| [get_LocalName](./get_localname/)() override | Returnerar namnet på den aktuella noden utan namnrymdsprefixet. |
| [get_Name](./get_name/)() override | Returnerar namnet på den aktuella noden. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_OuterXml](./get_outerxml/)() override | Returnerar markup som representerar denna nod och alla dess barn. |
| [get_PublicId](./get_publicid/)() | Returnerar värdet på den offentliga identifieraren i notationsdeklarationen. |
| [get_SystemId](./get_systemid/)() | Returnerar värdet på systemidentifieraren i notationsdeklarationen. |
| [set_InnerXml](./set_innerxml/)(String) override | Ställer in markup som representerar barnen till denna nod. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar nodens barn till den angivna [XmlWriter](../xmlwriter/). Denna metod har ingen effekt på [XmlNotation](./)-noder. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar noden till den angivna [XmlWriter](../xmlwriter/). Denna metod har ingen effekt på [XmlNotation](./)-noder. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlNode](../xmlnode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
