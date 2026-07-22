---
title: "System::Xml::Schema::XmlSchemaObjectEnumerator-klass"
linktitle: "XmlSchemaObjectEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::XmlSchemaObjectEnumerator-klass. Representerar enumeratorn för XmlSchemaObjectCollection i C++."
type: docs
weight: 5200
url: /sv/cpp/system.xml.schema/xmlschemaobjectenumerator/
---
## XmlSchemaObjectEnumerator class


Representerar enumeratorn för [XmlSchemaObjectCollection](../xmlschemaobjectcollection/).

```cpp
class XmlSchemaObjectEnumerator : public System::Collections::Generic::IEnumerator<SharedPtr<System::Xml::Schema::XmlSchemaObject>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| [Dispose](./dispose/)() override | Gör ingenting. |
| [get_Current](./get_current/)() const override | Returnerar det aktuella [XmlSchemaObject](../xmlschemaobject/) i samlingen. |
| [MoveNext](./movenext/)() override | Flyttar till nästa objekt i samlingen. |
| [Reset](./reset/)() override | Återställer enumeratorn till början av samlingen. |
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
