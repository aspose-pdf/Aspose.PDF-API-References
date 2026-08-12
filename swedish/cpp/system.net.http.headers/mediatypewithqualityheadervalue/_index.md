---
title: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue klass"
linktitle: "MediaTypeWithQualityHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::MediaTypeWithQualityHeaderValue klass. Representerar en MIME-typ med en extra kvalitetsfaktor i ett värde av ''Content-Type''-headern. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue class


Representerar en MIME-typ med en extra kvalitetsfaktor i ett värde av 'Content-Type'-headern. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Quality](./get_quality/)() | RTTI-information. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | Skapar en ny instans. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String) | Skapar en ny instans. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)(String, double) | Skapar en ny instans. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [MediaTypeWithQualityHeaderValue](./). |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Ställer in ett kvalitetsvärde. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<MediaTypeWithQualityHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [MediaTypeWithQualityHeaderValue](./). |
## Se även

* Class [MediaTypeHeaderValue](../mediatypeheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
