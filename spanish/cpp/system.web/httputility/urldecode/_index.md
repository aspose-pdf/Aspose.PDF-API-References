---
title: "System::Web::HttpUtility::UrlDecode método"
linktitle: "UrlDecode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Web::HttpUtility::UrlDecode método. Decodifica el fragmento URI de una matriz de bytes en C++."
type: docs
weight: 300
url: /es/cpp/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) method


Decodifica fragmento URI desde matriz de bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Fragmento de URI codificado. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Codificación a usar. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) method


Decodifica fragmento URI desde matriz de bytes.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bytes | const System::ArrayPtr\<uint8_t\>\& | Fragmento de URI codificado. |
| desplazamiento | int32_t | Desplazamiento en la matriz de bytes dada. |
| count | int32_t | Número de bytes a leer. |
| e | const System::SharedPtr\<Text::Encoding\>\& | Codificación a usar. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String) method


Decodifica fragmento URI desde cadena.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | String | Fragmento de URI codificado. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) method


Decodifica fragmento URI desde cadena.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | String | Fragmento de URI codificado. |
| e | System::SharedPtr\<Text::Encoding\> | Codificación a usar. |

### ReturnValue

Fragmento URI decodificado.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Encoding](../../../system.text/encoding/)
* Class [HttpUtility](../)
* Namespace [System::Web](../../)
* Library [Aspose.PDF for C++](../../../)
