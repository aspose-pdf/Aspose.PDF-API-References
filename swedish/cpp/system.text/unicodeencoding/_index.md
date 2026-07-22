---
title: "System::Text::UnicodeEncoding klass"
linktitle: "UnicodeEncoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::UnicodeEncoding klass. Unicode‑kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2500
url: /sv/cpp/system.text/unicodeencoding/
---
## UnicodeEncoding class


Unicode‑kodning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klonar kodningsobjekt. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Jämför kodningar. |
| [GetHashCode](./gethashcode/)() const override | Hashar kodning. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Hämta det maximala antalet byte som behövs för att koda ett angivet antal tecken. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Hämta det maximala antalet tecken som behövs för att avkoda ett angivet antal byte. |
| [GetPreamble](./getpreamble/)() override | Returnerar en sekvens av byte som anger kodningen (t.ex. BOM). |
| [operator==](./operator==/)(const UnicodeEncoding\&) const | Jämför kodningar efter kodsidor och flaggor. |
| [UnicodeEncoding](./unicodeencoding/)() | Konstruktor. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool) | Konstruktor. |
| [UnicodeEncoding](./unicodeencoding/)(bool, bool, bool) | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | Big endian kodsidnummer. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardvärde för kodsida. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | Liten endian kodsidnummer. |
## Se även

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
