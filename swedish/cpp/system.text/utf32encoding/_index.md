---
title: "System::Text::UTF32Encoding klass"
linktitle: "UTF32Encoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::UTF32Encoding-klass. UTF-32-kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.text/utf32encoding/
---
## UTF32Encoding class


UTF-32-kodning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class UTF32Encoding : public System::Text::ICUEncoding
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone](./clone/)() override | Klonar kodningsobjekt. |
| [Equals](./equals/)(SharedPtr\<Object\>) override | Jämför med objekt. |
| [GetHashCode](./gethashcode/)() const override | Hämtar kodningens hash‑kod. |
| [GetPreamble](./getpreamble/)() override | Hämta kodsidans förord. |
| [operator==](./operator==/)(const UTF32Encoding\&) const | Jämför kodningarnas parametrar. |
| [UTF32Encoding](./utf32encoding/)() | Konstruktor. |
| [UTF32Encoding](./utf32encoding/)(bool, bool) | Konstruktor. |
| [UTF32Encoding](./utf32encoding/)(bool, bool, bool) | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static constexpr [BIG_UTF32_CODE_PAGE](./big_utf32_code_page/) | Magiskt tal som används av [Windows](../../system.windows/) för big endian UTF-32‑kodsid. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standardvärde för kodsida. |
| static constexpr [UTF32_CODE_PAGE](./utf32_code_page/) | Magiskt tal som används av [Windows](../../system.windows/) för little endian UTF-32‑kodsid. |
## Se även

* Class [ICUEncoding](../icuencoding/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
