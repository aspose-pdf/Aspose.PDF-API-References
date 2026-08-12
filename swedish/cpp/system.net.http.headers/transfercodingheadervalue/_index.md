---
title: "System::Net::Http::Headers::TransferCodingHeaderValue klass"
linktitle: "TransferCodingHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::TransferCodingHeaderValue klass. Representerar ett värde för ''Accept-Encoding''‑headern. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller assert‑fel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2400
url: /sv/cpp/system.net.http.headers/transfercodingheadervalue/
---
## TransferCodingHeaderValue class


Representerar ett värde för 'Accept-Encoding'-huvudet. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class TransferCodingHeaderValue : public virtual System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Parameters](./get_parameters/)() | Returnerar parametrarna. |
| [get_Value](./get_value/)() | RTTI-information. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetTransferCodingLength](./gettransfercodinglength/)(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [TransferCodingHeaderValue](./). |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [TransferCodingHeaderValue](./). |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)() | Skapar en ny instans. |
| [TransferCodingHeaderValue](./transfercodingheadervalue/)(String) | Skapar en ny instans. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<TransferCodingHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [TransferCodingHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
