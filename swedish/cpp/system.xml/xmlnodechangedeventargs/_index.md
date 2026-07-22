---
title: "System::Xml::XmlNodeChangedEventArgs class"
linktitle: "XmlNodeChangedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlNodeChangedEventArgs class. Tillhandahåller data för händelserna XmlDocument::NodeChanged, XmlDocument::NodeChanging, XmlDocument::NodeInserted, XmlDocument::NodeInserting, XmlDocument::NodeRemoved och XmlDocument::NodeRemoving i C++."
type: docs
weight: 2600
url: /sv/cpp/system.xml/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs class


Tillhandahåller data för händelserna **XmlDocument::NodeChanged**, **XmlDocument::NodeChanging**, **XmlDocument::NodeInserted**, **XmlDocument::NodeInserting**, **XmlDocument::NodeRemoved** och **XmlDocument::NodeRemoving**.

```cpp
class XmlNodeChangedEventArgs : public System::EventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Action](./get_action/)() | Returnerar ett värde som indikerar vilken typ av nodändringshändelse som inträffar. |
| [get_NewParent](./get_newparent/)() | Returnerar värdet av [XmlNode::get_ParentNode](../xmlnode/get_parentnode/) efter att operationen slutförts. |
| [get_NewValue](./get_newvalue/)() | Returnerar det nya värdet av noden. |
| [get_Node](./get_node/)() | Returnerar [XmlNode](../xmlnode/) som läggs till, tas bort eller ändras. |
| [get_OldParent](./get_oldparent/)() | Returnerar värdet av [XmlNode::get_ParentNode](../xmlnode/get_parentnode/) innan operationen påbörjades. |
| [get_OldValue](./get_oldvalue/)() | Returnerar det ursprungliga värdet av noden. |
| [XmlNodeChangedEventArgs](./xmlnodechangedeventargs/)(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) | Initierar en ny instans av klassen [XmlNodeChangedEventArgs](./). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
