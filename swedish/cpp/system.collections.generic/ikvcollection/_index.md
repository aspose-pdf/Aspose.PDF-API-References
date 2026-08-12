---
title: "System::Collections::Generic::IKVCollection-klass"
linktitle: "IKVCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IKVCollection-klass. Gränssnitt för en behållare som innehåller nycklar eller värden i en dictionary-liknande behållare. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2500
url: /sv/cpp/system.collections.generic/ikvcollection/
---
## IKVCollection class


Gränssnitt för en behållare som innehåller nycklar eller värden i en dictionary-liknande behållare. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class IKVCollection : public System::Collections::Generic::IList<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | [KeyValuePair](../keyvaluepair/)-typ. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const T\&) override | Lägger till ett objekt i behållaren. |
| [Clear](./clear/)() override | Tar bort alla element från behållaren. |
| [Contains](./contains/)(const T\&) const override | Kontrollerar om objektet finns i behållaren. |
| virtual [get_Count](./get_count/)() const | Hämtar antalet element i behållaren. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Kontrollerar om behållaren är skrivskyddad. |
| virtual [GetEnumerator](./getenumerator/)() | RTTI-information. |
| virtual [idx_get](./idx_get/)(int) const | Getter-funktion. |
| [idx_set](./idx_set/)(int, T) override | Setter-funktion. |
| [IndexOf](./indexof/)(const T\&) const override | Hämtar index för objektet i behållaren. |
| [Insert](./insert/)(int, const T\&) override | Infogar objekt på angiven position. |
| [Remove](./remove/)(const T\&) override | Tar bort objektet från behållaren. |
| [RemoveAt](./removeat/)(int) override | Tar bort objektet på angiven position. |

## Se även

* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
