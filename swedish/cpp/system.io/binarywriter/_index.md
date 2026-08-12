---
title: "System::IO::BinaryWriter-klass"
linktitle: "BinaryWriter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::BinaryWriter-klass. Representerar en skrivare som skriver värden av primitiva typer till en byte‑ström. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.io/binarywriter/
---
## BinaryWriter class


Representerar en skrivare som skriver värden av primitiva typer till en byte‑ström. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class BinaryWriter : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BinaryWriter](./binarywriter/)(const StreamPtr\&, const EncodingPtr\&, bool) | Skapar en instans av [BinaryWriter](./)-klassen som skriver data till den angivna strömmen med den angivna kodningen. |
| [Close](./close/)() | Stänger det aktuella [BinaryWriter](./)-objektet och den underliggande utmatningsströmmen. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av det aktuella objektet och stänger den underliggande strömmen. |
| [Flush](./flush/)() | Spolar utmatningsströmmen. |
| [get_BaseStream](./get_basestream/)() | Returnerar utmatningsströmmen. |
| [Seek](./seek/)(int, System::IO::SeekOrigin) | Ställer in positionen för strömmen som representeras av det aktuella objektet. |
| virtual [Write](./write/)(uint8_t) | Skriver det angivna 8‑bitars osignerade heltalsvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(const ArrayPtr\<uint8_t\>\&, int, int) | Skriver det angivna delintervallet av byte från den angivna bytearrayen till utmatningsströmmen. |
| virtual [Write](./write/)(const ArrayPtr\<char_t\>\&, int, int) | Skriver det angivna delintervallet av UTF‑16‑tecken från den angivna teckenarrayen till utmatningsströmmen. |
| virtual [Write](./write/)(bool) | Skriver en enstaka byte med värdet 0 om **value** är 'true' och 1 om **value** är 'false' till utmatningsströmmen. |
| virtual [Write](./write/)(char16_t) | Skriver det angivna 16‑bitars breda teckenvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(int16_t) | Skriver det angivna 16‑bitars heltalsvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(int) | Skriver det angivna 32‑bitars heltalsvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(int64_t) | Skriver det angivna 64‑bitars heltalsvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(uint16_t) | Skriver det angivna 16‑bitars osignerade heltalsvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(uint32_t) | Skriver det angivna 32‑bitars osignerade heltalsvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(uint64_t) | Skriver det angivna 64‑bitars osignerade heltalsvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(float) | Skriver det angivna enkelprecisions‑flytande‑punktvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(double) | Skriver det angivna dubbelprecisions‑flytande‑punktvärdet till utmatningsströmmen. |
| virtual [Write](./write/)(const Decimal\&) | Skriver byte‑representationen av det angivna [Decimal](../../system/decimal/)-värdet till utmatningsströmmen. |
| virtual [Write](./write/)(const String\&) | Skriver en längdprefixad sträng i den aktuella kodningen till utmatningsströmmen. |
| virtual [Write](./write/)(const char_t *) | Skriver en längdprefixad sträng i den aktuella kodningen till utmatningsströmmen. |
| [~BinaryWriter](./~binarywriter/)() | Destruktor. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::IO](../)
* Library [Aspose.PDF for C++](../../)
