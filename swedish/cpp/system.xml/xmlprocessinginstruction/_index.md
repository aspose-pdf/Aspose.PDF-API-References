---
title: "System::Xml::XmlProcessingInstruction-klass"
linktitle: "XmlProcessingInstruction"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlProcessingInstruction-klass. Representerar en bearbetningsinstruktion, som XML definierar för att behålla processor-specifik information i dokumentets text i C++."
type: docs
weight: 3100
url: /sv/cpp/system.xml/xmlprocessinginstruction/
---
## XmlProcessingInstruction class


Representerar en bearbetningsinstruktion, som XML definierar för att behålla processor‑specifik information i dokumentets text.

```cpp
class XmlProcessingInstruction : public System::Xml::XmlLinkedNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [get_Data](./get_data/)() | Returnerar innehållet i bearbetningsinstruktionen, exklusive målet. |
| [get_InnerText](./get_innertext/)() override | Returnerar de sammanfogade värdena för noden och alla dess barn. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_Target](./get_target/)() | Returnerar målet för bearbetningsinstruktionen. |
| [get_Value](./get_value/)() override | Returnerar värdet på noden. |
| [set_Data](./set_data/)(const String\&) | Ställer in innehållet i bearbetningsinstruktionen, exklusive målet. |
| [set_InnerText](./set_innertext/)(String) override | Ställer in de sammanslagna värdena för noden och alla dess barn. |
| [set_Value](./set_value/)(String) override | Ställer in värdet på noden. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till noden till den angivna [XmlWriter](../xmlwriter/). Eftersom ProcessingInstruction-noder inte har barn har denna metod ingen effekt. |
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
