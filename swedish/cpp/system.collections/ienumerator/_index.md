---
title: "System::Collections::IEnumerator-klass"
linktitle: "IEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::IEnumerator-klass. Gränssnitt för enumerator som kan användas för att iterera genom vissa element. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.collections/ienumerator/
---
## IEnumerator class


Gränssnitt för enumerator som kan användas för att iterera genom vissa element. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class IEnumerator : public virtual System::IDisposable,
                    public virtual System::Object
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Current](./current/)() const | Hämtar aktuellt element. |
| virtual [get_Current](./get_current/)() const | Hämtar aktuellt element. |
| virtual [MoveNext](./movenext/)() | Flyttar enumerator till nästa element. Om inget element har refererats tidigare, sätts referensen till det första tillgängliga elementet. Om behållarens slut har nåtts, görs inget. |
| virtual [Reset](./reset/)() | Återställer enumeratorn till positionen före det första elementet. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ValueType](./valuetype/) | RTTI-information. |

## Se även

* Class [IDisposable](../../system/idisposable/)
* Class [Object](../../system/object/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
