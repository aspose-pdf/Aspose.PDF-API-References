---
title: "System::Xml::Schema::XmlSchemaCollectionEnumerator klass"
linktitle: "XmlSchemaCollectionEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaCollectionEnumerator klass. Stöder en enkel iteration över en samling. Denna klass kan inte ärvas i C++."
type: docs
weight: 1600
url: /sv/cpp/system.xml.schema/xmlschemacollectionenumerator/
---
## XmlSchemaCollectionEnumerator class


Stöder en enkel iteration över en samling. Denna klass kan inte ärvas.

```cpp
class XmlSchemaCollectionEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchema>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| [Dispose](./dispose/)() override | Gör ingenting. |
| [get_Current](./get_current/)() const override | Returnerar den aktuella [XmlSchema](../xmlschema/) i samlingen. |
| [MoveNext](./movenext/)() override | Flyttar fram enumeratorn till nästa schema i samlingen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [IEnumerator](../../system.collections.generic/ienumerator/)
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
