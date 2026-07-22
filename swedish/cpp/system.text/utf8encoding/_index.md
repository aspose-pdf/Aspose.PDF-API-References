---
title: "System::Text::UTF8Encoding-klass"
linktitle: "UTF8Encoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::UTF8Encoding-klass. UTF-8-kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2800
url: /sv/cpp/system.text/utf8encoding/
---
## UTF8Encoding class


UTF-8-kodning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class UTF8Encoding : public System::Text::ICUEncoding
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klonar kodningsobjekt. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Jämför med objekt. |
| [GetHashCode](./gethashcode/)() const override | Hämtar kodningens hash‑kod. |
| [GetMaxByteCount](./getmaxbytecount/)(int) override | Hämta det maximala antalet byte som behövs för att koda ett angivet antal tecken. |
| [GetMaxCharCount](./getmaxcharcount/)(int) override | Hämta det maximala antalet tecken som behövs för att avkoda ett angivet antal byte. |
| [GetPreamble](./getpreamble/)() override | Hämta kodsidans förord. |
| [operator==](./operator==/)(const UTF8Encoding\&) const | Jämför kodningsparametrar. |
| [UTF8Encoding](./utf8encoding/)() | Konstruktor. |
| [UTF8Encoding](./utf8encoding/)(bool) | Konstruktor. |
| [UTF8Encoding](./utf8encoding/)(bool, bool) | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardvärde för kodsida. |
| static constexpr [UTF8_CODE_PAGE](./utf8_code_page/) | RTTI-information. |
## Se även

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
