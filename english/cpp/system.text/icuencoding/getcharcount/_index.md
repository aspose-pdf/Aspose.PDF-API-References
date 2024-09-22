---
title: System::Text::ICUEncoding::GetCharCount method
linktitle: GetCharCount
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::ICUEncoding::GetCharCount method. Get the number of characters needed to decode a byte buffer in C++.'
type: docs
weight: 400
url: /cpp/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) method


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | Bytes to decode. |

### ReturnValue

Number of characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method


Get the number of characters needed to decode a byte buffer.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | ArrayPtr\<uint8_t\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### ReturnValue

Number of characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## ICUEncoding::GetCharCount(const uint8_t *, int) method


Get the number of characters needed to decode a byte buffer.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const uint8_t * | Bytes to decode. |
| count | int | Bytes count. |

### ReturnValue

Number of characters.

## See Also

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
