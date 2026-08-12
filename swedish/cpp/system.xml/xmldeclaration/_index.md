---
title: "System::Xml::XmlDeclaration klass"
linktitle: "XmlDeclaration"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDeclaration klass. Representerar XML-deklarationsnoden <?xml version=''1.0''...?> i C++."
type: docs
weight: 1300
url: /sv/cpp/system.xml/xmldeclaration/
---
## XmlDeclaration class


Representerar XML-deklarationsnoden **<?xml version='1.0'...?>**.

```cpp
class XmlDeclaration : public System::Xml::XmlLinkedNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [get_Encoding](./get_encoding/)() | Returnerar kodningsnivån för XML-dokumentet. |
| [get_InnerText](./get_innertext/)() override | Returnerar de sammanslagna värdena för [XmlDeclaration](./). |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_Standalone](./get_standalone/)() | Returnerar värdet för attributet standalone. |
| [get_Value](./get_value/)() override | Returnerar värdet för [XmlDeclaration](./). |
| [get_Version](./get_version/)() | Returnerar XML-versionen av dokumentet. |
| [set_Encoding](./set_encoding/)(const String\&) | Ställer in kodningsnivån för XML-dokumentet. |
| [set_InnerText](./set_innertext/)(String) override | Ställer in de sammanslagna värdena för [XmlDeclaration](./). |
| [set_Standalone](./set_standalone/)(const String\&) | Ställer in värdet för attributet standalone. |
| [set_Value](./set_value/)(String) override | Ställer in värdet för [XmlDeclaration](./). |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar nodens barn till den angivna [XmlWriter](../xmlwriter/). Eftersom [XmlDeclaration](./) noder inte har barn har den här metoden ingen effekt. |
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
