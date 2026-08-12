---
title: "System::Xml::XmlDocumentType-klass"
linktitle: "XmlDocumentType"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlDocumentType-klass. Representerar dokumenttypdeklarationen i C++."
type: docs
weight: 1600
url: /sv/cpp/system.xml/xmldocumenttype/
---
## XmlDocumentType class


Representerar dokumenttypdeklarationen.

```cpp
class XmlDocumentType : public System::Xml::XmlLinkedNode
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneNode](./clonenode/)(bool) override | Skapar en duplikat av denna nod. |
| [get_Entities](./get_entities/)() | Returnerar samlingen av [XmlEntity](../xmlentity/) noder som deklarerats i dokumenttypdeklarationen. |
| [get_InternalSubset](./get_internalsubset/)() | Returnerar värdet av dokumenttypdefinitionens (DTD) interna delmängd i DOCTYPE-deklarationen. |
| [get_IsReadOnly](./get_isreadonly/)() override | Returnerar ett värde som indikerar om noden är skrivskyddad. |
| [get_LocalName](./get_localname/)() override | Returnerar det lokala namnet på noden. |
| [get_Name](./get_name/)() override | Returnerar det kvalificerade namnet på noden. |
| [get_NodeType](./get_nodetype/)() override | Returnerar typen på den aktuella noden. |
| [get_Notations](./get_notations/)() | Returnerar samlingen av [XmlNotation](../xmlnotation/) noder som finns i dokumenttypdeklarationen. |
| [get_PublicId](./get_publicid/)() | Returnerar värdet av den offentliga identifieraren i DOCTYPE-deklarationen. |
| [get_SystemId](./get_systemid/)() | Returnerar värdet av systemidentifieraren i DOCTYPE-deklarationen. |
| [WriteContentTo](./writecontentto/)(const SharedPtr\<XmlWriter\>\&) override | Sparar alla barn till noden till den angivna [XmlWriter](../xmlwriter/). För [XmlDocumentType](./) noder har denna metod ingen effekt. |
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
