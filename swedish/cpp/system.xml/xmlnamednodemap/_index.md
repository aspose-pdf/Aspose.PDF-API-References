---
title: "System::Xml::XmlNamedNodeMap klass"
linktitle: "XmlNamedNodeMap"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNamedNodeMap klass. Representerar en samling noder som kan nås via namn eller index i C++."
type: docs
weight: 2200
url: /sv/cpp/system.xml/xmlnamednodemap/
---
## XmlNamedNodeMap class


Representerar en samling noder som kan nås via namn eller index.

```cpp
class XmlNamedNodeMap : public System::Collections::Generic::IEnumerable<SharedPtr<System::Xml::XmlNode>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [begin](./begin/)() const | Hämtar iterator till det första elementet i samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator till det första elementet i samlingen. |
| [cend](./cend/)() const | Hämtar iterator för ett icke-existerande element bakom det sista elementet i samlingen. |
| [end](./end/)() const | Hämtar iterator för ett icke-existerande element bakom det sista elementet i samlingen. |
| virtual [get_Count](./get_count/)() | Returnerar antalet noder i [XmlNamedNodeMap](./). |
| [GetEnumerator](./getenumerator/)() override | Tillhandahåller stöd för iteration över samlingen av noder i [XmlNamedNodeMap](./). |
| virtual [GetNamedItem](./getnameditem/)(String) | Hämtar ett [XmlNode](../xmlnode/) specificerat med namn. |
| virtual [GetNamedItem](./getnameditem/)(String, String) | Hämtar en nod med matchande [XmlNode::get_LocalName](../xmlnode/get_localname/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) värden. |
| virtual [Item](./item/)(int32_t) | Hämtar noden på det angivna indexet i [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String) | Tar bort noden från [XmlNamedNodeMap](./). |
| virtual [RemoveNamedItem](./removenameditem/)(String, String) | Tar bort en nod med matchande [XmlNode::get_LocalName](../xmlnode/get_localname/) och [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) värden. |
| virtual [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) | Lägger till ett [XmlNode](../xmlnode/) med dess [XmlNode::get_Name](../xmlnode/get_name/) värde. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [iterator](./iterator/) | Iterator-typ. |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
