---
title: System::Text::UTF7Encoding::GetBytes method
linktitle: GetBytes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::UTF7Encoding::GetBytes method. Get the bytes that result from encoding a character buffer in C++.'
type: docs
weight: 500
url: /cpp/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters to encode. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Get the bytes that result from encoding a character buffer.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### ReturnValue

Number of written bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method


Get the bytes that result from encoding a character buffer.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | uint8_t * | [Buffer](../../../system/buffer/) to put characters to. |
| byte_count | int | Output buffer size. |

### ReturnValue

Number of written bytes.

## See Also

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const String\&) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) to encode. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


Get the bytes that result from encoding a character buffer.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | ArrayPtr\<uint8_t\> | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### ReturnValue

Number of written bytes.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Get the bytes that result from encoding a character buffer.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### ReturnValue

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::ArrayView\<uint8_t\> | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### ReturnValue

Number of written bytes.

## See Also

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method


Get the bytes that result from encoding a character buffer.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::StackArray\<uint8_t, SB\>\& | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### ReturnValue

Number of written bytes.

## See Also

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
