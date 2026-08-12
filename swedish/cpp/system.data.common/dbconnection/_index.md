---
title: "System::Data::Common::DbConnection‑klass"
linktitle: "DbConnection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::Common::DbConnection‑klass. Databasanslutning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.data.common/dbconnection/
---
## DbConnection class


Databasanslutning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class DbConnection : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_ConnectionString](./get_connectionstring/)() const | RTTI-information. |
| virtual [Open](./open/)() | Öppnar anslutning till databasen. |
| virtual [set_ConnectionString](./set_connectionstring/)(String) const | Ställer in anslutningsinformation (t.ex. server och port). |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
