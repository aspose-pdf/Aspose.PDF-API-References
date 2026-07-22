---
title: "System::Text::RegularExpressions::Match klass"
linktitle: "Match"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::Match klass. Enskild matchning av reguljärt uttryck mot en sträng. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.text.regularexpressions/match/
---
## Match class


[Single](../../system/single/) match of regexp over string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Match : public System::Text::RegularExpressions::Group
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Lägger till fångst i matchning. |
| [AddGroup](./addgroup/)(const GroupPtr\&) | Lägger till grupp i matchning. |
| static [get_Empty](./get_empty/)() | Åtkomst för tom matchning. |
| [get_Groups](./get_groups/)() | Hämtar grupplista. |
| [Match](./match/)(const UStringPtr\&, int, int) | Konstruktor. |
| [NextMatch](./nextmatch/)() | Iteration över matchningar. |
| virtual [Result](./result/)(const String\&) | Formaterar sträng genom att ersätta submatch‑referenser med deras värden. |
| [SetMappedIndexes](./setmappedindexes/)(const std::vector\<int\>\&) |  |
## Se även

* Class [Group](../group/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
