---
title: "System::TimeZone-klass"
linktitle: "TimeZone"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeZone-klass. Representerar en tidszon. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 6500
url: /sv/cpp/system/timezone/
---
## TimeZone class


Representerar en tidszon. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i pekaren [System::SmartPtr](../smartptr/) och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class TimeZone : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [get_CurrentTimeZone](./get_currenttimezone/)() | Returnerar en ny instans av klassen [TimeZone](./) som representerar den aktuella tidszonen. |
| virtual [get_DaylightName](./get_daylightname/)() const | Returnerar ett namn för sommartiden för tidszonen som representeras av det aktuella objektet. |
| virtual [get_StandardName](./get_standardname/)() const | Returnerar ett namn för standardtiden för tidszonen som representeras av det aktuella objektet. |
| virtual [GetDaylightChanges](./getdaylightchanges/)(int32_t) | Returnerar perioden för sommartid för ett specifikt år. |
| virtual [GetUtcOffset](./getutcoffset/)(DateTime) | Returnerar UTC-förskjutningen för den angivna lokala tiden. |
| virtual [IsDaylightSavingTime](./isdaylightsavingtime/)(DateTime) | Avgör om datum- och tidsvärdet som representeras av det angivna [DateTime](../datetime/)-objektet faller inom intervallet för sommartid för tidszonen som representeras av det aktuella [TimeZone](./)-objektet. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
