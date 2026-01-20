---
title: System::Text::Encoding::GetChars method
linktitle: GetChars
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encoding::GetChars method. Get the characters that result from decoding a byte buffer in C++.'
type: docs
weight: 2000
url: /cpp/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to read bytes from. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to read bytes from. |
| byte_index | int | Input buffer offset. |
| byte_count | int | Input buffer size. |
| chars | ArrayPtr\<char_t\> | [Buffer](../../../system/buffer/) to put characters to. |
| char_index | int | Output buffer offset. |

### ReturnValue

Number of written characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### ReturnValue

[Buffer](../../../system/buffer/) of decoded characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetChars(const uint8_t *, int, char_t *, int) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const uint8_t * | [Buffer](../../../system/buffer/) to read bytes from. |
| byte_count | int | Input buffer size. |
| chars | char_t * | [Buffer](../../../system/buffer/) to put characters to. |
| char_count | int | Output buffer size. |

### ReturnValue

Number of written characters.

## See Also

* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
