---
title: "System::Xml::XmlElement-klass"
linktitle: "XmlElement"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlElement-klass. Representerar ett element i C++."
type: docs
weight: 1700
url: /sv/cpp/system.xml/xmlelement/
---
## XmlElement class


Representerar ett element.

```cpp
class XmlElement : public System::Xml::XmlLinkedNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| virtual [get_HasAttributes](./get_hasattributes/)() | Returnerar ett **bool**-värde som indikerar om den aktuella noden har några attribut. |
| [get_InnerText](./get_innertext/)() override | Returnerar de sammanfogade värdena för noden och alla dess barn. |
| [get_InnerXml](./get_innerxml/)() override | Returnerar markupen som bara representerar barnen till denna nod. |
| [get_IsEmpty](./get_isempty/)() | Returnerar taggformatet för elementet. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på den aktuella noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NamespaceURI](./get_namespaceuri/)() override | Returnerar namnrymdens URI för denna nod. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returnerar [XmlDocument](../xmldocument/) som denna nod tillhör. |
| [get_Prefix](./get_prefix/)() override | Returnerar namnrymdsprefixet för den här noden. |
| [get_SchemaInfo](./get_schemainfo/)() override | Returnerar post‑schemavaliderings‑infosettet som har tilldelats den här noden som ett resultat av schemavalidering. |
| virtual [GetAttribute](./getattribute/)(String) | Returnerar värdet för attributet med det angivna namnet. |
| virtual [GetAttribute](./getattribute/)(String, String) | Returnerar värdet för attributet med det angivna lokala namnet och namnrymdens URI. |
| virtual [GetAttributeNode](./getattributenode/)(String) | Returnerar [XmlAttribute](../xmlattribute/) med det angivna namnet. |
| virtual [GetAttributeNode](./getattributenode/)(String, String) | Returnerar [XmlAttribute](../xmlattribute/) med det angivna lokala namnet och namnrymdens URI. |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String) | Returnerar en [XmlNodeList](../xmlnodelist/) som innehåller en lista över alla underordnade element som matchar den angivna [XmlElement::get_Name](./get_name/). |
| virtual [GetElementsByTagName](./getelementsbytagname/)(String, String) | Returnerar en [XmlNodeList](../xmlnodelist/) som innehåller en lista över alla underordnade element som matchar de angivna [XmlElement::get_LocalName](./get_localname/)- och [XmlElement::get_NamespaceURI](./get_namespaceuri/)-värdena. |
| virtual [HasAttribute](./hasattribute/)(String) | Avgör om den aktuella noden har ett attribut med det angivna namnet. |
| virtual [HasAttribute](./hasattribute/)(String, String) | Avgör om den aktuella noden har ett attribut med det angivna lokala namnet och namnrymdens URI. |
| [RemoveAll](./removeall/)() override | Tar bort alla angivna attribut och barn till den aktuella noden. Standardattribut tas inte bort. |
| virtual [RemoveAllAttributes](./removeallattributes/)() | Tar bort alla angivna attribut från elementet. Standardattribut tas inte bort. |
| virtual [RemoveAttribute](./removeattribute/)(String) | Tar bort ett attribut efter namn. |
| virtual [RemoveAttribute](./removeattribute/)(String, String) | Tar bort ett attribut med det angivna lokala namnet och namnrymdens URI. (Om det borttagna attributet har ett standardvärde ersätts det omedelbart). |
| virtual [RemoveAttributeAt](./removeattributeat/)(int32_t) | Tar bort attributnoden med det angivna indexet från elementet. (Om det borttagna attributet har ett standardvärde ersätts det omedelbart). |
| virtual [RemoveAttributeNode](./removeattributenode/)(SharedPtr\<XmlAttribute\>) | Tar bort den angivna [XmlAttribute](../xmlattribute/). |
| virtual [RemoveAttributeNode](./removeattributenode/)(String, String) | Tar bort [XmlAttribute](../xmlattribute/) som anges av det lokala namnet och namnrymdens URI. (Om det borttagna attributet har ett standardvärde ersätts det omedelbart). |
| [set_InnerText](./set_innertext/)(String) override | Ställer in de sammanslagna värdena för noden och alla dess barn. |
| [set_InnerXml](./set_innerxml/)(String) override | Ställer in markup som bara representerar barnen till denna nod. |
| [set_IsEmpty](./set_isempty/)(bool) | Ställer in taggformatet för elementet. |
| [set_Prefix](./set_prefix/)(String) override | Ställer in namnrymdsprefixet för denna nod. |
| virtual [SetAttribute](./setattribute/)(String, String) | Ställer in värdet för attributet med det angivna namnet. |
| virtual [SetAttribute](./setattribute/)(String, String, String) | Ställer in värdet för attributet med det angivna lokala namnet och namnrymdens URI. |
| virtual [SetAttributeNode](./setattributenode/)(SharedPtr\<XmlAttribute\>) | Lägger till den angivna [XmlAttribute](../xmlattribute/). |
| virtual [SetAttributeNode](./setattributenode/)(String, String) | Lägger till den angivna [XmlAttribute](../xmlattribute/). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till noden till den specificerade [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar den aktuella noden till den angivna [XmlWriter](../xmlwriter/). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlLinkedNode](../xmllinkednode/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
