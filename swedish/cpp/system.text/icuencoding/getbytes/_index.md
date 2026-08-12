---
title: "System::Text::ICUEncoding::GetBytes metod"
linktitle: "GetBytes"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUEncoding::GetBytes metod. Hämtar de byte som resultat av att koda en teckenbuffert i C++."
type: docs
weight: 300
url: /sv/cpp/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | ArrayPtr\<char_t\> | Tecken att koda. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | ArrayPtr\<char_t\> | Tecken att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att lägga tecken i. |
| byte_index | int | Utdatabuffertens offset. |

### ReturnValue

Antal skrivna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | ArrayPtr\<char_t\> | Tecken att koda. |
| index | int | Start på teckensegmentet. |
| count | int | Antal tecken att konvertera. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | const char_t * | Tecken att koda. |
| char_count | int | Antal tecken att konvertera. |
| bytes | uint8_t * | [Buffer](../../../system/buffer/) för att lägga tecken i. |
| byte_count | int | Storlek på utdata-buffert. |

### ReturnValue

Antal skrivna byte.

## Se även

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const String\&) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) att koda. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) för att lägga tecken i. |
| byte_index | int | Utdatabuffertens offset. |

### ReturnValue

Antal skrivna byte.

## Se även

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | const System::Details::ArrayView\<char_t\>\& | Tecken att koda. |
| index | int | Start på teckensegmentet. |
| count | int | Antal tecken att konvertera. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | const System::Details::StackArray\<char_t, N\>\& | Tecken att koda. |
| index | int | Start på teckensegmentet. |
| count | int | Antal tecken att konvertera. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | System::Details::ArrayView\<char_t\> | Tecken att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | System::Details::ArrayView\<uint8_t\> | [Buffer](../../../system/buffer/) för att lägga tecken i. |
| byte_index | int | Utdatabuffertens offset. |

### ReturnValue

Antal skrivna byte.

## Se även

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method


Hämta de byte som erhålls vid kodning av en teckenbuffert.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | System::Details::StackArray\<char_t, SC\>\& | Tecken att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | System::Details::StackArray\<uint8_t, SB\>\& | [Buffer](../../../system/buffer/) för att lägga tecken i. |
| byte_index | int | Utdatabuffertens offset. |

### ReturnValue

Antal skrivna byte.

## Se även

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
