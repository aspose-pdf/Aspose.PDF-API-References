---
title: System::Text::UTF7Encoding::GetByteCount method
linktitle: GetByteCount
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::UTF7Encoding::GetByteCount method. Get the number of characters needed to encode a character buffer in C++.'
type: docs
weight: 400
url: /cpp/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) method


Get the number of characters needed to encode a character buffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters buffer. |

### ReturnValue

Required buffer size.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method


Get the number of characters needed to encode a character buffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | ArrayPtr\<char_t\> | Characters buffer. |
| index | int | Slice begin. |
| count | int | Slice size. |

### ReturnValue

Required buffer size.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(const char_t *, int) method


Get the number of characters needed to encode a character buffer.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters buffer. |
| count | int | [Buffer](../../../system/buffer/) size. |

### ReturnValue

Required buffer size.

## See Also

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(const String\&) method


Get the number of characters needed to encode a string.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


| Parameter | Type | Description |
| --- | --- | --- |
| s | const String\& | [String](../../../system/string/) to encode. |

### ReturnValue

Required buffer size.

## See Also

* Class [String](../../../system/string/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Get the number of characters needed to encode a character buffer.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Characters buffer. |
| index | int | Slice begin. |
| count | int | Slice size. |

### ReturnValue

Required buffer size.

## See Also

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method


Get the number of characters needed to encode a character buffer.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Characters buffer. |
| index | int | Slice begin. |
| count | int | Slice size. |

### ReturnValue

Required buffer size.

## See Also

* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
