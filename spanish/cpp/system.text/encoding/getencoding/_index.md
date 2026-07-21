---
title: "Método System::Text::Encoding::GetEncoding"
linktitle: "GetEncoding"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Text::Encoding::GetEncoding. Obtiene la codificación por nombre en C++."
type: docs
weight: 4100
url: /es/cpp/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) method


Obtiene la codificación por nombre.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const String\& | Nombre de [Encoding](../). |

### ReturnValue

[Encoding](../) of specified name.

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method


Obtiene la codificación por nombre.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const String\& | Nombre de [Encoding](../). |
| encoder_fallback | const EncoderFallbackPtr\& | Fallback para usar en la codificación. |
| decoder_fallback | const DecoderFallbackPtr\& | Fallback para usar en la decodificación. |

### ReturnValue

[Encoding](../) of specified name.

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(int) method


Obtiene la codificación por página de códigos.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codepage | int | Número de codepage. |

### ReturnValue

[Encoding](../) of specified codepage.

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method


Obtiene la codificación por página de códigos.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| codepage | int | Número de codepage. |
| encoder_fallback | const EncoderFallbackPtr\& | Fallback para usar en la codificación. |
| decoder_fallback | const DecoderFallbackPtr\& | Fallback para usar en la decodificación. |

### ReturnValue

[Encoding](../) of specified codepage.

## Ver también

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.PDF for C++](../../../)
