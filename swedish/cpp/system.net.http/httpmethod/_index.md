---
title: "System::Net::Http::HttpMethod-klass"
linktitle: "HttpMethod"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::HttpMethod-klass. Representerar en HTTP‑metod. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.http/httpmethod/
---
## HttpMethod class


Representerar en HTTP‑metod. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekaren och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class HttpMethod : public System::IEquatable<System::SharedPtr<System::Net::Http::HttpMethod>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<HttpMethod\>) override | Bestämmer om de aktuella och angivna objekten är lika. |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static [get_Delete](./get_delete/)() | Returnerar HTTP‑metoden 'DELETE'. |
| static [get_Get](./get_get/)() | Returnerar HTTP‑metoden 'GET'. |
| static [get_Head](./get_head/)() | Returnerar HTTP‑metoden 'HEAD'. |
| [get_Method](./get_method/)() | Returnerar en strängrepresentation av HTTP‑metoden. |
| static [get_Options](./get_options/)() | Returnerar HTTP‑metoden 'OPTIONS'. |
| static [get_Post](./get_post/)() | Returnerar HTTP‑metoden 'POST'. |
| static [get_Put](./get_put/)() | Returnerar HTTP‑metoden 'PUT'. |
| static [get_Trace](./get_trace/)() | Returnerar HTTP‑metoden 'TRACE'. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| [HttpMethod](./httpmethod/)(String) | Skapar en ny instans. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
## Se även

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Net::Http](../)
* Library [Aspose.PDF for C++](../../)
