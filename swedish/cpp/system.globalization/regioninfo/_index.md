---
title: "System::Globalization::RegionInfo klass"
linktitle: "RegionInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::RegionInfo-klass. Tillhandahåller information om region. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2100
url: /sv/cpp/system.globalization/regioninfo/
---
## RegionInfo class


Tillhandahåller information om region. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class RegionInfo : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| virtual [get_CurrencyEnglishName](./get_currencyenglishname/)() const | Hämtar valutans engelska namn. |
| virtual [get_CurrencyNativeName](./get_currencynativename/)() const | Hämtar valutans inhemska namn. |
| virtual [get_CurrencySymbol](./get_currencysymbol/)() const | Hämtar valutasymbol. |
| static [get_CurrentRegion](./get_currentregion/)() | Hämtar region som är inställd i systemet. |
| virtual [get_DisplayName](./get_displayname/)() const | Hämtar fullständigt regionsnamn. |
| virtual [get_EnglishName](./get_englishname/)() const | Hämtar regionens engelska namn. |
| virtual [get_GeoId](./get_geoid/)() const | Hämtar unik identifierare för en region. |
| virtual [get_IsMetric](./get_ismetric/)() const | Kontrollerar om regionen använder metriska systemet. |
| virtual [get_ISOCurrencySymbol](./get_isocurrencysymbol/)() const | Hämtar ISO-valutasymbol. |
| virtual [get_Name](./get_name/)() const | Hämtar regionsnamn. |
| virtual [get_NativeName](./get_nativename/)() const | Hämtar inhemskt regionsnamn. |
| virtual [get_ThreeLetterISORegionName](./get_threeletterisoregionname/)() const | Hämtar 3‑bokstavig ISO-regionskod. |
| virtual [get_ThreeLetterWindowsRegionName](./get_threeletterwindowsregionname/)() const | Hämtar 3‑bokstavig [Windows](../../system.windows/)-regionskod. |
| virtual [get_TwoLetterISORegionName](./get_twoletterisoregionname/)() const | Hämtar 2‑bokstavig ISO-regionskod. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [operator=](./operator=/)(const RegionInfo\&) |  |
| [RegionInfo](./regioninfo/)(const String\&) | RTTI-information. |
| [RegionInfo](./regioninfo/)(int) | Konstruktor. |
| [RegionInfo](./regioninfo/)(const RegionInfo\&) |  |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
