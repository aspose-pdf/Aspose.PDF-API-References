---
title: "System::Xml::XmlEntity klass"
linktitle: "XmlEntity"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlEntity klass. Representerar en entitetsdeklaration, såsom <!ENTITY... > i C++."
type: docs
weight: 1800
url: /sv/cpp/system.xml/xmlentity/
---
## XmlEntity class


Representerar en enhetsdeklaration, såsom **<!ENTITY... >**.

```cpp
class XmlEntity : public System::Xml::XmlNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en dubblett av denna nod. Entitetsnoder kan inte klonas. Att anropa den här metoden på ett [XmlEntity](./)-objekt kastar ett undantag. |
| [get_BaseURI](./get_baseuri/)() override | Returnerar den grundläggande Uniform Resource Identifier (URI) för den aktuella noden. |
| [get_InnerText](./get_innertext/)() override | Returnerar de sammanslagna värdena för entitetsnoden och alla dess barn. |
| [get_InnerXml](./get_innerxml/)() override | Returnerar markup som representerar barnen till denna nod. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returnerar ett värde som indikerar om noden är skrivskyddad. |
| [get_LocalName](./get_localname/)() override | Returnerar nodens namn utan namnrymdspräfixet. |
| [get_Name](./get_name/)() override | Returnerar nodens namn. |
| [get_NodeType](./get_nodetype/)() override | Returnerar nodens typ. |
| [get_NotationName](./get_notationname/)() | Returnerar namnet på det valfria NDATA-attributet i entitetsdeklarationen. |
| [get_OuterXml](./get_outerxml/)() override | Returnerar markup som representerar denna nod och alla dess barn. |
| [get_PublicId](./get_publicid/)() | Returnerar värdet på den offentliga identifieraren i entitetsdeklarationen. |
| [get_SystemId](./get_systemid/)() | Returnerar värdet på systemidentifieraren i entitetsdeklarationen. |
| [set_InnerText](./set_innertext/)(String) override | Ställer in de sammanslagna värdena för entitetsnoden och alla dess barn. |
| [set_InnerXml](./set_innerxml/)(String) override | Ställer in markup som representerar barnen till denna nod. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till noden till den angivna [XmlWriter](../xmlwriter/). För [XmlEntity](./)-noder har den här metoden ingen effekt. |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar noden till den angivna [XmlWriter](../xmlwriter/). För [XmlEntity](./)-noder har den här metoden ingen effekt. |
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
