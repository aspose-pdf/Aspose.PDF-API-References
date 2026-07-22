---
title: "System::Data::Common::DbDataReader-klass"
linktitle: "DbDataReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::Common::DbDataReader-klass. API för att ta emot data från databas. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.data.common/dbdatareader/
---
## DbDataReader class


API för att ta emot data från databas. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DbDataReader : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Close](./close/)() | Stänger datainhämtningskanal. |
| virtual [idx_get](./idx_get/)(String) | Hämtar namngivet objekt. |
| virtual [idx_get](./idx_get/)(int) | Hämtar objekt efter index. |
| virtual [Read](./read/)() | Läser nästa post från databasen. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | RTTI-information. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
