---
title: System::Text::Encoder::GetByteCount method
linktitle: GetByteCount
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encoder::GetByteCount method. Gets the number of bytes needed to encode a buffer in C++.'
type: docs
weight: 400
url: /cpp/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method


Gets the number of bytes needed to encode a buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters to encode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of characters to encode. |
| flush | bool | If true, cleans internal encoder state after calculation. |

### ReturnValue

Number of bytes required to encode the buffer.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoder::GetByteCount(const char_t *, int, bool) method


Gets the number of bytes needed to encode a buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| count | int | Number of characters to encode. |
| flush | bool | If true, cleans internal encoder state after calculation. |

### ReturnValue

Number of bytes required to encode the buffer.

## See Also

* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
