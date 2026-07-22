---
title: "System::IO::TextReader klass"
linktitle: "TextReader"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::TextReader klass. En basklass för klasser som representerar läsare som läser sekvenser av tecken från olika källor. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.io/textreader/
---
## TextReader class


En basklass för klasser som representerar läsare som läser sekvenser av tecken från olika källor. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class TextReader : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Close](./close/)() | Stänger strömmen och frigör förvärvade resurser. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| virtual [Peek](./peek/)() | Läser ett enskilt tecken från strömmen utan att ändra strömmens läsmarkör. |
| virtual [Read](./read/)() | Läser ett enskilt tecken från strömmen. |
| virtual [Read](./read/)(ArrayPtr\<char_t\>, int, int) | Läser det angivna antalet tecken från strömmen och skriver dem till den angivna teckenarrayen med start vid den angivna positionen. |
| virtual [ReadBlock](./readblock/)(ArrayPtr\<char_t\>, int, int) | Läser det angivna maximala antalet tecken från den aktuella textläsaren och skriver data till en buffert, med start vid det angivna indexet. |
| virtual [ReadLine](./readline/)() | Läser tecken från strömmen tills slutet av den aktuella raden. |
| virtual [ReadToEnd](./readtoend/)() | Läser tecken från strömmen tills slutet av strömmen. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
