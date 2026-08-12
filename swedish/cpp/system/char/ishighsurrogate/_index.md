---
title: "System::Char::IsHighSurrogate‑metod"
linktitle: "IsHighSurrogate"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Char::IsHighSurrogate‑metod. Avgör om det angivna tecknet är en hög surrogat i C++."
type: docs
weight: 800
url: /sv/cpp/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(char_t) method


Bestämmer om det specificerade tecknet är en högsurrogat.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | char_t | Tecknet att testa |

### ReturnValue

Sant om det angivna tecknet är en high surrogate, annars - falskt

## Se även

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const char_t *, int) method


Bestämmer om tecknet på den specificerade indexen i den specificerade teckenbufferten är en högsurrogat.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char_t * | Pekare till början av teckenbufferten |
| idx | int | Ett nollbaserat index i den angivna bufferten för tecknet att testa |

### ReturnValue

Sant om tecknet på det angivna indexet är en high surrogate, annars - falskt

## Se även

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::IsHighSurrogate(const String\&, int) method


Bestämmer om tecknet på den specificerade indexen i den specificerade strängen är en UTF-16 högsurrogat kodenhet.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | En sträng |
| index | int | Indexet i den angivna strängen för tecknet som ska testas |

### ReturnValue

Sant om tecknet på det angivna indexet är en UTF-16 high surrogate kodenhet, annars - falskt

## Se även

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
