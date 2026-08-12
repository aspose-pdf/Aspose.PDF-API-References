---
title: "System::Guid-klass"
linktitle: "Guid"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Guid-klass. Representerar en globalt unik identifierare. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ i C++."
type: docs
weight: 3100
url: /sv/cpp/system/guid/
---
## Guid class


Representerar en globalt unik identifierare. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Guid
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CompareTo](./compareto/)(const Guid\&) const | Utför aritmetisk jämförelse av GUID:erna som representeras av det aktuella och det angivna objektet. |
| [Equals](./equals/)(const Guid\&) const | Avgör om GUID:erna som representeras av det aktuella och det angivna objektet är lika. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [Guid](./guid/)() | Skapar ett objekt som representerar ett GUID bestående av enbart nollor. |
| [Guid](./guid/)(const ArrayPtr\<uint8_t\>\&) | Skapar ett objekt som representerar ett GUID specificerat som en array av osignerade 8-bitars heltalsvärden. |
| [Guid](./guid/)(const System::Details::ArrayView\<uint8_t\>\&) | Skapar ett objekt som representerar ett GUID specificerat som en array‑vy av osignerade 8-bitars heltalsvärden. |
| [Guid](./guid/)(const String\&) | Skapar ett objekt som representerar ett GUID specificerat som en sträng. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) | Skapar en instans av [Guid](./) klass från de specificerade GUID‑komponenterna. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) | Skapar en instans av [Guid](./) klass från de specificerade GUID‑komponenterna. |
| [Guid](./guid/)(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Skapar en instans av [Guid](./) klass från de specificerade osignerade heltalen och byte‑värdena. |
| [Guid](./guid/)(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) | Skapar en instans av [Guid](./) klass från de specificerade osignerade heltalen och byte‑värdena. |
| [Guid](./guid/)(const Guid\&) | Skapar ett objekt som representerar samma GUID som det specificerade objektet. |
| static [NewGuid](./newguid/)() | Genererar ett nytt GUID och returnerar ett [Guid](./) objekt som representerar det. |
| [operator!=](./operator!=/)(const Guid\&) const | Avgör om GUID:erna som representeras av det aktuella och det angivna objektet inte är lika. |
| [operator=](./operator=/)(const Guid\&) | Tilldelar det aktuella objektet GUID‑värdet som representeras av det specificerade [Guid](./) objektet. |
| [operator==](./operator==/)(const Guid\&) const | Avgör om GUID:erna som representeras av det aktuella och det angivna objektet är lika. |
| static [Parse](./parse/)(const String\&) | Konverterar den specificerade strängrepresentationen av ett GUID till ett motsvarande [Guid](./) objekt. |
| [ToByteArray](./tobytearray/)() const | Konverterar GUID‑et som representeras av det aktuella objektet till en array av byte. |
| [ToString](./tostring/)() const | Konverterar GUID‑et som representeras av det aktuella objektet till dess strängrepresentation. |
| [ToString](./tostring/)(const String\&) const | Konverterar GUID‑et som representeras av det aktuella objektet till dess strängrepresentation med det specificerade strängformatet. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const | Konverterar GUID‑et som representeras av det aktuella objektet till dess strängrepresentation med det specificerade strängformatet och kultur. |
| static [TryParse](./tryparse/)(const String\&, Guid\&) | Försöker konvertera den specificerade strängen till ett [Guid](./) objekt. |
| [~Guid](./~guid/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | Representerar ett GUID som har värdet 0. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
