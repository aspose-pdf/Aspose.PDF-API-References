---
title: "System::Text::ICUEncoder::GetByteCount metod"
linktitle: "GetByteCount"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUEncoder::GetByteCount metod. Hämtar antalet byte som behövs för att koda en buffert i C++."
type: docs
weight: 400
url: /sv/cpp/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Hämtar antalet byte som behövs för att koda en buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | ArrayPtr\<char_t\> | Tecken att koda. |
| index | int | [Buffer](../../../system/buffer/) förskjutning. |
| count | int | Antal tecken att koda. |
| spola | bool | Om true, rensar det interna kodartillståndet efter beräkning. |

### ReturnValue

Antal byte som krävs för att koda bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoder::GetByteCount(const char_t *, int, bool) method


Hämtar antalet byte som behövs för att koda en buffer.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | const char_t * | Tecken att koda. |
| count | int | Antal tecken att koda. |
| spola | bool | Om true, rensar det interna kodartillståndet efter beräkning. |

### ReturnValue

Antal byte som krävs för att koda bufferten.

## Se även

* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
