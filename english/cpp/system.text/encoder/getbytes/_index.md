---
title: System::Text::Encoder::GetBytes method
linktitle: GetBytes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encoder::GetBytes method. Get the bytes that result from encoding a buffer in C++.'
type: docs
weight: 500
url: /cpp/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Get the bytes that result from encoding a buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters to encode. |
| charIndex | int | Source array offset. |
| charCount | int | Source subarray length. |
| bytes | ArrayPtr\<uint8_t\> | Destination byte buffer. |
| byteIndex | int | Destination buffer offset. |
| flush | bool | If true, cleans internal encoder state after calculation. |

### ReturnValue

Number of bytes written.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Get the bytes that result from encoding a buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| charCount | int | Source array length. |
| bytes | uint8_t * | Destination byte buffer. |
| byteCount | int | Destination buffer size. |
| flush | bool | If true, cleans internal encoder state after calculation. |

### ReturnValue

Number of bytes written.

## See Also

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
