---
title: "System::Xml::XmlDocumentFragment klass"
linktitle: "XmlDocumentFragment"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocumentFragment klass. Representerar ett lättviktigt objekt som är användbart för trädinsättningsoperationer i C++."
type: docs
weight: 1500
url: /sv/cpp/system.xml/xmldocumentfragment/
---
## XmlDocumentFragment class


Representerar ett lättviktigt objekt som är användbart för trädinsättningsoperationer.

```cpp
class XmlDocumentFragment : public System::Xml::XmlNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [get_InnerXml](./get_innerxml/)() override | Returnerar markup som representerar barnen till denna nod. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_OwnerDocument](./get_ownerdocument/)() override | Returnerar [XmlDocument](../xmldocument/) som denna nod tillhör. |
| [set_InnerXml](./set_innerxml/)(String) override | Ställer in markup som representerar barnen till denna nod. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till noden till den specificerade [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar noden till den specificerade [XmlWriter](../xmlwriter/). |
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
