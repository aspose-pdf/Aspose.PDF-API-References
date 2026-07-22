---
title: "System::Char::ConvertToUtf32 metod"
linktitle: "ConvertToUtf32"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Char::ConvertToUtf32 metod. Konverterar det angivna UTF-16-surrogatparet till en UTF-32-kod enhet i C++."
type: docs
weight: 200
url: /sv/cpp/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) method


Konverterar det angivna UTF-16-surrogatparet till en UTF-32-kodenhet.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| highSurrogate | char_t | Det högsurrogatet för UTF-16-surrogatparet som ska konverteras |
| lowSurrogate | char_t | Det lågsurrogatet för UTF-16-surrogatparet som ska konverteras |

### ReturnValue

En UTF-32-kod enhet som erhålls från konverteringen

## Se även

* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Char::ConvertToUtf32(const String\&, int) method


Konverterar värdet av ett UTF-16-kodat tecken eller surrogatpar på en specificerad position i en sträng till en UTF-32-kod enhet.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | En sträng som innehåller ett tecken eller ett surrogatpar |
| index | int | Indexpositionen för tecknet eller surrogatparet i den angivna strängen |

### ReturnValue

En UTF-32-kod enhet som erhålls från konverteringen

## Se även

* Class [String](../../string/)
* Class [Char](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
