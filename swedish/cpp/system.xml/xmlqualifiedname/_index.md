---
title: "System::Xml::XmlQualifiedName klass"
linktitle: "XmlQualifiedName"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::XmlQualifiedName klass. Representerar ett XML‑kvalificerat namn i C++."
type: docs
weight: 3200
url: /sv/cpp/system.xml/xmlqualifiedname/
---
## XmlQualifiedName class


Representerar ett XML‑kvalificerat namn.

```cpp
class XmlQualifiedName : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Avgör om det angivna [XmlQualifiedName](./)-objektet är lika med det aktuella [XmlQualifiedName](./)-objektet. |
| [get_IsEmpty](./get_isempty/)() const | Returnerar ett värde som indikerar om [XmlQualifiedName](./) är tom. |
| [get_Name](./get_name/)() const | Returnerar en strängrepresentation av det kvalificerade namnet för [XmlQualifiedName](./). |
| [get_Namespace](./get_namespace/)() const | Returnerar en strängrepresentation av namnrymden för [XmlQualifiedName](./). |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för [XmlQualifiedName](./). |
| static [ToString](./tostring/)(const String\&, const String\&) | Returnerar strängvärdet för [XmlQualifiedName](./). |
| [ToString](./tostring/)() const override | Returnerar strängvärdet för [XmlQualifiedName](./). |
| [XmlQualifiedName](./xmlqualifiedname/)() | Initierar en ny instans av klassen [XmlQualifiedName](./). |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&) | Initierar en ny instans av klassen [XmlQualifiedName](./) med det angivna namnet. |
| [XmlQualifiedName](./xmlqualifiedname/)(const String\&, const String\&) | Initierar en ny instans av klassen [XmlQualifiedName](./) med det angivna namnet och namnrymden. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | Tillhandahåller ett tomt [XmlQualifiedName](./). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Anmärkningar



Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig instanser av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [Object](../../system/object/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
