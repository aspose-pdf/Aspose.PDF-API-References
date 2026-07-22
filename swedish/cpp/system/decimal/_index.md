---
title: "System::Decimal klass"
linktitle: "Decimal"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Decimal klass. Representerar ett decimaltal. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ i C++."
type: docs
weight: 2000
url: /sv/cpp/system/decimal/
---
## Decimal class


Representerar ett decimaltal. Denna typ bör allokeras på stacken och passeras till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Decimal
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Add](./add/)(const Decimal\&, const Decimal\&) | Lägger till två specificerade [Decimal](./) värden. |
| static [Ceiling](./ceiling/)(const Decimal\&) | Returnerar det minsta heltalsvärdet som är större än eller lika med det specificerade värdet. |
| static [Compare](./compare/)(const Decimal\&, const Decimal\&) | Bestämmer om värdet som representeras av det första [Decimal](./) objektet är mindre än, lika med eller större än värdet som representeras av det andra [Decimal](./) objektet. |
| [CompareTo](./compareto/)(const Decimal\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än, lika med eller större än värdet som representeras av det specificerade objektet. |
| [Decimal](./decimal/)() | Skapar en instans som representerar 0. |
| [Decimal](./decimal/)(std::int8_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::int16_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::int32_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::int64_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint8_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint16_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint32_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint64_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(float) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(double) | Skapar en instans som representerar det angivna värdet. |
| explicit [Decimal](./decimal/)(const std::string\&) | Skapar en instans som representerar ett värde vars strängrepresentation anges som en instans av std::string‑klassen. |
| [Decimal](./decimal/)(int32_t, int32_t, int32_t, bool, uint8_t) | Skapar ett [Decimal](./)-objekt från de angivna komponenterna. |
| [Decimal](./decimal/)(const Decimal\&) | Skapar en instans av klassen [Decimal](./) som representerar samma tal som det angivna [Decimal](./)-objektet. |
| [Decimal](./decimal/)(const ArrayPtr\<int32_t\>\&) | Skapar en instans av klassen [Decimal](./) från en heltalsarray som innehåller en binär representation. |
| [Decimal](./decimal/)(std::nullptr_t) | Kastar alltid ArgumentNullException. |
| [Decimal](./decimal/)(const number_type\&) | Skapar en instans av klassen [Decimal](./) som representerar det angivna värdet. |
| static [Divide](./divide/)(const Decimal\&, const Decimal\&) | Dividerar två angivna [Decimal](./)-värden. |
| [Equals](./equals/)(const Decimal\&) const | Avgör om värdena som representeras av det aktuella objektet och det angivna objektet är lika. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Avgör om värdena som representeras av det aktuella objektet och det angivna objektet är lika. |
| static [Equals](./equals/)(const Decimal\&, const Decimal\&) | Avgör om värdena som representeras av de angivna objekten är lika. |
| static [Floor](./floor/)(const Decimal\&) | Returnerar det största heltalsvärdet som är mindre än eller lika med det angivna värdet. |
| static [FromOACurrency](./fromoacurrency/)(int64_t) | [Convert](../convert/) det angivna OLE‑valutavärdet till motsvarande [Decimal](./)-värde. INTE IMPLEMENTERAT. |
| static [GetBits](./getbits/)(const Decimal\&) | Konverterar det angivna [Decimal](./)-objektet till den binära representationen av värdet det representerar. |
| static [GetBytes](./getbytes/)(const Decimal\&, const System::ArrayPtr\<uint8_t\>\&) | [Convert](../convert/) det angivna [Decimal](./)-värdet till en bytearray. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [GetTypeCode](./gettypecode/)() const | Hämtar objektets typkod. |
| static [Multiply](./multiply/)(const Decimal\&, const Decimal\&) | Multiplicerar två angivna [Decimal](./)-värden. |
| static [Negate](./negate/)(const Decimal\&) | Returnerar en ny instans av klassen [Decimal](./) som representerar ett värde som erhålls genom negation av värdet som representeras av det angivna objektet. |
| explicit [operator bool](./operatorbool/)() const | Konverterar värdet som representeras av det aktuella objektet till ett booleskt värde. |
| explicit [operator double](./operatordouble/)() const | Konverterar värdet som representeras av det aktuella objektet till ett dubbelprecisionsflyttal. |
| explicit [operator float](./operatorfloat/)() const | Konverterar värdet som representeras av det aktuella objektet till ett enkelprecisionsflyttal. |
| [operator!=](./operator!=/)(const Decimal\&) const | Avgör om värdena som representeras av det aktuella objektet och det angivna objektet inte är lika. |
| [operator!=](./operator!=/)(std::nullptr_t) const | Avgör om värdet som representeras av det aktuella objektet är annorlunda än 0. |
| [operator%](./operator%/)(const Decimal\&) const | Returnerar en ny instans av klassen [Decimal](./) som representerar ett värde som är resultatet av en modulo‑operation med värdena som representeras av det aktuella och det angivna objektet. |
| [operator%=](./operator%=/)(const Decimal\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av en modulo‑operation med värdena som representeras av det aktuella och det angivna objektet. |
| [operator*](./operator_/)(const Decimal\&) const | Returnerar en ny instans av klassen [Decimal](./) som representerar ett värde som är resultatet av multiplikation av värdena som representeras av det aktuella och det angivna objektet. |
| [operator*=](./operator_=/)(const Decimal\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av multiplikation av värdena som representeras av det aktuella och det angivna objektet. |
| [operator+](./operator+/)(const Decimal\&) const | Returnerar en ny instans av klassen [Decimal](./) som representerar ett värde som är summan av värdena som representeras av det aktuella och det angivna objektet. |
| [operator++](./operator++/)() | Ökar värdet som representeras av det aktuella objektet. |
| [operator+=](./operator+=/)(const Decimal\&) | Tilldelar det aktuella objektet ett nytt värde som är summan av värdena som representeras av det aktuella och det angivna objektet. |
| [operator-](./operator-/)(const Decimal\&) const | Returnerar en ny instans av klassen [Decimal](./) som representerar ett värde som är resultatet av subtraktion av värdet som representeras av det angivna objektet från värdet som representeras av det aktuella objektet. |
| [operator-](./operator-/)() const | Returnerar en ny instans av klassen [Decimal](./) som representerar ett värde som erhålls genom negation av värdet som representeras av det aktuella objektet. |
| [operator--](./operator--/)() | Minskar värdet som representeras av det aktuella objektet. |
| [operator-=](./operator-=/)(const Decimal\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av subtraktion av värdet som representeras av det angivna objektet från värdet som representeras av det aktuella objektet. |
| [operator/](./operator//)(const Decimal\&) const | Returnerar en ny instans av klassen [Decimal](./) som representerar ett värde som är resultatet av division av värdet som representeras av det aktuella objektet med värdet som representeras av det angivna objektet. |
| [operator/=](./operator/=/)(const Decimal\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av division av värdet som representeras av det aktuella objektet med värdet som representeras av det angivna objektet. |
| [operator<](./operator_/)(const Decimal\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än värdet som representeras av det angivna objektet. |
| [operator<=](./operator_=/)(const Decimal\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än eller lika med värdet som representeras av det angivna objektet. |
| [operator=](./operator=/)(const Decimal\&) | Tilldelar värdet som representeras av det angivna objektet till det aktuella objektet. |
| [operator==](./operator==/)(const Decimal\&) const | Avgör om värdena som representeras av det aktuella objektet och det angivna objektet är lika. |
| [operator==](./operator==/)(std::nullptr_t) const | Bestämmer om värdet som representeras av det aktuella objektet är 0. |
| [operator>](./operator_/)(const Decimal\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än värdet som representeras av det angivna objektet. |
| [operator>=](./operator_=/)(const Decimal\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna objektet. |
| static [Parse](./parse/)(const String\&) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av klassen [Decimal](./). |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av klassen [Decimal](./) med den angivna stilen. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av klassen [Decimal](./) med den angivna formatleverantören. |
| static [Parse](./parse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av klassen [Decimal](./) med den angivna stilen och formatleverantören. |
| static [Remainder](./remainder/)(const Decimal\&, const Decimal\&) | Beräknar resten efter division av två [Decimal](./)-värden. |
| static [Round](./round/)(const Decimal\&, MidpointRounding) | Avrundar det angivna värdet till närmaste heltal. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static [Round](./round/)(const Decimal\&, int, MidpointRounding) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter anger funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static [Subtract](./subtract/)(const Decimal\&, const Decimal\&) | Subtraherar ett angivet [Decimal](./)-värde från ett annat. |
| static [ToByte](./tobyte/)(Decimal) | Konverterar [Decimal](./)-värdet till ett osignerat 8-bitars heltalsvärde. |
| static [ToDouble](./todouble/)(Decimal) | Konverterar [Decimal](./)-värdet till ett dubbelprecisions-flyttal. |
| static [ToInt16](./toint16/)(Decimal) | Konverterar [Decimal](./)-värdet till ett signerat 16-bit heltal. |
| static [ToInt32](./toint32/)(Decimal) | Konverterar [Decimal](./)-värdet till ett signerat 32-bit heltal. |
| static [ToInt64](./toint64/)(Decimal) | Konverterar [Decimal](./)-värdet till ett signerat 64-bit heltal. |
| static [ToOACurrency](./tooacurrency/)(const Decimal\&) | [Convert](../convert/) det angivna [Decimal](./)-värdet till motsvarande OLE-valutavärde. INTE IMPLEMENTERAT. |
| static [ToSByte](./tosbyte/)(Decimal) | Konverterar [Decimal](./)-värdet till ett signerat 8-bit heltal. |
| static [ToSingle](./tosingle/)(Decimal) | Konverterar [Decimal](./)-värdet till ett enkelprecisions-flyttal. |
| [ToStdString](./tostdstring/)() const | Returnerar en instans av std::string som innehåller strängrepresentationen av värdet som objektet representerar. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av värdet som objektet representerar. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Konverterar aktuellt objekt till en sträng med hjälp av kultur-specifik formatinformation. |
| [ToString](./tostring/)(const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const Decimal\&, std::nullptr_t) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Konverterar aktuellt objekt till dess strängrepresentation med det angivna strängformatet och kultur-specifik formatinformation som tillhandahålls av det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| [ToStringInternal](./tostringinternal/)() const | Returnerar strängrepresentationen av värdet som objektet representerar. För internt bruk. |
| static [ToUInt16](./touint16/)(Decimal) | Konverterar [Decimal](./)-värdet till ett osignerat 16-bit heltal. |
| static [ToUInt32](./touint32/)(Decimal) | Konverterar [Decimal](./)-värdet till ett osignerat 32-bit heltal. |
| static [ToUInt64](./touint64/)(Decimal) | Konverterar [Decimal](./)-värdet till ett osignerat 64-bit heltal. |
| static [Truncate](./truncate/)(const Decimal\&) | Returnerar [Decimal](./)-objektet som representerar ett värde vars heltalsdel är lika med den för värdet som representeras av det angivna [Decimal](./)-objektet, där alla bråktal har kasserats. |
| static [TryParse](./tryparse/)(const String\&, Decimal\&) | Konverterar den angivna strängen som innehåller en siffers strängrepresentation till motsvarande [Decimal](./)-värde. |
| static [TryParse](./tryparse/)(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) | Konverterar den angivna strängen som innehåller en siffers strängrepresentation till motsvarande [Decimal](./)-värde med den angivna formateringsinformationen och talstilen. |
| static [Type](./type/)() | Returnerar en referens till [TypeInfo](../typeinfo/)-objektet som representerar typinformationen för [Decimal](./)-klassen. |
| [~Decimal](./~decimal/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [MaxValue](./maxvalue/) | Representerar det största tal som kan representeras av [Decimal](./)-klassen. |
| static [MinusOne](./minusone/) | Representerar talet -1. |
| static [MinValue](./minvalue/) | Representerar det minsta tal som kan representeras av [Decimal](./)-klassen. |
| static [One](./one/) | Representerar talet 1. |
| static [Zero](./zero/) | Representerar talet 0. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [number_type](./number_type/) | Ett alias för Detail::decimal_number_type. |
## Anmärkningar



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
This code example produces the following output:
-79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
