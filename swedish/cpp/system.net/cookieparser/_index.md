---
title: "System::Net::CookieParser klass"
linktitle: "CookieParser"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::CookieParser klass. Används för att tolka ett cookie‑huvud och skapa en instans av Cookie‑klassen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.net/cookieparser/
---
## CookieParser class


Används för att tolka ett cookie‑huvud och skapa en instans av [Cookie](../cookie/)-klassen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class CookieParser : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [CheckQuoted](./checkquoted/)(String) | Kontrollerar om den angivna strängen är omsluten av citationstecken. |
| [CookieParser](./cookieparser/)(String) | RTTI-information. |
| [Get](./get/)() | Returnerar en instans baserad på den angivna strängen. |
| [GetServer](./getserver/)() | Hämtar server‑cookien. |
| [GetString](./getstring/)() | Returnerar strängrepresentationen av ett cookie‑huvud. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
