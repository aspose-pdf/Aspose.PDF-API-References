---
title: "Método System::Net::WebRequest::RegisterPrefix"
linktitle: "RegisterPrefix"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Net::WebRequest::RegisterPrefix. Registra el descendiente de WebRequest para el URI especificado en C++."
type: docs
weight: 600
url: /es/cpp/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix method


Registra el descendiente de [WebRequest](../) para el URI especificado.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefijo | String | El URI o el prefijo del URI. |
| creator | System::SharedPtr\<IWebRequestCreate\> | Crea nuevas instancias de la clase [WebRequest](../). |

### ReturnValue

Verdadero cuando el descendiente de [WebRequest](../) se registra correctamente para el URI especificado, de lo contrario falso.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
