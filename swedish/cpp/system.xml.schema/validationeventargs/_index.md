---
title: "System::Xml::Schema::ValidationEventArgs-klass"
linktitle: "ValidationEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Xml::Schema::ValidationEventArgs-klass. Returnerar detaljerad information relaterad till ValidationEventHandler i C++."
type: docs
weight: 200
url: /sv/cpp/system.xml.schema/validationeventargs/
---
## ValidationEventArgs class


Returnerar detaljerad information relaterad till [ValidationEventHandler](../validationeventhandler/).

```cpp
class ValidationEventArgs : public System::EventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Exception](./get_exception/)() | Returnerar [XmlSchemaException](../xmlschemaexception/) som är associerad med valideringseventet. |
| [get_Message](./get_message/)() | Returnerar textbeskrivningen som motsvarar valideringseventet. |
| [get_Severity](./get_severity/)() | Returnerar allvaret för valideringseventet. |
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
* Namespace [System::Xml::Schema](../)
* Library [Aspose.PDF for C++](../../)
