---
title: "System::Xml::XmlSignificantWhitespace-klass"
linktitle: "XmlSignificantWhitespace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlSignificantWhitespace-klass. Representerar blanksteg mellan markup i en blandad innehållsnod eller blanksteg inom ett xml:space=''preserve''-omfång. Detta kallas också betydande blanksteg i C++."
type: docs
weight: 3700
url: /sv/cpp/system.xml/xmlsignificantwhitespace/
---
## XmlSignificantWhitespace class


Representerar blanksteg mellan markup i en blandad innehållsnod eller blanksteg inom ett **xml:space='preserve'**‑omfång. Detta kallas även betydande blanksteg.

```cpp
class XmlSignificantWhitespace : public System::Xml::XmlCharacterData
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_PreviousText](./get_previoustext/)() override | Returnerar textnoden som omedelbart föregår denna nod. |
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

* Class [XmlCharacterData](../xmlcharacterdata/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
