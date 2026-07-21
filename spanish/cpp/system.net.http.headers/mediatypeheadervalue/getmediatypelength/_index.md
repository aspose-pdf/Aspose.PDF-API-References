---
title: "System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength método"
linktitle: "GetMediaTypeLength"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength método. Convierte una cadena pasada desde el índice especificado a una instancia de la clase MediaTypeHeaderValue en C++."
type: docs
weight: 1000
url: /es/cpp/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength method


Convierte una cadena pasada desde el índice especificado a una instancia de la clase [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | String | Una cadena para analizar. |
| startIndex | int32_t | Una posición inicial para el análisis. |
| mediaTypeCreator | HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\> | El delegado que se usa para crear instancias de la clase [MediaTypeHeaderValue](../). |
| parsedValue | System::SharedPtr\<MediaTypeHeaderValue\>\& | Una instancia donde se asignará un objeto analizado. |

### ReturnValue

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MediaTypeHeaderValue](../)
* Class [MediaTypeHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
