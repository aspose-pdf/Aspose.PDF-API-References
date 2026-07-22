---
title: "System::Text::Encoding::GetEncoding metod"
linktitle: "GetEncoding"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::Encoding::GetEncoding metod. Hämtar kodning efter namn i C++."
type: docs
weight: 4100
url: /sv/cpp/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) method


Hämtar kodning efter namn.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const String\& | [Encoding](../) namn. |

### ReturnValue

[Encoding](../) of specified name.

## Se även

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method


Hämtar kodning efter namn.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | const String\& | [Encoding](../) namn. |
| encoder_fallback | const EncoderFallbackPtr\& | Fallback att använda för kodning. |
| decoder_fallback | const DecoderFallbackPtr\& | Fallback att använda för avkodning. |

### ReturnValue

[Encoding](../) of specified name.

## Se även

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(int) method


Hämtar kodning efter kodsida.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codepage | int | Kodsidnummer. |

### ReturnValue

[Encoding](../) of specified codepage.

## Se även

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method


Hämtar kodning efter kodsida.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| codepage | int | Kodsidnummer. |
| encoder_fallback | const EncoderFallbackPtr\& | Fallback att använda för kodning. |
| decoder_fallback | const DecoderFallbackPtr\& | Fallback att använda för avkodning. |

### ReturnValue

[Encoding](../) of specified codepage.

## Se även

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
