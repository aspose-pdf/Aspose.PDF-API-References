---
title: "System::Xml::XmlEntityReference class"
linktitle: "XmlEntityReference"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlEntityReference-klass. Representerar en enhetsreferensnod i C++."
type: docs
weight: 1900
url: /sv/cpp/system.xml/xmlentityreference/
---
## XmlEntityReference class


Representerar en enhetsreferensnod.

```cpp
class XmlEntityReference : public System::Xml::XmlLinkedNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [get_BaseURI](./get_baseuri/)() override | Returnerar den grundläggande Uniform Resource Identifier (URI) för den aktuella noden. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returnerar ett värde som indikerar om noden är skrivskyddad. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar nodens namn. |
| [get_NodeType](./get_nodetype/)() override | Returnerar nodens typ. |
| [get_Value](./get_value/)() override | Returnerar värdet på noden. |
| [set_Value](./set_value/)(String) override | Ställer in värdet på noden. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till noden till den specificerade [XmlWriter](../xmlwriter/). |
| [WriteTo](./writeto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar noden till den specificerade [XmlWriter](../xmlwriter/). |
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
