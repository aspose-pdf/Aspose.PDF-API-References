---
title: "System::Net::Http::Headers::ProductInfoHeaderValue klass"
linktitle: "ProductInfoHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::ProductInfoHeaderValue klass. Representerar en produkt eller en kommentar i ett värde för ''User-Agent''-huvudet. Objekt av den här klassen bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en System::SmartPtr‑pekare och använd den pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1800
url: /sv/cpp/system.net.http.headers/productinfoheadervalue/
---
## ProductInfoHeaderValue class


Representerar en produkt eller en kommentar i ett värde för 'User-Agent'-huvudet. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd den pekaren för att skicka den till funktioner som argument.

```cpp
class ProductInfoHeaderValue : public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| [get_Comment](./get_comment/)() | Returnerar en kommentar. |
| [get_Product](./get_product/)() | RTTI-information. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetProductInfoLength](./getproductinfolength/)(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [ProductInfoHeaderValue](./). |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [ProductInfoHeaderValue](./). |
| [ProductInfoHeaderValue](./productinfoheadervalue/)(String, String) | Skapar en ny instans. |
| [ProductInfoHeaderValue](./productinfoheadervalue/)(System::SharedPtr\<ProductHeaderValue\>) | Skapar en ny instans. |
| [ProductInfoHeaderValue](./productinfoheadervalue/)(String) | Skapar en ny instans. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<ProductInfoHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av klassen [ProductInfoHeaderValue](./). |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
