---
title: "System::Web::HttpUtility::UrlDecodeToBytes método"
linktitle: "UrlDecodeToBytes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Web::HttpUtility::UrlDecodeToBytes método. Decodifica el fragmento URI de una cadena de bytes en C++."
type: docs
weight: 400
url: /es/cpp/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const String\&) method


Decodifica fragmento URI desde cadena de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | Fragmento de URI codificado. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


Decodifica fragmento URI desde cadena.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const String\& | Fragmento de URI codificado. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Codificación a usar. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


Decodifica fragmento URI desde matriz de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Fragmento de URI codificado. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Decodifica fragmento URI desde matriz de bytes.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Fragmento de URI codificado. |
| desplazamiento | int32_t | Desplazamiento en la matriz de bytes dada. |
| count | int32_t | Número de bytes a leer. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
