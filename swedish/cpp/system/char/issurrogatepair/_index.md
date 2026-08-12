---
title: "System::Char::IsSurrogatePair metod"
linktitle: "IsSurrogatePair"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Char::IsSurrogatePair metod. Bestämmer om de två angivna tecknen utgör ett UTF‑16‑surrogatpar i C++."
type: docs
weight: 1700
url: /sv/cpp/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) method


Bestämmer om de två angivna tecknen för ett UTF-16 surrogatpar.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| highSurrogate | char_t | Ett tecken som testas för att vara ett högsurrogat |
| lowSurrogate | char_t | Ett tecken som testas för att vara ett lågsurrogat |

### ReturnValue

Sant om de angivna tecknen bildar ett surrogatpar, annars - falskt

## Se även

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsSurrogatePair(const String\&, int) method


Bestämmer om två på varandra följande tecken i den angivna teckenbufferten bildar ett surrogatpar.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const String\& | En sträng |
| index | int | Ett nollbaserat index i den angivna bufferten där teckensekvensen som ska testas börjar |

### ReturnValue

Sant om de angivna tecknen är ett surrogatpar, annars - falskt

## Se även

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
