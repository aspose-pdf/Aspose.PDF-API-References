---
title: "System::Data::Common::DbCommand-klass"
linktitle: "DbCommand"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::Common::DbCommand-klass. Databaskommando. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.data.common/dbcommand/
---
## DbCommand class


Databaskommando. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DbCommand : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [ExecuteNonQuery](./executenonquery/)() | Utför icke-frågekommando. |
| virtual [ExecuteReader](./executereader/)() | Utför frågekommando. |
| virtual [get_CommandText](./get_commandtext/)() const | RTTI-information. |
| virtual [get_Connection](./get_connection/)() const | Hämtar databasanslutning som är associerad med kommandot. |
| virtual [set_CommandText](./set_commandtext/)(String) const | Ställer in DB-kommandotext. |
| virtual [set_Connection](./set_connection/)(SharedPtr\<System::Data::Common::DbConnection\>) | Hämtar databasanslutning som är associerad med kommandot. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
