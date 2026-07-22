---
title: "System::Net::Sockets::LingerOption klass"
linktitle: "LingerOption"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Sockets::LingerOption klass. Anger om en socket ska förbli ansluten efter ett anrop till Close() eller Close()-metoderna. Den anger också perioden som socketen förblir ansluten om dataöverföringen fortsätter. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.net.sockets/lingeroption/
---
## LingerOption class


Anger om en socket ska förbli ansluten efter ett anrop till Close() eller Close()-metoderna. Den anger också perioden som socketen förblir ansluten om dataöverföringen fortsätter. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class LingerOption : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Enabled](./get_enabled/)() | RTTI-information. |
| [get_LingerTime](./get_lingertime/)() | Hämtar en fördröjningstimeout i sekunder. |
| [LingerOption](./lingeroption/)(bool, int32_t) | Skapar en ny instans. |
| [set_Enabled](./set_enabled/)(bool) | Ställer in ett värde som indikerar om socketen kommer att fördröja stängning i ett försök att skicka all väntande data. |
| [set_LingerTime](./set_lingertime/)(int32_t) | Ställer in en fördröjningstimeout i sekunder. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.PDF for C++](../../)
