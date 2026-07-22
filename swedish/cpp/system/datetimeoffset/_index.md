---
title: "System::DateTimeOffset class"
linktitle: "DateTimeOffset"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::DateTimeOffset‑klass. Innehåller datum och tid på dagen i förhållande till Coordinated Universal Time. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1800
url: /sv/cpp/system/datetimeoffset/
---
## DateTimeOffset class


Innehåller datum och tid på dagen i förhållande till Coordinated Universal Time. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DateTimeOffset
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(TimeSpan) const | Lägger till ett specificerat tidsintervall till [DateTimeOffset](./)-objektet. |
| [AddDays](./adddays/)(double) const | Lägger till ett specificerat antal dagar till [DateTimeOffset](./)-objektet. |
| [AddHours](./addhours/)(double) const | Lägger till ett specificerat antal timmar till [DateTimeOffset](./)-objektet. |
| [AddMilliseconds](./addmilliseconds/)(double) const | Lägger till ett specificerat antal millisekunder till [DateTimeOffset](./)-objektet. |
| [AddMinutes](./addminutes/)(double) const | Lägger till ett specificerat antal minuter till [DateTimeOffset](./)-objektet. |
| [AddMonths](./addmonths/)(int) const | Lägger till ett specificerat antal månader till [DateTimeOffset](./)-objektet. |
| [AddSeconds](./addseconds/)(double) const | Lägger till ett specificerat antal sekunder till [DateTimeOffset](./)-objektet. |
| [AddTicks](./addticks/)(int64_t) const | Lägger till ett specificerat antal tickar till [DateTimeOffset](./)-objektet. |
| [AddYears](./addyears/)(int) const | Lägger till ett specificerat antal år till [DateTimeOffset](./)-objektet. |
| static [Compare](./compare/)(const DateTimeOffset\&, const DateTimeOffset\&) | Jämför två [DateTimeOffset](./)-objekt. |
| [CompareTo](./compareto/)(const DateTimeOffset\&) const | Jämför två [DateTimeOffset](./)-objekt. |
| [CompareTo](./compareto/)(const SharedPtr\<Object\>\&) const | Jämför två [DateTimeOffset](./)-objekt. |
| [DateTimeOffset](./datetimeoffset/)() | Standardkonstruktor. |
| [DateTimeOffset](./datetimeoffset/)(DateTime) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int64_t, TimeSpan) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(DateTime, TimeSpan) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, TimeSpan) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, TimeSpan) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const SharedPtr\<Globalization::Calendar\>\&, TimeSpan) | Konstruktor. |
| static [Equals](./equals/)(const DateTimeOffset\&, const DateTimeOffset\&) | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt. |
| [Equals](./equals/)(const DateTimeOffset\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt. |
| [Equals](./equals/)(const SharedPtr\<Object\>\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt. |
| [EqualsExact](./equalsexact/)(const DateTimeOffset\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt och har samma förskjutning. |
| [EqualsExact](./equalsexact/)(const SharedPtr\<Object\>\&) const | Kontrollerar om två [DateTimeOffset](./)-objekt representerar samma tidpunkt och har samma förskjutning. |
| static [FromFileTime](./fromfiletime/)(int64_t) | [Convert](../convert/)[Windows](../../system.windows/) filtid till datum och tid med lokal tidsförskjutning. |
| static [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(int64_t) | [Convert](../convert/) Unix-tid till [DateTimeOffset](./)-objekt. |
| static [FromUnixTimeSeconds](./fromunixtimeseconds/)(int64_t) | [Convert](../convert/) Unix-tid till [DateTimeOffset](./)-objekt. |
| [get_Date](./get_date/)() const | Hämtar datumkomponenten för det aktuella objektet. |
| [get_DateTime](./get_datetime/)() const | Hämtar [DateTime](../datetime/)-värde. |
| [get_Day](./get_day/)() const | Hämtar dag i månaden för det aktuella objektet. |
| [get_DayOfWeek](./get_dayofweek/)() const | Hämtar veckodag för det aktuella objektet. |
| [get_DayOfYear](./get_dayofyear/)() const | Hämtar dag på året för det aktuella objektet. |
| [get_Hour](./get_hour/)() const | Hämtar timkomponenten för det aktuella objektet. |
| [get_LocalDateTime](./get_localdatetime/)() const | Hämtar [DateTime](../datetime/)-värde som representerar lokalt datum och tid. |
| [get_Millisecond](./get_millisecond/)() const | Hämtar millisekundkomponenten för det aktuella objektet. |
| [get_Minute](./get_minute/)() const | Hämtar minutkomponenten för det aktuella objektet. |
| [get_Month](./get_month/)() const | Hämtar månadskomponenten för det aktuella objektet. |
| static [get_Now](./get_now/)() | Hämtar [DateTimeOffset](./) vars datum och tid är satta till den aktuella lokala tiden och vars förskjutning är satt till den lokala tidsförskjutningen. |
| [get_Offset](./get_offset/)() const | Hämtar förskjutning från UTC. |
| [get_Second](./get_second/)() const | Hämtar sekundkomponenten för det aktuella objektet. |
| [get_Ticks](./get_ticks/)() const | Hämtar antalet tickar för det aktuella objektet. |
| [get_TimeOfDay](./get_timeofday/)() const | Hämtar tid på dagen för det aktuella objektet. |
| [get_UtcDateTime](./get_utcdatetime/)() const | Hämtar [DateTime](../datetime/)-värde som representerar UTC-datum och -tid. |
| static [get_UtcNow](./get_utcnow/)() | Hämtar [DateTimeOffset](./) vars datum och tid är satta till den aktuella UTC-tiden och vars förskjutning är [TimeSpan::Zero](../timespan/zero/). |
| [get_UtcTicks](./get_utcticks/)() const | Hämtar antalet tick för det aktuella objektet i UTC-tid. |
| [get_Year](./get_year/)() const | Hämtar årkomponenten för det aktuella objektet. |
| [GetHashCode](./gethashcode/)() const | Hämtar hashkod för det aktuella [DateTimeOffset](./) objektet. |
| [IsNull](./isnull/)() const |  |
| [operator!=](./operator!=/)(const DateTimeOffset\&) const | Bestämmer om det aktuella objektet och det angivna [DateTimeOffset](./)-objektet representerar olika datum- och tidsvärden. |
| [operator!=](./operator!=/)(std::nullptr_t) const |  |
| [operator+](./operator+/)(TimeSpan) const | Returnerar en ny instans av klassen [DateTimeOffset](./) som representerar datum- och tidsvärdet som är summan av värdet som representeras av det aktuella objektet och det angivna tidsintervallet. |
| [operator-](./operator-/)(TimeSpan) const | Returnerar en ny instans av klassen [DateTimeOffset](./) som representerar datum- och tidsvärdet som är resultatet av subtraktionen av det angivna tidsintervallet från värdet som representeras av det aktuella objektet. |
| [operator-](./operator-/)(const DateTimeOffset\&) const | Returnerar en instans av klassen [TimeSpan](../timespan/) som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella och det angivna objektet. |
| [operator<](./operator_/)(const DateTimeOffset\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är tidigare än värdet som representeras av det angivna [DateTimeOffset](./)-objektet. |
| [operator<](./operator_/)(std::nullptr_t) const |  |
| [operator<=](./operator_=/)(const DateTimeOffset\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är tidigare än eller samma som värdet som representeras av det angivna [DateTimeOffset](./)-objektet. |
| [operator<=](./operator_=/)(std::nullptr_t) const |  |
| [operator==](./operator==/)(const DateTimeOffset\&) const | Bestämmer om det aktuella objektet och det angivna [DateTimeOffset](./)-objektet representerar samma datum- och tidsvärde. |
| [operator==](./operator==/)(std::nullptr_t) const |  |
| [operator>](./operator_/)(const DateTimeOffset\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är senare än värdet som representeras av det angivna [DateTimeOffset](./)-objektet. |
| [operator>](./operator_/)(std::nullptr_t) const |  |
| [operator>=](./operator_=/)(const DateTimeOffset\&) const | Bestämmer om det aktuella objektet representerar datum- och tidsvärdet som är senare än eller samma som värdet som representeras av det angivna [DateTimeOffset](./)-objektet. |
| [operator>=](./operator_=/)(std::nullptr_t) const |  |
| static [Parse](./parse/)(const String\&) | Konverterar den angivna strängen till motsvarande [DateTimeOffset](./). |
| static [Parse](./parse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Konverterar den angivna strängen till ett [DateTimeOffset](./)-objekt med den angivna formatleverantören och formateringsstilen. |
| static [ParseExact](./parseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Konverterar den angivna strängen till ett [DateTimeOffset](./)-objekt med det angivna formatet, formatleverantören och formateringsstilen. |
| static [ParseExact](./parseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) | Konverterar den angivna strängen till ett [DateTimeOffset](./)-objekt med de angivna formaten, formatleverantören och formateringsstilen. |
| [Subtract](./subtract/)(TimeSpan) const | Subtraherar ett angivet tidsintervall från det aktuella objektet. |
| [Subtract](./subtract/)(const DateTimeOffset\&) const | Subtraherar ett angivet [DateTimeOffset](./)-värde från det aktuella objektet. |
| [ToFileTime](./tofiletime/)() const | Konverterar det aktuella objektet till [Windows](../../system.windows/)-filtid. |
| [ToLocalTime](./tolocaltime/)() const | Konverterar det aktuella objektet till ett objekt som representerar lokal tid. |
| [ToOffset](./tooffset/)(TimeSpan) const | Ersätt det aktuella objektets förskjutning med den angivna förskjutningen. |
| [ToString](./tostring/)(const String\&, const SharedPtr\<IFormatProvider\>\&) const | Konverterar det aktuella objektet till en sträng med det angivna formatet och formatleverantören. |
| [ToString](./tostring/)(const SharedPtr\<IFormatProvider\>\&) const | Konverterar det aktuella objektet till en sträng med den angivna formatleverantören. |
| [ToString](./tostring/)(const String\&) const | Konverterar det aktuella objektet till en sträng med det angivna formatet. |
| [ToString](./tostring/)() const | Konverterar det aktuella objektet till en sträng. |
| [ToUniversalTime](./touniversaltime/)() const | Konverterar aktuellt objekt till ett objekt som representerar UTC-tiden,. |
| [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Hämtar millisekunder som förflutit sedan Unix-epokens början. |
| [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Hämtar sekunder som förflutit sedan Unix-epokens början. |
| static [TryParse](./tryparse/)(const String\&, DateTimeOffset\&) | Försöker konvertera den angivna strängen till [DateTimeOffset](./)-objekt. |
| static [TryParse](./tryparse/)(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Försöker konvertera den angivna strängen till [DateTimeOffset](./)-objekt med den angivna formatleverantören och formateringsstilen. |
| static [TryParseExact](./tryparseexact/)(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Försöker konvertera den angivna strängen till [DateTimeOffset](./)-objekt med de angivna formaten, formatleverantören och formateringsstilen. |
| static [TryParseExact](./tryparseexact/)(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) | Försöker konvertera den angivna strängen till [DateTimeOffset](./)-objekt med det angivna formatet, formatleverantören och formateringsstilen. |
| static [Type](./type/)() | Returnerar ett [TypeInfo](../typeinfo/)-objekt som representerar [TimeSpan](../timespan/)-strukturen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Hämtar maximal förskjutning i tick. |
| static [MaxValue](./maxvalue/) | Hämtar största [DateTimeOffset](./)-värdet. |
| static constexpr [MinOffset](./minoffset/) | Hämtar minimal förskjutning i tick. |
| static [MinValue](./minvalue/) | Hämtar tidigaste [DateTimeOffset](./)-värdet. |
| static [UnixEpoch](./unixepoch/) | Hämtar Unix-epokens början. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
