---
title: "System::Net::Http::Headers::TransferCodingWithQualityHeaderValue klass"
linktitle: "TransferCodingWithQualityHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::TransferCodingWithQualityHeaderValue klass. Representerar ett värde med en extra kvalitet för ''Accept-Encoding''-huvudet. Objekt av den här klassen bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en System::SmartPtr‑pekare och använd den pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2500
url: /sv/cpp/system.net.http.headers/transfercodingwithqualityheadervalue/
---
## TransferCodingWithQualityHeaderValue class


Representerar ett värde med en extra kvalitet för 'Accept-Encoding'-huvudet. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class TransferCodingWithQualityHeaderValue : public System::Net::Http::Headers::TransferCodingHeaderValue
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Quality](./get_quality/)() | RTTI-information. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [TransferCodingWithQualityHeaderValue](./). |
| [set_Quality](./set_quality/)(Nullable\<double\>) | Ställer in kvalitetsvärdet för 'Accept-Encoding'-huvudet. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)() | Skapar en ny instans. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)(String) | Skapar en ny instans. |
| [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)(String, double) | Skapar en ny instans. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<TransferCodingWithQualityHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [TransferCodingWithQualityHeaderValue](./). |
## Se även

* Class [TransferCodingHeaderValue](../transfercodingheadervalue/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
