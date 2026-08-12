---
title: "System::Net::PathList klass"
linktitle: "PathList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::PathList klass. Representerar listan av instanser av klassen CookieCollection. Objekt av denna klass bör endast allokeras med hjälp av funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3000
url: /sv/cpp/system.net/pathlist/
---
## PathList class


Representerar listan av instanser av klassen [CookieCollection](../cookiecollection/). Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class PathList : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)() | Skapar en ny instans. |
| [get_Count](./get_count/)() const | Returnerar antalet objekt. |
| [get_SyncRoot](./get_syncroot/)() const | Returnerar objektet genom vilket samlingen synkroniseras. |
| [GetCookiesCount](./getcookiescount/)() | Returnerar antalet kakor för alla samlingsobjekt. |
| [GetEnumerator](./getenumerator/)() | Returnerar enumeratorn för den aktuella samlingen. |
| [idx_get](./idx_get/)(String) | Hämtar cookie-samlingen enligt angiven sökväg. |
| [idx_set](./idx_set/)(String, System::SharedPtr\<CookieCollection\>) | Ställer in cookie-samlingen enligt angiven sökväg. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
