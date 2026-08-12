---
title: "System::Collections::Generic::KeyValuePair klass"
linktitle: "KeyValuePair"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::KeyValuePair-klass. Par av nyckel och värde. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ i C++."
type: docs
weight: 2900
url: /sv/cpp/system.collections.generic/keyvaluepair/
---
## KeyValuePair class


Par av nyckel och värde. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Key](./get_key/)() const | Hämtar nyckel. |
| [get_Value](./get_value/)() const | Hämtar värde. |
| [GetHashCode](./gethashcode/)() const | Beräknar nyckel‑värde‑parens hash genom att xorra nyckelns och värdets hashvärden. |
| [IsNull](./isnull/)() const | Returnerar alltid falskt. |
| [KeyValuePair](./keyvaluepair/)() | Noll‑nyckel‑värde‑par‑initialiserare. |
| [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
| [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Typkonverteringskonstruktor. |
| [operator<](./operator_/)(const KeyValuePair\&) const | Patch för klasser som ärver från [IComparer<KeyValuePair<TKey, TValue>>](../icomparer/), jämför ingenting. |
| [ToString](./tostring/)() const | Konverterar nyckel‑värde‑par till sträng. |

## Se även

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
