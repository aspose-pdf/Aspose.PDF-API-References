---
title: "System::Net::Http::Headers::HttpHeaders klass"
linktitle: "HttpHeaders"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::HttpHeaders-klass. Samlingen av HTTP-rubriker. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.http.headers/httpheaders/
---
## HttpHeaders class


Samlingen av HTTP-rubriker. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class HttpHeaders : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Collections::Generic::IEnumerable<System::String>>>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Validerar ett nytt namn/värde-par och lägger till det i den aktuella samlingen. |
| [Add](./add/)(String, String) | Validerar ett nytt namn‑värde‑par och lägger till det i den aktuella samlingen. |
| virtual [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) | Konkatenar den angivna HttpHeaders-klassens instans med den aktuella. |
| [AddParsedValue](./addparsedvalue/)(String, System::SharedPtr\<Object\>) | Hämtar en rubrik med det angivna namnet och lägger till ett parsat värde i rubriken. |
| [Clear](./clear/)() | Tar bort alla objekt från samlingen. |
| [Contains](./contains/)(String) |  |
| [ContainsParsedValue](./containsparsedvalue/)(String, System::SharedPtr\<Object\>) | Kontrollerar om rubriken innehåller det angivna värdet. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator. |
| [GetHeaderString](./getheaderstring/)(String) | Returnerar en strängrepresentation av värden för det angivna rubriknamnet. |
| [GetHeaderString](./getheaderstring/)(String, System::SharedPtr\<Object\>) | Returnerar en strängrepresentation av värden för det angivna rubriknamnet. |
| [GetHeaderStrings](./getheaderstrings/)() | Returnerar en samling som innehåller strängrepresentationer av rubrikernas värden. |
| [GetParsedValues](./getparsedvalues/)(String) | Returnerar tolkade värden för det angivna rubriknamnet. |
| [GetValues](./getvalues/)(String) | Returnerar motsvarande värden för det angivna namnet. |
| static [ParsedValuesAsList](./parsedvaluesaslist/)(const System::SharedPtr\<Object\>) | Konverterar tolkade värden till en lista. |
| [Remove](./remove/)(String) | Försöker ta bort ett objekt med det angivna namnet. |
| [RemoveParsedValue](./removeparsedvalue/)(String, System::SharedPtr\<Object\>) | Hämtar en rubrik med det angivna namnet och tar bort ett tolkat värde från rubriken. |
| [SetConfiguration](./setconfiguration/)(System::SharedPtr\<Collections::Generic::Dictionary\<String, System::SharedPtr\<HttpHeaderParser\>\>\>, System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) |  |
| [SetOrRemoveParsedValue](./setorremoveparsedvalue/)(String, System::SharedPtr\<Object\>) | Hämtar en rubrik med det angivna namnet och sätter eller tar bort dess värde. Rubrikvärdet kommer att tas bort när parametern 'value' är nullptr, annars kommer ett tolkat värde att sättas. |
| [SetParsedValue](./setparsedvalue/)(String, System::SharedPtr\<Object\>) | Hämtar en rubrik med det angivna namnet och sätter ett tolkat värde på rubriken. |
| [ToString](./tostring/)() const override | Analog till C#-metoden [Object.ToString()](../../system/object/tostring/). Gör det möjligt att konvertera anpassade objekt till sträng. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, String) | Försöker lägga till ett nytt namn‑värde‑par i den aktuella samlingen. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Lägger till en samling av namn‑värde‑par i den aktuella samlingen. |
| [TryGetValues](./trygetvalues/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) | Försöker hämta motsvarande värden för det angivna namnet. |
| [TryParseAndAddValue](./tryparseandaddvalue/)(String, String) | Försöker tolka det angivna värdet och lägga till det i rubrikvärdena. |
## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
