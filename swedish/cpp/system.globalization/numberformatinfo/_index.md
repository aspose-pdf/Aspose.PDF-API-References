---
title: "System::Globalization::NumberFormatInfo klass"
linktitle: "NumberFormatInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::NumberFormatInfo klass. Innehåller information om hur man formaterar tal. Sättar-operationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1900
url: /sv/cpp/system.globalization/numberformatinfo/
---
## NumberFormatInfo class


Innehåller information om hur man formaterar tal. Sättar-operationer är endast aktiverade på objekt som inte är skrivskyddade. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klonar formatinformation. |
| [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Hämtar antalet decimaler för valuta. |
| [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Hämtar decimalavgränsare för valuta. |
| [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Hämtar grupperingstecken för valuta. |
| [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Hämtar antalet valuta-decimaler per grupp. |
| [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Hämtar negativt mönster för valuta. |
| [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Hämtar positivt mönster för valuta. |
| [get_CurrencySymbol](./get_currencysymbol/)() const | Hämtar valutasymbol. |
| static [get_CurrentInfo](./get_currentinfo/)() | Hämtar information om talformat definierad av den aktuella trådens kultur. |
| [get_DigitSubstitution](./get_digitsubstitution/)() const | Hämtar ett värde som anger hur siffrans form ska visas. |
| static [get_InvariantInfo](./get_invariantinfo/)() | Hämtar information om talformat definierad av invariant kultur. |
| [get_IsReadOnly](./get_isreadonly/)() const | Kontrollerar om formatet är skrivskyddat. |
| [get_NaNSymbol](./get_nansymbol/)() const | Hämtar NaN‑symbolen. |
| [get_NativeDigits](./get_nativedigits/)() const | Hämtar siffrors symboler (0 till 9). |
| [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Hämtar symbol för negativ oändlighet. |
| [get_NegativeSign](./get_negativesign/)() const | Hämtar negativt tecken. |
| [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Hämtar antalet decimaler. |
| [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Hämtar decimalavgränsare. |
| [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Hämtar gruppavgränsare för tal. |
| [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Hämtar antal siffror per grupp. |
| [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Hämtar negativt talmönster. |
| [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Hämtar antalet decimaler i procentvärden. |
| [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Hämtar decimalavgränsare i procentvärden. |
| [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Hämtar gruppavgränsare i procentvärden. |
| [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Hämtar antal siffror per grupp av procentvärden. |
| [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Hämtar negativt procentmönster. |
| [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Hämtar positivt procentmönster. |
| [get_PercentSymbol](./get_percentsymbol/)() const | Hämtar procentsymbol. |
| [get_PerMilleSymbol](./get_permillesymbol/)() const | Hämtar promillesymbol. |
| [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Hämtar symbol för positiv oändlighet. |
| [get_PositiveSign](./get_positivesign/)() const | Hämtar positivt tecken. |
| [GetFormat](./getformat/)(const TypeInfo\&) override | Hämtar formaterare av specifik typ. |
| static [GetInstance](./getinstance/)(const IFormatProviderPtr\&) | Hämtar formaterare som är associerad med formatleverantör. |
| [NumberFormatInfo](./numberformatinfo/)() | Standardkonstruktor (invariant [NumberFormatInfo](./)). |
| [operator=](./operator=/)(const NumberFormatInfo\&) |  |
| static [ReadOnly](./readonly/)(NumberFormatInfoPtr) | Hämtar skrivskyddad version av formaterare. |
| [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Ställer in antal decimaler för valuta. |
| [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const String\&) | Ställer in decimalavgränsare för valuta. |
| [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const String\&) | Ställer in grupperingstecken för valuta. |
| [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const ArrayPtr\<int\>\&) | Ställer in antal valuta-decimaler per grupp. |
| [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Ställer in negativt mönster för valuta. |
| [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Ställer in positivt mönster för valuta. |
| [set_CurrencySymbol](./set_currencysymbol/)(const String\&) | Ställer in valutasymbol. |
| [set_DigitSubstitution](./set_digitsubstitution/)(DigitShapes) | Ställer in ett värde som anger hur siffrans form ska visas. |
| [set_NaNSymbol](./set_nansymbol/)(const String\&) | Ställer in Not-a-Number-symbol. |
| [set_NativeDigits](./set_nativedigits/)(const ArrayPtr\<String\>\&) | Ställer in siffrorsymboler (0 till 9). |
| [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const String\&) | Ställer in negativ oändlighetssymbol. |
| [set_NegativeSign](./set_negativesign/)(const String\&) | Ställer in negativt tecken. |
| [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Ställer in antal decimaler. |
| [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const String\&) | Ställer in decimalavgränsare. |
| [set_NumberGroupSeparator](./set_numbergroupseparator/)(const String\&) | Ställer in grupperingstecken för tal. |
| [set_NumberGroupSizes](./set_numbergroupsizes/)(const ArrayPtr\<int\>\&) | Ställer in antal siffror per grupp. |
| [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Ställer in negativt mönster för tal. |
| [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Ställer in antal decimaler i procentvärden. |
| [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const String\&) | Ställer in decimalavgränsare i procentvärden. |
| [set_PercentGroupSeparator](./set_percentgroupseparator/)(const String\&) | Ställer in grupperingstecken i procentvärden. |
| [set_PercentGroupSizes](./set_percentgroupsizes/)(const ArrayPtr\<int\>\&) | Ställer in antal siffror per grupp av procentvärden. |
| [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Ställer in mönster för negativ procent. |
| [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Ställer in mönster för positiv procent. |
| [set_PercentSymbol](./set_percentsymbol/)(const String\&) | Ställer in procentsymbol. |
| [set_PerMilleSymbol](./set_permillesymbol/)(const String\&) | Ställer in promillesymbol. |
| [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const String\&) | Ställer in symbol för positiv oändlighet. |
| [set_PositiveSign](./set_positivesign/)(const String\&) | Ställer in positivt tecken. |
## Se även

* Class [Object](../../system/object/)
* Class [IFormatProvider](../../system/iformatprovider/)
* Class [ICloneable](../../system/icloneable/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
