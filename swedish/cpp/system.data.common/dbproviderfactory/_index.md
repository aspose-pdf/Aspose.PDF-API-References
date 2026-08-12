---
title: "System::Data::Common::DbProviderFactory-klass"
linktitle: "DbProviderFactory"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Data::Common::DbProviderFactory-klass. Leverantör för åtkomst till databas. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.data.common/dbproviderfactory/
---
## DbProviderFactory class


Leverantör för åtkomst till databas. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DbProviderFactory : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [CreateCommand](./createcommand/)() | RTTI-information. |
| virtual [CreateConnection](./createconnection/)() | Skapar databasanslutning. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Data::Common](../)
* Library [Aspose.PDF for C++](../../)
