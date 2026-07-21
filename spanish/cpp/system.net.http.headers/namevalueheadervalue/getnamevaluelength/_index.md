---
title: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength method"
linktitle: "GetNameValueLength"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength method. Convierte una cadena pasada desde el índice especificado a una instancia de la clase NameValueHeaderValue en C++."
type: docs
weight: 900
url: /es/cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) method


Convierte una cadena pasada desde el índice especificado a una instancia de la clase [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | String | Una cadena para analizar. |
| startIndex | int32_t | Una posición inicial para el análisis. |
| nameValueCreator | HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\> | Una función que se utiliza para crear nuevas instancias de la clase [NameValueHeaderValue](../). |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | Una instancia donde se asignará un objeto analizado. |

### ReturnValue

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) method


Convierte una cadena pasada desde el índice especificado a una instancia de la clase [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | String | Una cadena para analizar. |
| startIndex | int32_t | Una posición inicial para el análisis. |
| parsedValue | System::SharedPtr\<NameValueHeaderValue\>\& | Una instancia donde se asignará un objeto analizado. |

### ReturnValue

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
