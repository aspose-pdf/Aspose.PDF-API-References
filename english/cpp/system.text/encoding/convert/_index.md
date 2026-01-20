---
title: System::Text::Encoding::Convert method
linktitle: Convert
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encoding::Convert method. Converts bytes between two encodings in C++.'
type: docs
weight: 3000
url: /cpp/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) method


Converts bytes between two encodings.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const EncodingPtr\& | Source encoding. |
| dst_encoding | const EncodingPtr\& | Destination encoding. |
| bytes | const ArrayPtr\<uint8_t\>\& | Bytes to convert. |

### ReturnValue

Converted bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) method


Converts bytes between two encodings.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const EncodingPtr\& | Source encoding. |
| dst_encoding | const EncodingPtr\& | Destination encoding. |
| bytes | const ArrayPtr\<uint8_t\>\& | Bytes to convert. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### ReturnValue

Converted bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
