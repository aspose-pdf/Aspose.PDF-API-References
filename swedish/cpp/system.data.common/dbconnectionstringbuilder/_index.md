---
title: "System::Data::Common::DbConnectionStringBuilder‑klass"
linktitle: "DbConnectionStringBuilder"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::Common::DbConnectionStringBuilder‑klass. API för att bygga anslutningssträng med namngivna fält. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.data.common/dbconnectionstringbuilder/
---
## DbConnectionStringBuilder class


API för att bygga anslutningssträng med namngivna fält. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DbConnectionStringBuilder : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_ConnectionString](./get_connectionstring/)() const | Hämtar hela anslutningssträngen. |
| virtual [idx_get](./idx_get/)(String) | RTTI-information. |
| virtual [idx_set](./idx_set/)(String, Object::ptr) | Ställer in namngivet värde. |
| virtual [set_ConnectionString](./set_connectionstring/)(String) | Ställer in hela anslutningssträngen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
