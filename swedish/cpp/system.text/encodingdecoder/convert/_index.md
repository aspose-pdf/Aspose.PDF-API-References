---
title: "System::Text::EncodingDecoder::Convert metod"
linktitle: "Konvertera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::EncodingDecoder::Convert metod. Konverterar byte till tecken i C++."
type: docs
weight: 100
url: /sv/cpp/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Konverterar byte till tecken.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | ArrayPtr\<uint8_t\> | Byte att avkoda. |
| byteIndex | int | Inmatningsbuffertens offset. |
| byteCount | int | Storlek på inmatningsbuffert. |
| tecken | ArrayPtr\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Förskjutning för målarray. |
| charCount | int | Storlek på målarray. |
| spola | bool | Om sant, rensar internt avkodartillstånd efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antalet skrivna tecken. |
| completed | bool\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Konverterar byte till tecken.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | const uint8_t * | Byte att avkoda. |
| byteCount | int | Storlek på inmatningsbuffert. |
| tecken | char_t * | Målbuffert för tecken. |
| charCount | int | Storlek på målarray. |
| spola | bool | Om sant, rensar internt avkodartillstånd efter beräkning. |
| bytesUsed | int\& | Referens till variabel för att lagra antalet lästa byte. |
| charsUsed | int\& | Referens till variabel för att lagra antalet skrivna tecken. |
| completed | bool\& | Referens till variabel som ska sättas till true om inmatningsbufferten är uttömd och till false annars. |

## Se även

* Class [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
