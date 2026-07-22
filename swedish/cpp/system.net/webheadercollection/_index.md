---
title: "System::Net::WebHeaderCollection-klass"
linktitle: "WebHeaderCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebHeaderCollection-klass. Representerar samlingen av protokollhuvuden. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3600
url: /sv/cpp/system.net/webheadercollection/
---
## WebHeaderCollection class


Representerar samlingen av protokollhuvuden. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class WebHeaderCollection : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(String, String) | Lägger till det angivna paret av rubriknamn och rubrikvärde i samlingen. |
| [Add](./add/)(HttpResponseHeader, String) | Lägger till det angivna paret av rubriken och rubrikvärdet i samlingen. |
| [Add](./add/)(HttpRequestHeader, String) | Lägger till det angivna paret av rubriken och rubrikvärdet i samlingen. |
| [AllKeys](./allkeys/)() | Returnerar en samling av rubriknamn som lagras i samlingen. |
| [get_Count](./get_count/)() const | Returnerar antalet element i samlingen. |
| [get_Keys](./get_keys/)() | Returnerar en samling av rubriknamn som lagras i samlingen. |
| [GetKey](./getkey/)(int) | Returnerar en nyckel på det angivna indexet. |
| [GetValues](./getvalues/)(String) | Returnerar samlingen av rubrikvärden. |
| [idx_get](./idx_get/)(HttpRequestHeader) | Hämtar rubrikvärdet med den angivna förfrågningsrubriken. |
| [idx_get](./idx_get/)(HttpResponseHeader) | Hämtar rubrikvärdet med den angivna svarsrubriken. |
| [idx_get](./idx_get/)(String) | Hämtar rubrikvärdet med det angivna rubriknamnet. |
| [idx_set](./idx_set/)(HttpRequestHeader, String) | Ställer in rubrikvärdet för den angivna rubriken. |
| [idx_set](./idx_set/)(HttpResponseHeader, String) | Ställer in rubrikvärdet med den angivna svarsrubriken. |
| [idx_set](./idx_set/)(String, String) | Ställer in rubrikvärdet med det angivna rubriknamnet. |
| static [IsRestricted](./isrestricted/)(const String\&) | Testar om den angivna HTTP-rubriken kan ställas in för förfrågan. |
| [Remove](./remove/)(String) | Tar bort rubriken med det angivna rubriknamnet. |
| [Remove](./remove/)(HttpResponseHeader) | Tar bort den angivna svarsrubriken. |
| [Remove](./remove/)(HttpRequestHeader) | Tar bort den angivna förfrågningsrubriken. |
| [Set](./set/)(String, String) | Ställer in värdet för den angivna headern. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| [WebHeaderCollection](./webheadercollection/)() | Skapar en ny instans. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
