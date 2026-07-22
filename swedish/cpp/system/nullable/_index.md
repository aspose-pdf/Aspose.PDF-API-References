---
title: "System::Nullable klass"
linktitle: "Nullable"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Nullable klass. Framåtredeklaration i C++."
type: docs
weight: 4800
url: /sv/cpp/system/nullable/
---
## Nullable class


Framåtriktad deklaration.

```cpp
template<typename T>class Nullable
```


| Parameter | Beskrivning |
| --- | --- |
| T | Den underliggande värdetypen som utökas av klassen [Nullable](./) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(const T1\&) const | Avgör om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](./)-objektet. |
| [get_HasValue](./get_hasvalue/)() const | Avgör om det aktuella objektet representerar något värde. |
| [get_Value](./get_value/)() const | Returnerar en kopia av värdet som representeras av det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [GetValueOrDefault](./getvalueordefault/)(T) | Returnerar värdet som representeras av det aktuella objektet eller det angivna värdet om värdet som representeras av det aktuella objektet är null. |
| [GetValueOrDefault](./getvalueordefault/)() |  |
| [IsNull](./isnull/)() const | Avgör om det aktuella objektet representerar ett null‑värde. |
| [Nullable](./nullable/)() | Skapar en instans som representerar ett null‑värde. |
| [Nullable](./nullable/)(std::nullptr_t) | Skapar en instans som representerar null. |
| [Nullable](./nullable/)(const T1\&) | Skapar en instans av klassen [Nullable](./) som representerar det angivna värdet konverterat (om nödvändigt) till värdet av den underliggande typen T. |
| [Nullable](./nullable/)(const Nullable\<T1\>\&) | Skapar en instans som representerar ett värde som representeras av det angivna [Nullable](./)-objektet. Det angivna nullable‑objektet kan representera ett värde av en annan typ än den underliggande typen för den skapade instansen, varvid det representerade värdet konverteras till en värdetyp T. |
| [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<bool()>\&, bool) const | Hjälpfunktion för att kontrollera om både detta och **other** inte är null och anropa ett lambda‑uttryck i så fall. Används i implementationer. |
| [operator const T &](./operatorconstt&/)() const | Returnerar en konstant referens till värdet som representeras av det aktuella objektet. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Avgör om värdet som representeras av det aktuella objektet inte är null. |
| [operator!=](./operator!=/)(const T1\&) const | Avgör om värdet som representeras av det aktuella objektet inte är lika med det angivna värdet. |
| [operator!=](./operator!=/)(const Nullable\<T1\>\&) const | Avgör om värdet som representeras av det aktuella objektet inte är lika med värdet som representeras av det angivna [Nullable](./)-objektet. |
| [operator&=](./operator&=/)(bool) | Tillämpar [operator&=()](./operator&=/) på värdet som representeras av det aktuella objektet med det angivna värdet som argument på högersidan. |
| [operator+](./operator+/)(std::nullptr_t) const | Returnerar en standardkonstruktad instans av klassen Nullable<T>. |
| [operator+](./operator+/)(const T1\&) const | Adderar nullable‑ och icke‑nullable‑värden. |
| [operator+](./operator+/)(const Nullable\<T1\>\&) const | Adderar nullable‑värden. |
| [operator+=](./operator+=/)(std::nullptr_t) | Återställer det aktuella objektet så att det representerar ett null‑värde. |
| [operator+=](./operator+=/)(const T1\&) | Tillämpar [operator+=()](./operator+=/) på värdet som representeras av det aktuella objektet med det angivna värdet som argument på högersidan. |
| [operator+=](./operator+=/)(const Nullable\<T1\>\&) | Tillämpar [operator+=()](./operator+=/) på värdet som representeras av det aktuella objektet med värdet som representeras av det angivna [Nullable](./)-objektet som argument på högersidan. |
| [operator-](./operator-/)(T1) const | Subtraherar nullable‑ och null‑pekande värden. |
| [operator-](./operator-/)(const T1\&) const | Subtraherar nullable‑ och icke‑nullable‑värden. |
| [operator-](./operator-/)(const Nullable\<T1\>\&) const | Subtraherar nullable‑värden. |
| [operator-=](./operator-=/)(T1) | Returnerar en instans av klassen [Nullable](./) som representerar ett null‑värde. |
| [operator-=](./operator-=/)(const T1\&) | Applicerar [operator-=()](./operator-=/) på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidig argument. |
| [operator-=](./operator-=/)(const Nullable\<T1\>\&) | Applicerar [operator-=()](./operator-=/) på värdet som representeras av det aktuella objektet med värdet som representeras av det angivna [Nullable](./)-objektet som ett högersidig argument. |
| [operator<](./operator_/)(std::nullptr_t) const | Returnerar alltid falskt. |
| [operator<](./operator_/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än det angivna värdet genom att tillämpa [operator<()](./operator_/) på dessa värden. |
| [operator<](./operator_/)(const Nullable\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än värdet som representeras av det angivna [Nullable](./)-objektet genom att tillämpa [operator<()](./operator_/) på dessa värden. |
| [operator<=](./operator_=/)(std::nullptr_t) const | Returnerar alltid falskt. |
| [operator<=](./operator_=/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än eller lika med det angivna värdet genom att tillämpa [operator<=()](./operator_=/) på dessa värden. |
| [operator<=](./operator_=/)(const Nullable\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än eller lika med värdet som representeras av det angivna [Nullable](./)-objektet genom att tillämpa [operator<=()](./operator_=/) på dessa värden. |
| [operator=](./operator=/)(std::nullptr_t) | Tilldelar ett null till det aktuella objektet. |
| [operator=](./operator=/)(const T1\&) | Ersätter objektets för närvarande representerade värde med det angivna. |
| [operator=](./operator=/)(const Nullable\<T1\>\&) | Ersätter objektets för närvarande representerade värde med det angivna. |
| [operator==](./operator==/)(std::nullptr_t) const | Bestämmer om värdet som representeras av det aktuella objektet är null. |
| [operator==](./operator==/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är lika med det angivna värdet. |
| [operator==](./operator==/)(const Nullable\<T1\>\&) const | Avgör om värdet som representeras av det aktuella objektet är lika med värdet som representeras av det angivna [Nullable](./)-objektet. |
| [operator>](./operator_/)(std::nullptr_t) const | Returnerar alltid falskt. |
| [operator>](./operator_/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än det angivna värdet genom att tillämpa [operator>()](./operator_/) på dessa värden. |
| [operator>](./operator_/)(const Nullable\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än värdet som representeras av det angivna [Nullable](./)-objektet genom att tillämpa [operator>()](./operator_/) på dessa värden. |
| [operator>=](./operator_=/)(std::nullptr_t) const | Returnerar alltid falskt. |
| [operator>=](./operator_=/)(const T1\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna objektet genom att tillämpa [operator>=()](./operator_=/) på dessa värden. |
| [operator>=](./operator_=/)(const Nullable\<T1\>\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna [Nullable](./)-objektet genom att tillämpa [operator>=()](./operator_=/) på dessa värden. |
| [operator | =](./operator_=/)(bool) | Applicerar [operator | =()](./operator_=/) på värdet som representeras av det aktuella objektet med det angivna värdet som ett högersidig argument. |
| [reset](./reset/)() | Sätter det för närvarande representerade värdet till null. |
| [set_Value](./set_value/)(const T\&) | Sätter ett nytt värde till nullable‑objektet. |
| [ToString](./tostring/)() const | Konverterar värdet som representeras av det aktuella objektet till en sträng. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ValueType](./valuetype/) | Ett alias för en typ av värdet som representeras av den här klassen. |
## Anmärkningar


Representerar ett värde av den angivna typen som kan tilldelas null. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig klassen [System::SmartPtr](../smartptr/) för att hantera objekt av denna typ.

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
