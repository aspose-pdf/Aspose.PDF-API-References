---
title: "System::TimeSpan-klass"
linktitle: "TimeSpan"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::TimeSpan-klass. Representerar ett tidsintervall. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ i C++."
type: docs
weight: 6400
url: /sv/cpp/system/timespan/
---
## TimeSpan class


Representerar ett tidsintervall. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
class TimeSpan
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Returnerar en ny instans av [TimeSpan](./) klass som representerar ett tidsintervall som är summan av tidsintervallen som representeras av det aktuella och det specificerade objektet. |
| static [Compare](./compare/)(TimeSpan, TimeSpan) | Jämför två [TimeSpan](./) objekt. |
| [CompareTo](./compareto/)(TimeSpan) const | Jämför det aktuella och de specificerade objekten. |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Jämför det aktuella och de specificerade objekten. |
| [Duration](./duration/)() const | Returnerar en ny instans av [TimeSpan](./) objekt vars värde är det absoluta värdet av det aktuella objektet. |
| [Equals](./equals/)(TimeSpan) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det specificerade objektet. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det specificerade objektet. |
| static [Equals](./equals/)(TimeSpan, TimeSpan) | Returnerar true om de specificerade objekten representerar samma tidsintervall, annars - false. |
| static [FromDays](./fromdays/)(double) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det specificerade intervallet. |
| static [FromHours](./fromhours/)(double) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det specificerade intervallet. |
| static [FromMilliseconds](./frommilliseconds/)(double) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det specificerade intervallet. |
| static [FromMinutes](./fromminutes/)(double) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det specificerade intervallet. |
| static [FromSeconds](./fromseconds/)(double) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det specificerade intervallet. |
| static [FromTicks](./fromticks/)(int64_t) | Returnerar ett nytt [TimeSpan](./) objekt som representerar det specificerade intervallet. |
| [get_Days](./get_days/)() const | Returnerar dagkomponenten av tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| [get_Hours](./get_hours/)() const | Returnerar timkomponenten av tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| [get_Milliseconds](./get_milliseconds/)() const | Returnerar millisekundkomponenten av tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| [get_Minutes](./get_minutes/)() const | Returnerar minutkomponenten av tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| [get_Seconds](./get_seconds/)() const | Returnerar sekundkomponenten av tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| [get_Ticks](./get_ticks/)() const | Returnerar antalet 100-nanosekundintervall som utgör tidsintervallet som representeras av det aktuella [TimeSpan](./) objektet. |
| [get_TotalDays](./get_totaldays/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av dagar. |
| [get_TotalHours](./get_totalhours/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av timmar. |
| [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av millisekunder. |
| [get_TotalMinutes](./get_totalminutes/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av minuter. |
| [get_TotalSeconds](./get_totalseconds/)() const | Returnerar värdet av det aktuella [TimeSpan](./) objektet uttryckt i hela och bråkdelar av sekunder. |
| [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [IsNull](./isnull/)() const |  |
| [Negate](./negate/)() const | Returnerar en ny instans av [TimeSpan](./) objekt som representerar det negerade värdet som representeras av det aktuella [TimeSpan](./) objektet. |
| [operator!=](./operator!=/)(TimeSpan) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet inte är lika med tidsintervallet som representeras av det specificerade objektet. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Returnerar en ny instans av [TimeSpan](./) klass som representerar ett tidsintervall som är summan av tidsintervallen som representeras av det aktuella och det specificerade objektet. |
| [operator+](./operator+/)() const | Returnerar sig själv. |
| [operator+=](./operator+=/)(TimeSpan) | Tilldelar det aktuella objektet tidsintervallet som är summan av tidsintervallet som representeras av det aktuella och det specificerade objektet. |
| [operator-](./operator-/)(TimeSpan) const | Returnerar en ny instans av klassen [TimeSpan](./) som representerar ett tidsintervall som är resultatet av subtraktionen av tidsintervallet som representeras av det angivna objektet från tidsintervallet som representeras av det aktuella objektet. |
| [operator-](./operator-/)() const | Returnerar en ny instans av [TimeSpan](./) objekt som representerar det negerade värdet som representeras av det aktuella [TimeSpan](./) objektet. |
| [operator-=](./operator-=/)(TimeSpan) | Tilldelar det aktuella objektet tidsintervallet som är resultatet av subtraktionen av tidsintervallet som representeras av det angivna objektet från tidsintervallet som representeras av det aktuella objektet. |
| [operator/](./operator//)(double) const |  |
| [operator/](./operator//)(TimeSpan) const |  |
| [operator/=](./operator/=/)(double) |  |
| [operator<](./operator_/)(TimeSpan) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet är kortare än tidsintervallet som representeras av det angivna objektet. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(TimeSpan) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet är kortare än eller lika med tidsintervallet som representeras av det angivna objektet. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator=](./operator=/)(const TimeSpan\&) | Ställer in tidsintervallet som representeras av det angivna [TimeSpan](./)-objektet till det aktuella [TimeSpan](./)-objektet. |
| [operator==](./operator==/)(TimeSpan) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det specificerade objektet. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(TimeSpan) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet är längre än tidsintervallet som representeras av det angivna objektet. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(TimeSpan) const | Bestämmer om tidsintervallet som representeras av det aktuella objektet är längre än eller lika med tidsintervallet som representeras av det angivna objektet. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med den angivna formatleverantören. |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) |  |
| static [Parse](./parse/)(const String\&, std::nullptr_t) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med de angivna formaten, formatleverantören och stilarna. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med det angivna formatet, formatleverantören och stilarna. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles) |  |
| static [ParseExact](./parseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles) |  |
| [Subtract](./subtract/)(TimeSpan) const | Returnerar en ny instans av klassen [TimeSpan](./) som representerar ett tidsintervall som är resultatet av subtraktionen av tidsintervallet som representeras av det angivna objektet från tidsintervallet som representeras av det aktuella objektet. |
| [TimeSpan](./timespan/)() | Skapar ett [TimeSpan](./)-objekt som representerar ett nolltidsintervall. |
| explicit [TimeSpan](./timespan/)(int64_t) | Skapar en instans av klassen [TimeSpan](./) som representerar det angivna tidsintervallet. |
| [TimeSpan](./timespan/)(int, int, int) | Skapar en instans av klassen [TimeSpan](./) som representerar tidsintervallet som är lika med summan av det angivna antalet timmar, minuter och sekunder. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | Skapar en instans av klassen [TimeSpan](./) som representerar tidsintervallet som är lika med summan av det angivna antalet timmar, minuter, sekunder och millisekunder. |
| [TimeSpan](./timespan/)(const TimeSpan\&) | Skapar ett [TimeSpan](./)-objekt som representerar tidsintervallet som är lika med tidsintervallet som representeras av det angivna [TimeSpan](./)-objektet. |
| [ToString](./tostring/)() const | Returnerar strängrepresentationen av tidsintervallet som representeras av det aktuella objektet. |
| [ToString](./tostring/)(const String\&) const | Konverterar värdet av det aktuella objektet till motsvarande strängrepresentation, med det angivna formatet. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Konverterar värdet av det aktuella objektet till motsvarande strängrepresentation, med det angivna formatet och formatleverantören. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const |  |
| [ToString](./tostring/)(const String\&, std::nullptr_t) const |  |
| static [TryParse](./tryparse/)(const String\&, TimeSpan\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt och returnerar konverteringsresultatet. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med den angivna formatleverantören och returnerar konverteringsresultatet. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParse](./tryparse/)(const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med de angivna formaten och formatleverantören, och returnerar konverteringsresultatet. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med det angivna formatet, formatleverantören och stilarna, och returnerar konverteringsresultatet. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med de angivna formaten, formatleverantören och stilarna, och returnerar konverteringsresultatet. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) | Konverterar en sträng till motsvarande [TimeSpan](./)-objekt med det angivna formatet och formatleverantören, och returnerar konverteringsresultatet. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) |  |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, std::nullptr_t, TimeSpan\&) |  |
| static [Type](./type/)() | Returnerar ett [TypeInfo](../typeinfo/) objekt som representerar [TimeSpan](./) strukturen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [MaxValue](./maxvalue/) | Det [TimeSpan](./) objektet som representerar det längsta möjliga intervallet. |
| static [MinValue](./minvalue/) | /// Det [TimeSpan](./) objektet som representerar det kortaste möjliga intervallet. |
| static constexpr [TicksPerDay](./ticksperday/) | Antalet 100‑nanosekundintervall på en dag (24‑timmarsintervall). |
| static constexpr [TicksPerHour](./ticksperhour/) | Antalet 100‑nanosekundintervall på en timme. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Antalet 100‑nanosekundintervall på en millisekund. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Antalet 100‑nanosekundintervall på en minut. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Antalet 100‑nanosekundintervall på en sekund. |
| static [Zero](./zero/) | Det [TimeSpan](./) objektet som representerar nollintervall. |
## Anmärkningar



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
This code example produces the following output:
Number of ticks: 260928000000000
Number of milliseconds: 0
Total number of milliseconds: 2.60928e+10
Number of minutes: 0
Total number of minutes: 434880
Number of hours: 0
Total number of hours: 0
Number of days: 302
Total number of days: 302
*/
```

## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
