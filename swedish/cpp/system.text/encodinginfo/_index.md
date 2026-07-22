---
title: "System::Text::EncodingInfo-klass"
linktitle: "EncodingInfo"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncodingInfo klass. Kort information om kodning. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1900
url: /sv/cpp/system.text/encodinginfo/
---
## EncodingInfo class


Kort information om kodning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class EncodingInfo : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EncodingInfo](./encodinginfo/)(int, const String\&, const String\&) | Konstruktor. |
| [get_CodePage](./get_codepage/)() const | Hämtar kodsidans ID. |
| [get_DisplayName](./get_displayname/)() const | Hämtar det fullständiga lokala kodningsnamnet. |
| [get_Name](./get_name/)() const | Hämtar kodningens korta namn. |
| [GetEncoding](./getencoding/)() | Hämtar kodning som beskrivs av info. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
