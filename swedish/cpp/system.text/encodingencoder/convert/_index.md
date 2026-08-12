---
title: "System::Text::EncodingEncoder::Convert metod"
linktitle: "Konvertera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncodingEncoder::Convert metod. Konverterar tecken till byte i C++."
type: docs
weight: 100
url: /sv/cpp/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method


Konverterar tecken till byte.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | ArrayPtr\<char_t\> | Tecken att koda. |
| charIndex | int | Inmatningsbuffertens offset. |
| charCount | int | Storlek på inmatningsbuffert. |
| byte | ArrayPtr\<uint8_t\> | Målbuffert för byte. |
| byteIndex | int | Förskjutning för målarray. |
| byteCount | int | Storlek på målarray. |
| spola | bool | Om true, rensar det interna kodartillståndet efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet tecken som lästs. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet bytes som skrivits. |
| completed | bool\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method


Konverterar tecken till byte.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | const char_t * | Tecken att koda. |
| charCount | int | Storlek på inmatningsbuffert. |
| byte | uint8_t * | Målbuffert för byte. |
| byteCount | int | Storlek på målarray. |
| spola | bool | Om true, rensar det interna kodartillståndet efter beräkning. |
| charsUsed | int\& | Referens till variabel för att lagra antalet tecken som lästs. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet bytes som skrivits. |
| completed | bool\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## Se även

* Class [EncodingEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
