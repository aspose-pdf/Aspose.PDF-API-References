---
title: "System::Text::ICUEncoder::GetBytes metod"
linktitle: "GetBytes"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUEncoder::GetBytes metod. Hämtar de byte som resultat av att koda en buffert i C++."
type: docs
weight: 500
url: /sv/cpp/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Hämta byte som resultat av att koda en buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | ArrayPtr\<char_t\> | Tecken att koda. |
| charIndex | int | Offset för källarray. |
| charCount | int | Längd för källsubarray. |
| byte | ArrayPtr\<uint8_t\> | Målbuffert för byte. |
| byteIndex | int | Offset för destinationsbuffer. |
| spola | bool | Om true, rensar det interna kodartillståndet efter beräkning. |

### ReturnValue

Antal skrivna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Hämta byte som resultat av att koda en buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | const char_t * | Tecken att koda. |
| charCount | int | Längd för källarray. |
| byte | uint8_t * | Målbuffert för byte. |
| byteCount | int | Storlek för destinationsbuffer. |
| spola | bool | Om true, rensar det interna kodartillståndet efter beräkning. |

### ReturnValue

Antal skrivna byte.

## Se även

* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
