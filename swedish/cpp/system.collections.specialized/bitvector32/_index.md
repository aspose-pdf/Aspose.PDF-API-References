---
title: "System::Collections::Specialized::BitVector32 klass"
linktitle: "BitVector32"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Specialized::BitVector32 klass. Tillhandahåller en enkel lätt bitvektor med enkel heltals‑ eller Boolean‑åtkomst till ett 32‑bitars lagringsutrymme i C++."
type: docs
weight: 100
url: /sv/cpp/system.collections.specialized/bitvector32/
---
## BitVector32 class


Tillhandahåller en enkel lätt bitvektor med enkel heltals‑ eller [Boolean](../../system/boolean/)‑åtkomst till ett 32‑bitars lagringsutrymme.

```cpp
class BitVector32
```

## Nested classes

* Class [Section](./section/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BitVector32](./bitvector32/)() | Initierar en ny tom instans av [BitVector32](./). |
| [BitVector32](./bitvector32/)(int32_t) | Initierar en ny instans av strukturen [BitVector32](./) med den angivna interna datan. |
| [BitVector32](./bitvector32/)(const BitVector32\&) | Initierar en ny instans av strukturen [BitVector32](./) med informationen i det angivna värdet. |
| static [CreateMask](./createmask/)() | Skapar den första masken i en serie. |
| static [CreateMask](./createmask/)(int32_t) | Skapar nästa mask i en serie. |
| static [CreateSection](./createsection/)(int16_t) | Skapar den första sektionen i en serie, med det angivna maximala värdet. |
| static [CreateSection](./createsection/)(int16_t, BitVector32::Section) | Skapar nästa sektion i en serie, med det angivna maximala värdet. |
| [Equals](./equals/)(const BitVector32\&) | Bestämmer om det angivna objektet är detsamma som det aktuella. |
| [get_Data](./get_data/)() | returnerar den råa data som lagras i denna bitvektor... |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [idx_get](./idx_get/)(int32_t) | Hämtar ett värde som indikerar om alla angivna bitar är satta. |
| [idx_get](./idx_get/)(BitVector32::Section) | Hämtar värdet för den angivna sektionen. |
| [idx_set](./idx_set/)(int32_t, bool) | Ställer in ett värde som indikerar om alla angivna bitar är satta. |
| [idx_set](./idx_set/)(BitVector32::Section, int32_t) | Ställer in värdet för den angivna sektionen. |
| static [ToString](./tostring/)(const BitVector32\&) | Konverterar värdet som representeras av värdeparametern till en sträng. |
| [ToString](./tostring/)() const | Konverterar värdet som representeras av det aktuella objektet till en sträng. |
## Se även

* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
