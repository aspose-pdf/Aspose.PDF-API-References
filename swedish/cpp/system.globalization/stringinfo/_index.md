---
title: "System::Globalization::StringInfo klass"
linktitle: "StringInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::StringInfo klass. Delare för att iterera genom strängdelar. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2400
url: /sv/cpp/system.globalization/stringinfo/
---
## StringInfo class


Delare för att iterera genom strängdelar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class StringInfo : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(SharedPtr\<Object\>) override |  |
| [get_LengthInTextElements](./get_lengthintextelements/)() const | Hämtar antalet textobjekt i [StringInfo](./)-objektet. |
| [get_String](./get_string/)() const | Hämtar värdet för [StringInfo](./)-objektet. |
| [GetHashCode](./gethashcode/)() const override | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Möjliggör hashning av anpassade objekt. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&) | Hämtar det första elementet i den angivna strängen. |
| static [GetNextTextElement](./getnexttextelement/)(const String\&, int) | Hämtar elementet på det angivna indexet i den angivna strängen. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&) | Skapar en enumerator för att iterera genom strängens tecken. |
| static [GetTextElementEnumerator](./gettextelementenumerator/)(const String\&, int) | Skapar en enumerator för att iterera genom strängens tecken med start vid det angivna indexet. |
| [operator=](./operator=/)(const StringInfo\&) |  |
| static [ParseCombiningCharacters](./parsecombiningcharacters/)(const String\&) | Hämtar index för bastecken, högsurrogater och kontrolltecken. |
| [set_String](./set_string/)(const String\&) | Ställer in värdet för [StringInfo](./)-objektet. |
| [StringInfo](./stringinfo/)() | RTTI-information. |
| [StringInfo](./stringinfo/)(const String\&) | Konstruktor. |
| [StringInfo](./stringinfo/)(const StringInfo\&) |  |
| [SubstringByTextElements](./substringbytextelements/)(int) const | Hämtar delsträng av textelement från det angivna textelementet till det sista textelementet. |
| [SubstringByTextElements](./substringbytextelements/)(int, int) const | Hämtar delsträng av textelement från det angivna textelementet genom det angivna antalet textelement. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
