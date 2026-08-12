---
title: "System::Xml::XmlAttributeCollection klass"
linktitle: "XmlAttributeCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlAttributeCollection klass. Representerar en samling av attribut som kan nås via namn eller index i C++."
type: docs
weight: 700
url: /sv/cpp/system.xml/xmlattributecollection/
---
## XmlAttributeCollection class


Representerar en samling attribut som kan nås via namn eller index.

```cpp
class XmlAttributeCollection : public System::Xml::XmlNamedNodeMap
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Append](./append/)(const SharedPtr\<XmlAttribute\>\&) | Infogar det angivna attributet som den sista noden i samlingen. |
| [CopyTo](./copyto/)(const ArrayPtr\<SharedPtr\<XmlAttribute\>\>\&, int32_t) | Kopierar alla [XmlAttribute](../xmlattribute/) objekt från denna samling till den angivna arrayen. |
| [idx_get](./idx_get/)(int32_t) | Returnerar attributet med det angivna indexet. |
| [idx_get](./idx_get/)(const String\&) | Returnerar attributet med det angivna namnet. |
| [idx_get](./idx_get/)(const String\&, const String\&) | Returnerar attributet med det angivna lokala namnet och namnrymdens Uniform Resource Identifier (URI). |
| [InsertAfter](./insertafter/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Infogar det angivna attributet omedelbart efter det angivna referensattributet. |
| [InsertBefore](./insertbefore/)(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) | Infogar det angivna attributet omedelbart före det angivna referensattributet. |
| [Prepend](./prepend/)(const SharedPtr\<XmlAttribute\>\&) | Infogar det angivna attributet som den första noden i samlingen. |
| [Remove](./remove/)(const SharedPtr\<XmlAttribute\>\&) | Tar bort det angivna attributet från samlingen. |
| [RemoveAll](./removeall/)() | Tar bort alla attribut från samlingen. |
| [RemoveAt](./removeat/)(int32_t) | Tar bort attributet som motsvarar det angivna indexet från samlingen. |
| [SetNamedItem](./setnameditem/)(SharedPtr\<XmlNode\>) override | Lägger till ett [XmlNode](../xmlnode/) med hjälp av dess [XmlNode::get_Name](../xmlnode/get_name/) resultat. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [XmlNamedNodeMap](../xmlnamednodemap/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
