---
title: "System::IO::StringReader-klass"
linktitle: "StringReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::StringReader-klass. Representerar en läsare som läser tecken från en sträng. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2400
url: /sv/cpp/system.io/stringreader/
---
## StringReader class


Representerar en läsare som läser tecken från en sträng. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class StringReader : public System::IO::TextReader
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Close](./close/)() override | Stänger strömmen. |
| [Dispose](./dispose/)() override | Gör ingenting. |
| [Dispose](./dispose/)(bool) override | Gör ingenting. |
| [Peek](./peek/)() override | Läser ett enda tecken från strömmen utan att ändra strömmens position. |
| [Read](./read/)() override | Läser ett enskilt tecken från strömmen. |
| [Read](./read/)(ArrayPtr\<char_t\>, int, int) override | Läser det angivna antalet tecken från strömmen till den angivna teckenarrayen med start vid den angivna positionen. |
| [ReadLine](./readline/)() override | Läser tecken från strömmen tills slutet av den aktuella raden. |
| [ReadToEnd](./readtoend/)() override | Läser tecken från strömmen tills slutet av strömmen. |
| [StringReader](./stringreader/)(const String\&) | Skapar en ny instans av [StringReader](./)-klassen som läser tecken från den angivna strängen. |
## Se även

* Class [TextReader](../textreader/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
