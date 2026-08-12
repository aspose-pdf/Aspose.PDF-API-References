---
title: "System::Text::ICUDecoder::GetChars metod"
linktitle: "GetChars"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUDecoder::GetChars metod. Hämta tecknen som resultat av att avkoda en buffer i C++."
type: docs
weight: 500
url: /sv/cpp/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Hämta tecknen som resultat av att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | ArrayPtr\<uint8_t\> | Byte att avkoda. |
| byteIndex | int | Inmatningsbuffertens offset. |
| byteCount | int | Storlek på inmatningsbuffert. |
| tecken | ArrayPtr\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Förskjutning för målarray. |

### ReturnValue

Antal tecken skrivna.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method


Hämta tecknen som resultat av att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | ArrayPtr\<uint8_t\> | Byte att avkoda. |
| byteIndex | int | Inmatningsbuffertens offset. |
| byteCount | int | Storlek på inmatningsbuffert. |
| tecken | ArrayPtr\<char_t\> | Målbuffert för tecken. |
| charIndex | int | Förskjutning för målarray. |
| spola | bool | Om sant, rensar internt avkodartillstånd efter beräkning. |

### ReturnValue

Antal tecken skrivna.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method


Hämta tecknen som resultat av att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | const uint8_t * | Byte att avkoda. |
| byteCount | int | Storlek på inmatningsbuffert. |
| tecken | char_t * | Målbuffert för tecken. |
| charCount | int | Storlek på målarray. |
| spola | bool | Om sant, rensar internt avkodartillstånd efter beräkning. |

### ReturnValue

Antal tecken skrivna.

## Se även

* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
