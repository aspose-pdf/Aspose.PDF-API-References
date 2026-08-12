---
title: "System::Char::TryParse metod"
linktitle: "TryParse"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Char::TryParse metod. Försöker konvertera en sträng som består av ett enda tecken till ett UTF‑16‑tecken. Funktionen lyckas endast när inmatningssträngen inte är null och har en längd på exakt ett tecken i C++."
type: docs
weight: 2600
url: /sv/cpp/system/char/tryparse/
---
## Char::TryParse method


Försöker konvertera en sträng som består av ett enda tecken till ett UTF-16‑tecken. Funktionen lyckas endast när inmatningssträngen inte är null och har en längd på exakt ett tecken.

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const System::String\& | [String](../../string/) att konvertera |
| result | char_t\& | Utdata‑variabeln som kommer att innehålla resultatet av konverteringen om konverteringen lyckas |

### ReturnValue

Sant om konverteringen lyckades, annars – falskt

## Se även

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
