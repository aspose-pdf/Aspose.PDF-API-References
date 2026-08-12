---
title: "System::StringComparer-klass"
linktitle: "StringComparer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::StringComparer-klass. Jämför strängar med olika jämförelselägen. Objekt av den här klassen bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertion-fel. Omslut alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 6200
url: /sv/cpp/system/stringcomparer/
---
## StringComparer class


Jämför strängar med olika jämförelselägen. Objekt av den här klassen bör endast allokeras med hjälp av funktionen [System::MakeObject()](../makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertion-fel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Compare](./compare/)(args_type, args_type) const override | Jämför två strängar med de aktuella inställningarna. |
| static [Create](./create/)(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) | Skapar kulturspecifik jämförare. |
| [Equals](./equals/)(String, String) const override | Kontrollerar om två strängar är lika med de aktuella inställningarna. |
| static [get_CurrentCulture](./get_currentculture/)() | Singleton för jämförare med aktuell kultur. |
| static [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | Singleton för jämförare med aktuell kultur som ignorerar skiftläge. |
| static [get_InvariantCulture](./get_invariantculture/)() | Singleton för jämförare med invariant kultur. |
| static [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | Singleton för jämförare med invariant kultur som ignorerar skiftläge. |
| static [get_Ordinal](./get_ordinal/)() | Singleton för ordinal jämförare. |
| static [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | Singleton för ordinal jämförare som ignorerar skiftläge. |
| [GetHashCode](./gethashcode/)(String) const override | Hämtar strängens hash‑kod. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [args_type](./args_type/) | RTTI-information. |
## Se även

* Class [Object](../object/)
* Class [IComparer](../../system.collections.generic/icomparer/)
* Class [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
