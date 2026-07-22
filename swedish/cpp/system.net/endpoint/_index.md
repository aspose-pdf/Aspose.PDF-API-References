---
title: "System::Net::EndPoint klass"
linktitle: "EndPoint"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::EndPoint klass. Den abstrakta klassen innehåller en nätverksadress. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.net/endpoint/
---
## EndPoint class


Den abstrakta klassen innehåller en nätverksadress. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class EndPoint : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Create](./create/)(System::SharedPtr\<SocketAddress\>) | Skapa en ny instans av [EndPoint](./)-klassen med den angivna socketadressen. |
| virtual [get_AddressFamily](./get_addressfamily/)() | RTTI-information. |
| virtual [GetImpl](./getimpl/)() const | Returnerar en pekare till implementationen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ImplPtr](./implptr/) | En pekare till implementationen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
