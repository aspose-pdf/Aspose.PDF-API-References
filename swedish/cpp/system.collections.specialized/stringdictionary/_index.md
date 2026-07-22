---
title: "System::Collections::Specialized::StringDictionary klass"
linktitle: "StringDictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Specialized::StringDictionary klass. Sträng till sträng-ordbok. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.collections.specialized/stringdictionary/
---
## StringDictionary class


[String](../../system/string/) to string dictionary. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringDictionary : public System::Collections::Generic::Dictionary<String, String>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [idx_get](./idx_get/)(const String\&) const override | Hämtar värdet för en specifik nyckel. |
## Se även

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.PDF for C++](../../)
