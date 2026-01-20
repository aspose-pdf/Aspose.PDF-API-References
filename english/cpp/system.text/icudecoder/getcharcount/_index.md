---
title: System::Text::ICUDecoder::GetCharCount method
linktitle: GetCharCount
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::ICUDecoder::GetCharCount method. Gets the number of characters needed to decode a buffer in C++.'
type: docs
weight: 400
url: /cpp/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | Bytes to decode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of bytes to decode. |

### ReturnValue

Number of characters required to decode the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method


Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | Bytes to decode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of bytes to decode. |
| flush | bool | If true, cleans internal decoder state after calculation. |

### ReturnValue

Number of characters required to decode the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUDecoder::GetCharCount(const uint8_t *, int, bool) method


Gets the number of characters needed to decode a buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const uint8_t * | Bytes to decode. |
| count | int | Number of bytes to decode. |
| flush | bool | If true, cleans internal decoder state after calculation. |

### ReturnValue

Number of characters required to decode the buffer.

## See Also

* Class [ICUDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
