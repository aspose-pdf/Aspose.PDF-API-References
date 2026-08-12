---
title: "System::Net::Http::Headers::NameValueHeaderValue-klass"
linktitle: "NameValueHeaderValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::NameValueHeaderValue-klass. Representerar ett nyckel/värde-par att använda i rubriker. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1400
url: /sv/cpp/system.net.http.headers/namevalueheadervalue/
---
## NameValueHeaderValue class


Representerar ett nyckel/värde-par att använda i rubriker. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekaren och använd pekaren för att skicka den till funktioner som argument.

```cpp
class NameValueHeaderValue : public virtual System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<Object\>) override | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static [Find](./find/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, String) | Hittar NameValueHeaderValue-klassens instans i en samling efter det angivna namnet. |
| [get_Name](./get_name/)() | Returnerar ett namn för den aktuella instansen. |
| [get_Value](./get_value/)() | Hämtar ett värde för den aktuella instansen. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetHashCode](./gethashcode/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Returnerar en hashkod för alla objekt i samlingen. |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [NameValueHeaderValue](./). |
| static [GetNameValueLength](./getnamevaluelength/)(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) | Konverterar en given sträng från det angivna indexet till en instans av klassen [NameValueHeaderValue](./). |
| static [GetNameValueListLength](./getnamevaluelistlength/)(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) | Konverterar en given sträng från det angivna indexet till samlingen av NameValueHeaderValue-klassens instanser och returnerar längden på den analyserade delsträngen. |
| static [GetValueLength](./getvaluelength/)(String, int32_t) | Returnerar längden på ett värde från det angivna indexet. |
| [NameValueHeaderValue](./namevalueheadervalue/)() | Skapar en ny instans. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String) | Skapar en ny instans. |
| [NameValueHeaderValue](./namevalueheadervalue/)(String, String) | Skapar en ny instans. |
| static [Parse](./parse/)(String) | Konverterar en given sträng till en instans av klassen [NameValueHeaderValue](./). |
| [set_Value](./set_value/)(String) | Ställer in ett värde för den aktuella instansen. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) | Returnerar en strängrepresentation av samlingen av NameValueHeaderValue-klassinstanser. |
| static [ToString](./tostring/)(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) | Returnerar en strängrepresentation av samlingen av NameValueHeaderValue-klassinstanser. |
| static [TryParse](./tryparse/)(String, System::SharedPtr\<NameValueHeaderValue\>\&) | Försöker konvertera en given sträng till en instans av [NameValueHeaderValue](./)-klassen. |
## Se även

* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
