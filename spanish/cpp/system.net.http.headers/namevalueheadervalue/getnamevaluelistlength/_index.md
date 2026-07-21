---
title: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength method"
linktitle: "GetNameValueListLength"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength method. Convierte una cadena pasada desde el índice especificado a la colección de instancias de la clase NameValueHeaderValue y devuelve la longitud de una subcadena analizada en C++."
type: docs
weight: 1000
url: /es/cpp/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength method


Convierte una cadena pasada desde el índice especificado a la colección de instancias de la clase NameValueHeaderValue y devuelve la longitud de la subcadena analizada.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | String | Una cadena para analizar. |
| startIndex | int32_t | Una posición inicial para el análisis. |
| delimitador | char16_t | Una cadena que se usa para delimitar elementos en la cadena especificada. |
| nameValueCollection | System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\> | El parámetro de salida donde se asignará una colección analizada. |

### ReturnValue

La longitud de una subcadena analizada.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ObjectCollection](../../objectcollection/)
* Class [NameValueHeaderValue](../)
* Class [NameValueHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
