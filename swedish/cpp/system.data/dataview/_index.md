---
title: "System::Data::DataView‑klass"
linktitle: "DataView"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::DataView‑klass. Vy som arbetar på en tabell. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.data/dataview/
---
## DataView class


Vy som arbetar på tabellen. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DataView : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Count](./get_count/)() | RTTI-information. |
| [get_Table](./get_table/)() | Hämtar tabellen som vyn tillhör. |
| [idx_get](./idx_get/)(const int32_t) | Hämtar radvyer. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Data](../)
* Library [Aspose.PDF for C++](../../)
