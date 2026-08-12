---
title: "System::Net::Http::Headers::HttpHeaders::TryGetValues method"
linktitle: "TryGetValues"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Net::Http::Headers::HttpHeaders::TryGetValues method. Intenta obtener los valores correspondientes por el nombre especificado en C++."
type: docs
weight: 1900
url: /es/cpp/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues method


Intenta obtener los valores correspondientes por el nombre especificado.

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | String | El nombre de la cabecera. |
| valores | System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\& | Una instancia donde se asignarán los valores correspondientes. |

### ReturnValue

True cuando se encuentran los valores del encabezado por el nombre especificado, de lo contrario false.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [HttpHeaders](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
