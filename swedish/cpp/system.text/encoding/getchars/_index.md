---
title: "System::Text::Encoding::GetChars metod"
linktitle: "GetChars"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::Encoding::GetChars metod. Hämtar tecknen som resultat av avkodning av en byte‑buffert i C++."
type: docs
weight: 2000
url: /sv/cpp/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>) method


Hämta tecknen som resultat av att avkoda en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att läsa byte från. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Hämta tecknen som resultat av att avkoda en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att läsa byte från. |
| byte_index | int | Inmatningsbuffertens offset. |
| byte_count | int | Storlek på inmatningsbuffert. |
| chars | ArrayPtr\<char_t\> | [Buffer](../../../system/buffer/) för att lägga tecken i. |
| char_index | int | Utdatabuffertens offset. |

### ReturnValue

Antal skrivna tecken.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method


Hämta tecknen som resultat av att avkoda en bytebuffert.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att läsa byte från. |
| index | int | Inmatningsbuffertens offset. |
| count | int | Storlek på inmatningsbuffert. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetChars(const uint8_t *, int, char_t *, int) method


Hämta tecknen som resultat av att avkoda en bytebuffert.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | const uint8_t * | [Buffer](../../../system/buffer/) för att läsa byte från. |
| byte_count | int | Storlek på inmatningsbuffert. |
| chars | char_t * | [Buffer](../../../system/buffer/) för att lägga tecken i. |
| char_count | int | Storlek på utdata-buffert. |

### ReturnValue

Antal skrivna tecken.

## Se även

* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
