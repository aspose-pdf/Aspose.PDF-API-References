---
title: "System::Globalization::DaylightTime class"
linktitle: "DaylightTime"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::DaylightTime class. Period för sommartid. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.globalization/daylighttime/
---
## DaylightTime class


Period för sommartid. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DaylightTime : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DaylightTime](./daylighttime/)(DateTime, DateTime, TimeSpan) | RTTI-information. |
| [get_Delta](./get_delta/)() const | Hämtar skillnaden mellan standardtid och sommartid. |
| [get_End](./get_end/)() const | Hämtar datum och tid när sommartiden slutar. |
| [get_Start](./get_start/)() const | Hämtar datum och tid när sommartiden börjar. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
