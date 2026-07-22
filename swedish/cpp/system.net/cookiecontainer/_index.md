---
title: "System::Net::CookieContainer class"
linktitle: "CookieContainer"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::CookieContainer class. Tillhandahåller en behållare för instanser av CookieCollection-klassen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.net/cookiecontainer/
---
## CookieContainer class


Tillhandahåller en behållare för instanser av CookieCollection-klassen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CookieContainer : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<Cookie\>) | Lägger till en cookie i samlingen. |
| [Add](./add/)(System::SharedPtr\<Cookie\>, bool) | Lägger till en cookie i samlingen. |
| [Add](./add/)(System::SharedPtr\<CookieCollection\>) | Kopierar cookies från den angivna samlingen till den aktuella. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) | Lägger till en cookie för den angivna URI:n. |
| [Add](./add/)(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) | Kopierar cookies från den angivna samlingen för den angivna URI:n till den aktuella samlingen. |
| [CookieContainer](./cookiecontainer/)() | Skapar en ny instans. |
| [CookieContainer](./cookiecontainer/)(int32_t) | Skapar en ny instans. |
| [CookieContainer](./cookiecontainer/)(int32_t, int32_t, int32_t) | Skapar en ny instans. |
| [CookieCutter](./cookiecutter/)(System::SharedPtr\<Uri\>, String, String, bool) | Kopierar cookies från den angivna HTTP-headern för den angivna URI:n. |
| [get_Capacity](./get_capacity/)() | Hämtar samlingens kapacitet. |
| [get_Count](./get_count/)() | Returnerar antalet objekt i samlingen. |
| [get_MaxCookieSize](./get_maxcookiesize/)() | Hämtar den maximala cookie‑storleken. |
| [get_PerDomainCapacity](./get_perdomaincapacity/)() | Hämtar samlingens kapacitet per domän. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>) | Returnerar en HTTP‑header som innehåller cookies som är associerade med den angivna URI:n. |
| [GetCookieHeader](./getcookieheader/)(System::SharedPtr\<Uri\>, String\&) | Returnerar en HTTP‑header som innehåller cookies som är associerade med den angivna URI:n. |
| [GetCookies](./getcookies/)(System::SharedPtr\<Uri\>) | Returnerar en samling cookies som är associerade med den angivna URI:n. |
| [InternalGetCookies](./internalgetcookies/)(System::SharedPtr\<Uri\>) | Returnerar en samling cookies som är associerade med den angivna URI:n. |
| [IsLocalDomain](./islocaldomain/)(String) | Kontrollerar om den angivna domänen är localhost. |
| [set_Capacity](./set_capacity/)(int32_t) | Ställer in samlingens kapacitet. |
| [set_MaxCookieSize](./set_maxcookiesize/)(int32_t) | Ställer in den maximala cookie‑storleken. |
| [set_PerDomainCapacity](./set_perdomaincapacity/)(int32_t) | Ställer in samlingens kapacitet per domän. |
| [SetCookies](./setcookies/)(System::SharedPtr\<Uri\>, String) | Kopierar cookies från den angivna headern till samlingen och associerar dem med den angivna URI:n. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | Den maximala cookie‑storleken. |
| static [DefaultCookieLimit](./defaultcookielimit/) | RTTI-information. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | Det maximala antalet objekt i samlingen per domän. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
