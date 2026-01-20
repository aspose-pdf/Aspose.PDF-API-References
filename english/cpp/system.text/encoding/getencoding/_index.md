---
title: System::Text::Encoding::GetEncoding method
linktitle: GetEncoding
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::Encoding::GetEncoding method. Gets encoding by name in C++.'
type: docs
weight: 4100
url: /cpp/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) method


Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | [Encoding](../) name. |

### ReturnValue

[Encoding](../) of specified name.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method


Gets encoding by name.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


| Parameter | Type | Description |
| --- | --- | --- |
| name | const String\& | [Encoding](../) name. |
| encoder_fallback | const EncoderFallbackPtr\& | Fallback to use for encoding. |
| decoder_fallback | const DecoderFallbackPtr\& | Fallback to use for decoding. |

### ReturnValue

[Encoding](../) of specified name.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(int) method


Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |

### ReturnValue

[Encoding](../) of specified codepage.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method


Gets encoding by codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |
| encoder_fallback | const EncoderFallbackPtr\& | Fallback to use for encoding. |
| decoder_fallback | const DecoderFallbackPtr\& | Fallback to use for decoding. |

### ReturnValue

[Encoding](../) of specified codepage.

## See Also

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
