---
title: "System::Text::Encoder::GetByteCount metod"
linktitle: "GetByteCount"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::Encoder::GetByteCount metod. Hämtar antalet byte som behövs för att koda en buffer i C++."
type: docs
weight: 400
url: /sv/cpp/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Hämtar antalet byte som behövs för att koda en buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
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
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoder::GetByteCount(const char_t *, int, bool) method


Hämtar antalet byte som behövs för att koda en buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken | const char_t * | Tecken att koda. |
| count | int | Antal tecken att koda. |
| spola | bool | Om true, rensar det interna kodartillståndet efter beräkning. |

### ReturnValue

Antal byte som krävs för att koda bufferten.

## Se även

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
