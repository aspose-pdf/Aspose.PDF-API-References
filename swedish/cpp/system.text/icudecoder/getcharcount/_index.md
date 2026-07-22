---
title: "System::Text::ICUDecoder::GetCharCount-metoden"
linktitle: "GetCharCount"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::ICUDecoder::GetCharCount-metoden. Hämtar antalet tecken som behövs för att avkoda en buffert i C++."
type: docs
weight: 400
url: /sv/cpp/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Hämtar antalet tecken som behövs för att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | ArrayPtr\<uint8_t\> | Byte att avkoda. |
| index | int | [Buffer](../../../system/buffer/) förskjutning. |
| count | int | Antal byte att avkoda. |

### ReturnValue

Antal tecken som krävs för att avkoda bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Hämtar antalet tecken som behövs för att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | ArrayPtr\<uint8_t\> | Byte att avkoda. |
| index | int | [Buffer](../../../system/buffer/) förskjutning. |
| count | int | Antal byte att avkoda. |
| spola | bool | Om sant, rensar internt avkodartillstånd efter beräkning. |

### ReturnValue

Antal tecken som krävs för att avkoda bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetCharCount(const uint8_t *, int, bool) method


Hämtar antalet tecken som behövs för att avkoda en buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| byte | const uint8_t * | Byte att avkoda. |
| count | int | Antal byte att avkoda. |
| spola | bool | Om sant, rensar internt avkodartillstånd efter beräkning. |

### ReturnValue

Antal tecken som krävs för att avkoda bufferten.

## Se även

* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
